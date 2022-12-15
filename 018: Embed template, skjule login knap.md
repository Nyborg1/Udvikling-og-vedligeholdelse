# [018]: Mulighed for at skjule login knap i embed template

## 1. Motivation
Når man oprererer med brugerstyring i config fil, vil det være en fordel at man kan anvende samme config til embed. Dette medfører at der vises login knap i hjemmesiden og dette er ikke altid ønskeligt. Der efterlyses en mulighed for at angive at hængelåsen i embed template skjules med tag 'data-vidi-...'

## 2. Foreslået løsning
Der laves en ny tag 'data-vidi-...'

## 3. Problemer med bagudkompatibilitet
Ingen.
I dag findes en workaournd som medfører at man må have to configfiler. dene ene bruges til vidi administation af projekter/tokens. den anden peger på en ekstern css fil der skjuler hængelåsen .

## 4. Sikkerhedsmæssige implikationer
Ingen.

## 5. Performance-implikationer
Ingen.

## 6. Dokumentationsbehov
Skal dokumenteres. https://vidi.readthedocs.io/da/latest/pages/standard/95_embed.html#indlejring-af-vidi

## 7. Arbejdsnoter

## 8. Issue tracker  

## 9. Tilsagn/tilkendegivelse
Nyborg kommune+

