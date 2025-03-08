# Iseseisvad ülesanded

Need ülesanded on mõeldud eelneva materjali põhjal lahendamiseks. Nende abil saad kinnistada oma teadmisi ja oskusi. Iga järgmine ülesanne on veidi keerukam.

## Nupp ja LED
Arduino loeb nupu asendit ja kontrollib LED-i. Kui nupp ei ole alla vajutatud, siis LED ei põle. Kui nupp on alla vajutatud, siis LED põleb.

[lahendus](https://www.tinkercad.com/things/9l0rDFltzT4-nupp-ja-led?sharecode=bk84U0YjR3kWApF88ORda8i7SK_ZtOPXiAPhRJYBXpg)

## Olekuga nupp
Arduino loeb nupuvajutusi. Kui LED ei põle ja nuppu vajutatakse, siis lülitub LED sisse. Kui LED põleb ja nuppu vajutatakse, siis lülitub LED välja.

[lahendus](https://www.tinkercad.com/things/jXDQBt10gAq-olekuga-nupp?sharecode=srv3PYnvZ-xr6ylmtvC2i9YQ01RoV6y4rb00E3xj4XE)

## Heledust muutev nupp
Arduino loeb nupuvajutusi. Iga nupuvajutus lisab LED-i heledusele 25% võimalikust heledusest. Kui heledus on juba 100% siis nupuvajutus kustutab LED-i.

[lahendus](https://www.tinkercad.com/things/4XiXp281psc-heledust-muutev-nupp?sharecode=fjMyfPgJl3_Ctr1pFQtSHfZNjkkJY5qVPf3NNxl9Zl8)

## Hingav LED
Nupuvajutuse peale muutub LED-i eredus aeglaselt ja sujuvalt väljalülitatud olekust maksimumini ja siis tagasi väljalülitatud olekusse. 

[lahendus](https://www.tinkercad.com/things/d2uubpWH6zj-hingav-led?sharecode=LhseibitcLsEhBG9mwv8kNeDwZl3mTPgr0h4SjjZWeA)

## Kahendloendur
Arduinoga on ühendatud 4 erinevat LED-i ja nupp. LED-id kuvavad nupuvajutuste arvu kahendkoodis - 1 (põleb) ja 0 (ei põle) vasakult paremale. Lugemine algab nullist (ükski LED ei põle) ja lõpeb 15 juures (kõik neli LEDi põlevad). Näiteks:

0 =0000

5 =0101

15=1111 

Kui nuppu on vajutatud rohkem kui 15 korda, siis süttivad LED-id vasakult paremale ükshaaval ja kui kõik neli LEDi põlevad, siis kustuvad nad ükshaaval paremalt vasakule.

[lahendus](https://www.tinkercad.com/things/0DeejZOl6Nv-kahendloendur?sharecode=3cR3hum_A3xtbrMDLQbkrvKebYimY_yVHq-bmemrtqQ)