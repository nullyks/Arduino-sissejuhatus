# Iseseisvad ülesanded

Need ülesanded on mõeldud eelneva materjali põhjal lahendamiseks. Nende abil saad kinnistada oma teadmisi ja oskusi. Iga järgmine ülesanne on veidi keerukam.

## Nupp ja LED
Arduino loeb nupu asendit ja kontrollib LED-i. Kui nupp ei ole alla vajutatud, siis LED ei põle. Kui nupp on alla vajutatud, siis LED põleb.

## Olekuga nupp
Arduino loeb nupuvajutusi. Kui LED ei põle ja nuppu vajutatakse, siis lülitub LED sisse. Kui LED põleb ja nuppu vajutatakse, siis lülitub LED välja.

## Heledust muutev nupp
Arduino loeb nupuvajutusi. Iga nupuvajutus lisab LED-i heledusele 25% võimalikust heledusest. Kui heledus on juba 100% siis nupuvajutus kustutab LED-i.

## Hingav LED
Nupuvajutuse peale muutub LED-i eredus aeglaselt ja sujuvalt väljalülitatud olekust maksimumini ja siis tagasi väljalülitatud olekusse. 

## Kahendloendur
ARduinoga on ühendatud 4 erinevat LED-i ja nupp. LED-id kuvavad nupuvajutuste arvu kahendkoodis - 1 (põleb) ja 0 (ei põle) vasakult paremale. Lugemine algab nullist (ükski LED ei põle) ja lõpeb 15 juures (kõik neli LEDi põlevad). Näiteks:

0 =0000

5 =0101

15=1111 

Kui nuppu on vajutatud rohkem kui 15 korda, siis süttivad LED-id vasakult paremale ükshaaval ja kui kõik neli LEDi põlevad, siis kustuvad nad ükshaaval paremalt vasakule.