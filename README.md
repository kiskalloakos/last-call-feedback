# LAST CALL — magyar közösségi teszt 🤠

**Blöffölj, figyelj a többiekre, és éld túl a szalonban!**

Ez a **Fusionnnn közösségének szánt, ingyenes tesztverzió**. Próbáld ki a játékot botokkal vagy a barátaiddal, és mondd el, mi tetszett, mi volt zavaros, és hol találtál hibát.

[▶ Fusionnnn YouTube-csatornája](https://www.youtube.com/@Fusionnnn/videos) · [💬 Visszajelzés / hibajelentés](https://github.com/kiskalloakos/last-call-feedback/issues/new/choose)

## Letöltés

**Verzió: 0.3.0-feedback.1 · Windows és macOS**

| Rendszer | Letöltés |
|---|---|
| Windows 64 bit | [⬇ Last Call — Windows ZIP](https://github.com/kiskalloakos/last-call-feedback/releases/download/v0.3.0-feedback.1/LastCall-Windows-0.3.0-feedback.1.zip) |
| macOS — Intel és Apple Silicon | [⬇ Last Call — macOS ZIP](https://github.com/kiskalloakos/last-call-feedback/releases/download/v0.3.0-feedback.1/LastCall-macOS-0.3.0-feedback.1.zip) |

A teljes letölthető játék a fenti ZIP-fájlokban van. A GitHub zöld **Code** gombja és a **Source code** ZIP nem a játékot tölti le.

**A játék felülete és oktatása jelenleg angol.** Ez a letöltési oldal és a visszajelzési űrlap magyar.

## Mit tartalmaz a teszt?

- Újrajátszható oktatás (**Tutorial**), amely nem fogyasztja a meccskeretet.
- **Összesen 5 meccs**: a botok elleni, a helyi hálózatos és az online játék közös keretből fogy.
- Barátokkal 4–8 játékos; a hiányzó helyeket igény szerint botok tölthetik fel.
- Beépített visszajelzési hivatkozás és menthető diagnosztikai jelentés.

**Egy meccs a tényleges induláskor fogy el.** A váróterem nem számít, az újrajátszás igen. A félbehagyott meccs is beleszámít; ugyanabba a futó meccsbe történő automatikus visszacsatlakozás nem fogyaszt új alkalmat. A keret játékosonként számít: a csatlakozó vendégnek is szüksége van megmaradt meccsre.

A keret helyben mentődik, újraindítás és azonos kiadású frissítés után is megmarad. Ez egyszerű helyi tesztkorlát, nem fiókhoz kötött jogosultság. Az ötödik meccset végigjátszhatod; utána az oktatás és a visszajelzés továbbra is elérhető.

## Indítás

**Windows:** csomagold ki a teljes ZIP-et egy mappába, majd indítsd a **Last Call.exe** fájlt. A mellette lévő adatkönyvtárat és fájlokat hagyd a helyükön.

**macOS:** csomagold ki a ZIP-et, majd nyisd meg a **Last Call.app** alkalmazást. A teszt nincs Apple által közjegyzőzve (notarizálva); a macOS ezért figyelmeztethet. Megbízható letöltés esetén a **Rendszerbeállítások → Adatvédelem és biztonság** felületén engedélyezhető a megnyitás. A rendszer védelmét ne kapcsold ki.

Elsőre érdemes a **Tutorial** menüponttal kezdeni. A főmenü jobb oldalán láthatod a hátralévő meccseket. A **Graphics settings** menüben csökkentheted a grafikát, ha akadozik a játék.

## Játék a barátokkal

**Mindenki ezt a pontos visszajelzési verziót használja.** A korábbi vagy korlátlan fejlesztői kiadással nem lehet közös szobába lépni.

**Online:** a házigazda az **Online room → Create room** gombbal nyit szobát, és megosztja a kódot. A többiek az **Online room** oldalon beírják a kódot, majd **Join room**. Internet szükséges; a szobának nincs nyilvános játékoskeresője.

**Helyi hálózaton:** azonos hálózatra csatlakozzatok. A házigazda a **Local network → Host LAN** gombbal indít; a többiek a házigazda helyi IP-címével és azonos porttal (**7777**) a **Join LAN** gombbal csatlakoznak. A tűzfalon szükség lehet a játék engedélyezésére a magánhálózaton.

Ha kevesebb mint négyen vagytok, kapcsoljátok be a botokat. Ha mindenki belépett és van megmaradt meccse, a házigazda indíthat.

## Segíts a visszajelzéseddel!

[**Visszajelzés küldése / hiba bejelentése →**](https://github.com/kiskalloakos/last-call-feedback/issues/new/choose)

GitHub-fiók szükséges. Külön űrlap van hibákhoz és játékélményhez. Hasznos, ha leírod, hányan játszottatok, milyen módban, és pontosan mi történt.

Hiba után a főmenüben válaszd a **Diagnosztika mentése** gombot. A játék megnyitja a jelentések mappáját, a fájl elérési útját pedig a vágólapra másolja. Nézd át a `.txt` fájlt, majd húzd be a hibajelentés szövegmezőjébe. Az Escape menü **Visszajelzés** gombja játék közben is megnyitja az űrlapokat.

**Nincs automatikus feltöltés.** A helyi diagnosztika a buildet, platformot, GPU-t, játékszakaszokat, műszaki állapotjelzéseket és megtisztított hibahívási láncokat tartalmazza. Az aktuális és az előző indítás korlátozott méretű naplója marad meg. Nem rögzítünk hangot, és az exportba nem másoljuk át a teljes Unity-logot, játékosneveket, szobakódokat vagy a személyes üzeneteket.

**A GitHub-jelentések és a csatolmányok nyilvánosak.** Ne tölts fel jelszót, e-mail-címet, szobakódot vagy más személyes adatot. Részletek: [adatkezelés](PRIVACY.md).

## Ismert korlátok

Ez fejlesztés alatt álló teszt, hibák és kiegyensúlyozatlanság előfordulhatnak. A botok gyakorlóellenfelek, nem kész, emberi módon gondolkodó ellenfelek. A házigazda kilépésekor a meccs megszakadhat; nincs házigazdaváltás. Rövid kapcsolatvesztéskor ugyanabban a futó kliensben 20 másodperces automatikus visszacsatlakozás van; az alkalmazás újraindítása utáni visszatérés nem támogatott.

Az online kapcsolat és a hangchat külső Unity-szolgáltatásokat használ, amelyek elérhetősége és ingyenes kapacitása korlátozott. A LAN-játékhoz nem kell Relay, a hangchathez internet szükséges. A valós, különböző hálózatokon futó Windows/macOS vegyes meccsekről különösen várjuk a visszajelzést. A minimum hardverigény még nincs megállapítva.

## Felhasználás

Ez a repó letöltésekhez és visszajelzésekhez készült. A teszt ingyenesen kipróbálható; ettől a játék és a benne lévő külső assetek nem válnak nyílt forrásúvá. A kész játék letöltési csomagjának elérhetőségét oszd meg. A nyers assetek kinyerésére vagy újrafelhasználására ez nem ad engedélyt.
