# 2023rpiproject
## Beschrijving
Cursus RPI2 SNT Brugge, uitwerken eigen project. Na het ingeven van een toegangscode op een Yale Acces module (toegang vakantiewoning), wens ik een display(tv) te laten starten waarop een welkomscherm de bezoeker welkom heet met de nodige info. Een aangepast sfeermuziekje starten of het favoriete nummer afspelen van de bezoeker is ook een gewenste actie.
Een koppeling maken van de Yale app met Homebridge zal de eerste stap zijn.
Als infoscherm koos ik voor het Smartmirror project.
Als muziekspeler integreer ik een spotify module/speaker.

update 28/2/2023. Binnen de koppeling naar homebridge blijkt het eigen dashboard minstens over de capaciteiten te beschikken die ik nodig heb.

## Bronnen
- https://www.yalehome.com/us/en/products/smart-technology/yale-access
- https://homebridge.io/raspberry-pi-image
- https://gist.github.com/LimeBlast/1574e0e141e4be43b37e
- https://magicmirror.builders/
- https://www.npmjs.com/package/homebridge-rusty-spotify
- https://developers.homebridge.io/#/service/Door
- https://www.audkit.com/spotify-music/spotify-on-raspberry-pi.html
- https://www.reddit.com/r/homebridge/comments/stj5kb/homebridge_spotify_speaker/
- https://forums.raspberrypi.com/viewtopic.php?t=151328
- https://developper.spotify.com



## Hardware
- Yale deurslot, bridge & codeklavier
- raspberry pi3 
- bestaande tv
- apple tv module

## Software
- Yale Acces app
- Homebridge Raspberry Pi Image 
- MagicMirror (+ modules)


### Eigen scripts en programma's
Sla je als aparte bestanden op in deze repository

https://nl.ephesossoftware.com/articles/diy/4-best-raspberry-pi-smart-tv-projects-weve-seen-so-far.html

## Planning & uitvoering
- 17/01/2023 Homebridge installeren, account aanmaken
- 24/01/2023 MagicMirror instellen
- - klok instellen (standaard aanwezig-clock)
- - welkomsttekst instellen (standaard aanwezig-helloworld)
- - weerbericht instellen op locatie (standaard aanwezig-weather)
- - google foto als achtergrond instellen (extra modules toevoegen-MMM-GooglePhotos)
- - wifi code op display zetten
- - muziekspeler instellen
- 31/1/2023 fine tuning maggic mirror
- 07/02/2023 Connectie tussen homebridge/yale/iphone (niet aanwezig in de les, opdracht extern gedaan tijdens de week)
- connectie werkt naar behoren, scene instellen lukt, maar bij keuze om muziek af te spelen bij input van het deurslot, krijg ik enkele de keuze om dit via apple music te doen (betalend)
- ik beschik over een spotify account, of wens via youtube video af te spelen.
- 14/02/2023 Homebridge spotify connecteren. Spotify API aanvragen.
- 28/02/2023 Homebridge verder instellen. Door het zoeken op Github kwam ik tot de vaststelling dat ook Homebridge zelf een mooi grafisch dashboard ter beschikking heeft, die je als aparte module kan installeren. Binnen de modules kan je ongeveer hetzelfde instellen zoals en weergeven zoals op een magicmirror + je krijgt rechtstreeks controle over je homedbridge devices.
