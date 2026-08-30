# Sissejuhatus Arduino arendusplaatide kasutamisse

See õppematerjal kajastab Arduino arendusplaadi kasutuselevõtmist. Materjalis selgitatakse, kuidas paigaldada ja seadistada vajalik tarkvara, ühendada arendusplaat arvutiga ning laadida arendusplaadile oma programm.

Samuti annab materjal kiire ülevaate Arduino arendusplaadi viikudest ning nende kasutamisest. Materjalis demonstreeritakse nupuvajutuse lugemist ja LED-i sisse ja välja lülitamist.

## Kasutatavad arendusplaadid

Kursusel kasutatakse läbisegi Arduino UNO R3 ja Arduino UNO R4 WiFi arendusplaate. Õppematerjali ühendusskeemid ja Tinkercadi näited on koostatud UNO R3 jaoks.

Näidetes kasutatavad viigud ja funktsioonid töötavad ka UNO R4 WiFi plaadil: mõlemad kasutavad 5 V loogikataset ning neil on samades kohtades digitaalviigud D0-D13, analoogviigud A0-A5 ja PWM-viigud D3, D5, D6, D9, D10 ning D11. PWM (ingl *pulse width modulation*) tähendab pikkusmodulatsiooni; kasutatakse ka termineid *pulsilaiusmodulatsioon* ja *impulsslaiusmodulatsioon*. Plaatide olulised erinevused tuuakse materjalis eraldi välja.

| Erinevus | Arduino UNO R3 | Arduino UNO R4 WiFi |
|---|---|---|
| USB-pistik | USB-B | USB-C |
| Arduino IDE plaadipakett | Arduino AVR Boards | Arduino UNO R4 Boards |
| Plaadi nimi Arduino IDE-s | Arduino Uno | Arduino UNO R4 WiFi |
| Suurim soovituslik vool ühe I/O-viigu kaudu | 20 mA | 8 mA |
| ADC | 10 bitti (0-1023) | vaikimisi 10 bitti (0-1023), kuni 14 bitti (0-16383) |

Kolmanda tootja UNO R3-ga ühilduvatel plaatidel võib USB-pistik ja USB-liidese kiip erineda. Täpsema võrdluse leiab [Arduino UNO R3 ja UNO R4 ametlikust võrdlusest](https://support.arduino.cc/hc/en-us/articles/9350551575964-What-s-the-difference-between-UNO-R3-and-UNO-R4-boards).

## Õpieesmärgid
Peale selle õppematerjali läbimist oskad paigaldada ja seadistada Arduino arendusplaatide kasutamiseks vajaliku tarkvara. Saad teada, kuidas arendusplaat arvutiga ühendada ja laadida sellele enda kirjutatud programm. Oskad teha vahet olulisematel Arduino arendusplaadi ühendusviikudel ja lugeda nende kaudu nupuvajutust ning juhtida LED-i.

## Õpiväljundid

Materjali edukalt läbinud õppija oskab:

*   paigaldada ja seadistada Arduino arendusplaadi kasutamiseks vajalikku tarkvara;
*   ühendada Arduino arendusplaadi arvutiga ja laadida arendusplaadile oma programmi;
*   eristada Arduino arendusplaadi viike ja selgitada nende kasutusvaldkondi;
*   Arduino arendusplaadiga ühendada nupu ja lugeda nupuvajutust;
*   Arduino arendusplaadiga ühendada LED-i ja seda juhtida;

## Hindamisjuhend
Selle õppematerjali puhul ei rakendata eristavat hindamist. 

Õppija on materjali omandanud, kui ta on iseseisvalt võimeline lahendama vähemalt neli iseseisvat ülesannet viiest. Korrektse lahenduse juurde kuulub seadmete ühendusjoonis ja kommenteeritud programmikood.

## Vajalikud vahendid

*   1 x personaalarvuti (sobib nii Windowsi, Linuxi kui ka macOS-iga)
*   1 x Arduino UNO R3 või Arduino UNO R4 WiFi arendusplaat
*   1 x plaadile sobiv USB-andmesidekaabel (UNO R3 puhul tavaliselt USB-B, UNO R4 WiFi puhul USB-C)
*   4 x LED (soovitavalt erivärvilised)
*   4 x takisti (470 Ω)
*   1 x makettplaat
*   1 x nupp (makettplaadiga ühilduv)
*   makettplaadi juhtmed (isane-isane)

## Õppematerjali osad

*   [Arduino IDE tarkvara paigaldamine ja seadistamine](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/1_Tarkvara_paigaldamine_ja_seadistamine.md)
*   [Arduino arendusplaadi ühendamine arvutiga ja programmi laadimine arendusplaadile](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/2_Ühendamine_ja_üleslaadimine.md)
*   [Arduino UNO arendusplaadi tähtsamad viigud](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/3_Arduino_UNO_viigud.md)
*   [Nupu lugemine](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/4_Nupu_lugemine.md)
*   [LED-i juhtimine](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/5_LED_juhtimine.md)
*   [Iseseisvad ülesanded](https://github.com/nullyks/Arduino-sissejuhatus/blob/main/materjalid/6_Iseseisvad_ülesanded.md)

## Õppematerjali koostajad

Tanel Toova (tanel.toova@tlu.ee)
