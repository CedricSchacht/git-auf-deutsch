# Git up Platt

De dagelke Spraakgebruch im dütsche Verloopteem, de git (oversett: Dööskopp) bruken, is faken dat krodde Denglish. "Kannst du bitte pullen" oder "Hast du gepusht" sind blot twee de faak putzig klingen Upbau.

Git up platt helpen da!

## Vörslagen

Da folgen twee Tabell mit Vörslagen för den dagelk Gebruuk.

| Verb        | Nu wart brukt | Vörslag               |
|-------------|---------------------|-----------------------|
| init        | initten             | updoon                |
| add         | adden               | daarandoon            |
| blame       | blamen              | ankleien              |
| pull        | pullen              | torren                |
| push        | pushen              | schuven               |
| clone       | clonen              | namaken               |
| fetch       | fetchen             | halen                 |
| branch      | branchen            | utnannerhauen         |
| commit      | commiten            | fastleggen            |
| rebase      | rebasen             | maken                 |
| diff        | diffen              | verglieken            |
| merge       | mergen              | tosamenbinnen         |
| fork        | forken              | ofsplieten            |
| stash       | stashen             | verkrupen             |
| tag         | taggen              | markeren              |
| cherry-pick | cherry-picken       | Sienbohn bicken       |
| checkout    | checkouten          | nehmen                |

| Substantiv    | Derzeit wird bruken | Vörslag               |
|---------------|---------------------|-----------------------|
| git           | git                 | Dööskopp              |
| github        | github              | Dööskopp-Bude         |
| gitlab        | gitlab              | Dööskopp-Labor        |
| gitea         | gitea               | Dööskopp-Trecksel     |
| blame         | blame               | Dööskopp wrögen       |
| bitbucket     | bitbucket           | Mahlwark Emmer        |
| repository    | repo                | Lagerhuus             |
| branch        | branch              | Tack                  |
| commit        | commit              | Stüren                |
| log           | log                 | Daagboken             |
| pull request  | pull request        | hebben will           |
| merge request | merge request       | Andrag tohoop brengen |
| stash         | stash               | Versteek              |
| status        | status              | Tostand               |
| tag           | tag                 | Marke                 |
| origin        | origin              | Begünn                |
| master        | master              | Baas                  |

## Bispillen

    - Kannst de Tack, den ik even umschrieven hebb, torren un zur Dööskopp-Bude schuven?
    
    - Daför heb ik een nee Lagerhuus opmaken, mook de na un nimm di de Verlooptwieg.
    
    - Nee, knuddel dat gliek to Baas im Begünn!
       
    - Du kannst in de Dööskopp wrögen kieken, de dat annern hat.

    - Ik hebb even abgetwiegt un de Ännerungen ut mien Versteek övergeven.
    
    - Mak en Andrag tohoop brengen, so du mit de Verenigung klaarworden bist!
    
    - An allerbest wi bicken de Sienbohnen up de Baastack rut.
    
    - Gabel up Dööskopp-Bude!

## Dööskopp op Platt anwennen

Well de nahste Stapp moken will, hier een Anwies, de Dööskopp up Platt in dien Konsole brengen. Da Dööskopp keen Umlaute tolaten, moten wi in de Befehlen leider daarup verzichten. Nimm de Ännerungen in dien ~/.gitconfig vör:

    git config --global alias.updoon init
    git config --global alias.namaken clone
    git config --global alias.torren pull
    git config --global alias.daarandoon add
    git config --global alias.schuven push
    git config --global alias.utnannerhauen branch
    git config --global alias.fastleggen commit
    git config --global alias.maken rebase
    git config --global alias.verglieken diff
    git config --global alias.tosamenbinnen merge
    git config --global alias.versteken stash
    git config --global alias.markeren tag
    git config --global alias.nehmen checkout
    git config --global alias.daagboken log
    git config --global alias.tostand status

Un pack de anner Rieg to diener ~/.bashrc (of wie dat up dien Betriebssystem benömen):

    alias doeoeskopp=git
