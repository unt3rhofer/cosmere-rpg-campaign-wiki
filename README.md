# session-recaps
## File naming
- ako je novi session, datoteka se naslovljuje sa `session-<troznamenkasti-redni-broj-sessiona-s-vodećim-nulama>.md`
- ako je novi interlude, datoteka se naslovljuje s `interlude-<troznamenkasti-redni-broj-interlude-s-vodećim-nulama>.md`
## Content
- prva linija: `#<episode_id>: <episode_title>`
  - episode_id = S<season_number>E<episode_number_in_season>
  - episode_title = proizvoljan naslov epizode
- druga linija: `#<date_of_session>`
  - date_of_session: datum sessiona u DD.MM.YYYY. formatu
# Characters
## File naming
- ako je novi character, naziv datoteke je ime charactera zapisano malim slovima sa znakom `-` u ulozi whitespacea
- ako je novi faction, naziv datoteke je ime factiona zapisano malim slovima sa znakom `-` u ulozi whitespacea
## Content
- prva linija: `#<character_name>`
  - character_name: puno ime charactera 
- tablica
``` markdown
| Attribute | Details |
|---|---|
| **Occupation** | |
| **Location** | |
| **Affiliation** | |
```
  - Occupation: najkraći mogući opis onoga čime se character bavi. Pokušati ne prelaziti tri rijeći
  - Location: poveznica na markdown datoteku lokacije gdje se character nalazi
  - Affiliation: poveznica na fakciju kojoj character pripada ili na individualne charactere s kojima je povezan
- bilješke, `## Notes`
  - slobodan tekst o characteru ako je potrebno
# Locations
## File naming
- ime datoteke je malim slovima napisano ime te lokacije, nije bitno je li drzava, grad, taverna, hram ili poljski wc sa znakom `-` u ulozi whitespacea
## Structure
 