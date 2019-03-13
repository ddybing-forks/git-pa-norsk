# Git på norsk

## Takk til
* [Bjorne](https://github.com/bjorne). Det er tatt utgangspunkt i Björns ["git-på-svenska"](https://github.com/bjorne/git-pa-svenska) hva gjelder både idè og layout. 

## Forslag til fornorsking

Nedan följer tabeller över verb och substantiv relaterade till git,
deras nuvarande bruk samt förslag på hur vi tillsammans kan bättra
oss.

| Verb        | Nåværende      | Forslag       |
|-------------|----------------|---------------|
| pull        | pulle          | rycka         |
| push        | pushe          | dytte         |
| fetch       | fetche         | hente         |
| branch      | branche        | forgrene      |
| commit      | commite        | förbinda      |
| rebase      | rebase         | ympa          |
| merge       | merge          | sammenføye    |
| squash      | squashe        | knuse         |
| stash       | stashe         | gjemme        |
| tag         | tagge          | merke         |
| cherry-pick | cherry-picke   | kirsebærplukk |
| amend       | amende         | rätta till    |
| blame       | blame          | klandre       |

| Substantiv   | Nåværende      | Forslag     |
|--------------|----------------|-------------|
| git          | git            | jävel       |
| repository   | repo           | förvaring   |
| branch       | branch         | gren        |
| commit       | commit         | förbindelse |
| pull request | pull request   | ryckbegäran |
| stash        | stash          | gjemme      |
| tag          | tagg           | merke       |

## Eksempler

    - Kan du rycka grenen jag just ympade och knuffa till github?

    - Jag förgrenade alldeles nyss och förband ändringarna från min gömma där.

    - Skicka en ryckbegäran när du är färdig med sammanfogningen!

    - Låt oss plocka russin från mäster-grenen.
    
    - Hoppsan, jag råkade visst kraftknuffa mot mäster-grenen.. D:

    - Mosa dina förbindelser innan du sammanfogar.

## Dagligt bruk

Nedan följer en rad kommandoradskommandon för att sätta upp en svensk
gitmiljö. Avsaknaden av svenska tecken i täcknamnen beror på en brist i git
(överväg att förbättra mjukvaran och skicka en ryckbegäran!). Följande
kommandon ändrar din `~/.gitconfig` och kommer att verka globalt.

    git config --global alias.ryck pull
    git config --global alias.knuffa push
    git config --global alias.gren branch
    git config --global alias.forgrena branch
    git config --global alias.forbinda commit
    git config --global alias.ympa rebase
    git config --global alias.sammanfoga merge
    git config --global alias.gom stash
    git config --global alias.klandra blame
    git config --global alias.marke tag
    git config --global alias.mark tag

    alias jävel=git
