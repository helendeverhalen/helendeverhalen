# Website beheren

Ga naar <https://app.cloudcannon.com/> om de tekst op de pagina's te veranderen in een zogenaamde "rich-text editor".


## Syntax

Er zijn wat truckjes in markdown om plaatjes en links op te nemen.

    [omschrijving link](/link/naar/ergens/in/assets)

Bijv.:

    [coulancebrief](/assets/downloads/coulancebrief.pdf)

Om een plaatje ergens op te nemen, gebruik:

    ![Omschrijving plaatje](/assets/images/plaatje.extensie)

Om een plaatje met een link te gebruiken:

    [![omschrijving link](/assets/images/plaatje.extensie)](http://link)

Om quotes te gebruiken rondom een tekst, gebruik geen aanhalingstekens, maar begin met een accent grave:

    `tekst'

Om te refereren naar iets op de site, bijvoorbeeld de contact pagina, gebruik "curly brackets". Probeer niet de naam
van de website te gebruiken, maar `site.url`:

    [contact]({{ site.url }}/contact)

## Lokaties

Er zijn eigenlijk maar twee lokaties om te onthouden. Stop plaatjes in de map `/assets/images` en documenten in de map `/assets/downloads`.




