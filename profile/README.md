![Github Banner](/profile/banner.jpg)

## Who are we?

```php
 namespace CMCA;
 use World\Countries;

 class WhoAreWe{
    public string $name = "China-Maldivian Cultural Association";
    public string $type = "NGO";
    public array $operating_in = [
        Countries::Maldives,
        Countries::China,
    ];
    public string $founder = "Mohamed Rasheed";

    public function getFoundersMessage():string
    {
        return <<<MSG
        On behalf of our great Team, I would like to welcome you to China-Maldivian Cultural Association.

        Our Association is a platform for the youth of Maldives to foster global awareness,
        creating opportunities for international collaboration, and develop skill sets that bridge and
        celebrates relationships between the peoples of Maldives and China through arts and culture.
        Our aim is to promote multiculturism. We avail opportunities to the youth of Maldives to have
        firsthand experience of the ancient culture and heritage of China.
        The founding of China-Maldivian Cultural Association is a lifelong dream of myself as a student at
        National Taiwan University during 1970s.
        MSG;
    }
    public function getMission(): string
    {
        return "The mission of China-Maldivian Cultural Association ( CMCA ) is to create a platform for youth
        to foster global awareness, to create opportunities for international collaboration, and to develop
        skill sets that bridge and celebrate relationships between the peoples of China and Maldives through
        arts and culture.";
    }
    public function getOurStory():string
    {
        return <<<STORY
        Since it's creation in December 2015, CMCA has forged partnerships with United Artists of Maldives,
        National Center for the Arts, Shaanxi Han Tang Cultural Creative Institute, The China Soong Ching Ling
        Foundation, China Peoples Association for Friendship with Foreign Countries, Beijing People’s Association
        for Friendship with Foreign Countries and Beijing International Peace Cultural Foundation.

        The year of 2016 was as tremendous for CMCA. We held our very first flagship program, the Youth Exchange
        Visit Program, which brought a group of Maldivian youth delegates to Beijing in December.

        The program provided these youth delegates an opportunity to sojourn through the cultural and historical
        sites of Beijing.

        Prior to December, CMCA programming staff participated in China Soong Ching Ling International Youth Camp in
        July experienced international collaboration through arts and culture that took them to Beijing, Shanghai,
        and Inner Mongolia.

        The year also marked the first Chinese Calligraphy workshop in the Maldives. All these programs affirm
        CMCA's mission.

        We believe that an exchange through arts and culture provides unique opportunities for youth to develop
        understanding and appreciation for the peoples and histories of China as well as the Maldives. This in
        return will strengthen our countries' friendship for the years to come.
        STORY;
    }
 }

```
