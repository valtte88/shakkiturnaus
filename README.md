#Shakkiturnaus

Vaihtoehto Swiss-manager ohjelmalle 1-N ryhmän sveitsiläiseen ja/tai round-robin turnaukseen. Mahdollisesti myös vahvuuslukulaskentaa samaan.

v1..v3: Tehty Claude 4.6:lla lyhyellä promptilla. Korjattu paritusalgoritmia Gemini 3.1:llä.
...v7: Lisäilty ominaisuuksia Claude 4.6

Ei taida sisältää ollenkaan käsin kirjoitettua koodia (v3 ja v7). Prompteja yms. saattaa olla jossain tallessa. Ainakin Gemini perusteli paritusalgoritmia yksityiskohtaisesti, mutta en perehtynyt.

Jatko:

A) Kokonaan puhtaalta pöydältä käsin?
B) Alusta asti, mutta huolellisella promptilla?
C) Tästä muokkaamalla loppuun asti?

Haasteita:

- Drag-and-drop todennäköisesti vain sekoittaa ja vaarantaa turnauksen luotettavuuden => pois kokonaan?
- Nyt muuttujat selaimen välimuistissa. Sekaantumisen vaara melkoinen. Voisiko muuttujia tallentaa esimerkiksi automaattiseti aina kun paritetaan seuraava kierros json fileen?
- Muokattavuus ei ole ehkä parasta A ryhmää?
