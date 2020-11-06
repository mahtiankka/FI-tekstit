# Variety 0.8.3

Käännös valmiina käyttöönne, olkaa hyvä.

Pakattu kansio sisältää kaksi tiedostoa.

Valmiin (fi.po) suomikäännöksen Variety ohjelmasta. Voit editoida ja muuttaa tiedostoa/käännöstä poedit ohjelmalla. 

Valmis (variety.mo) muotoon käännetty kielipaketti, jonka kopioidaan kohteeseen;
/usr/share/locale/fi/LC_MESSAGES/variety.mo

Käynnistä Variety uudelleen ja ympäristö on suomenkielinen.

Variety mietelauseisiin tai teeseihin muutoksia.

Jos haluat tehdä itse oman txt-tiedoston josta ohjelma lataa viisaita ajatuksia. Lisää .config/variety/ kasioon kaksi uutta kansiota, jotka olen lisännyt.
Tiesostoon pluginconfig/quotes/quotes.txt voit kirjoittaa omia lisäyksiä mallin mukaan.
Lisää .config/variety/plugins/quotes kansio, johon olen lisännyt Python skriptit joilla lainaukset toimii.

LocalFileSource.py tiedostoon muutin UTF-8 näppäimistökartan malliin muotoon ISO-8859-15 niin nyt myös ää ja öö näkyy.

Kansio .config/variety sisältää tiedoston variety.conf jossa ovat kaikki asetukset.
Jos lainaukset eivät näy ruudulla järkevänä tekstinä niin syynä on se, ettei fonttia ole asennettu koneeseen.
Etsi variety.conf sisältä rivi quotes_font ja kirjoita fontin nimi joka löytyy kuten alla.
quotes_font = "Ubuntu Condensed, 20"

Variety v0.8.3 Linux Mint 20 Cinnamon.
Testattu 6.11.2020

Valmistajan kotisivu:
https://peterlevi.com/variety/

GitHub:
https://github.com/varietywalls/variety

Lisenssi:
GNU GPL Version 3
