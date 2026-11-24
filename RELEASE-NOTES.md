# Magyar közösségi teszt — 0.3.0-feedback.1

A Fusionnnn közösségének készült, ingyenes Last Call tesztkiadás.

- **Összesen 5 meccs játékosonként**, közös keretből: botok, LAN és online.
- A tényleges meccsindítás számít; a váróterem és ugyanabba a futó meccsbe történő visszacsatlakozás nem. A félbehagyott meccs és az újrajátszás beleszámít.
- Az oktatás nem fogyaszt meccset, és a keret lejárta után is újrajátszható.
- A keret helyben megmarad újraindítás és frissítés után. Ez nem fiókhoz kötött, manipulációbiztos korlát.
- Magyar visszajelzési hivatkozás, menthető diagnosztika, magyar letöltési útmutató és GitHub-űrlapok.
- **A játék felülete és oktatása angol.**

## Letöltés és indítás

Töltsd le a rendszeredhez tartozó **LastCall-Windows-…zip** vagy **LastCall-macOS-…zip** fájlt, és csomagold ki teljesen. A mappán belül indítsd a **Last Call.exe** vagy **Last Call.app** fájlt. A **Source code** archívum nem tartalmazza a játékot.

A Windows-csomag 64 bites; a Mac-csomag Intel és Apple Silicon gépekhez készült. A Mac-alkalmazás nincs notarizálva. Minimum hardverigényt még nem állapítottunk meg.

[Magyar útmutató és ismert korlátok](https://github.com/kiskalloakos/last-call-feedback#readme) · [Visszajelzés / hibajelentés](https://github.com/kiskalloakos/last-call-feedback/issues/new/choose) · [Fusionnnn YouTube](https://www.youtube.com/@Fusionnnn/videos)

## Ellenőrzés és tesztkorlátok

A visszajelzési ellenőrző buildben sikeres: az ötmeccses keret, mentésből visszatöltés, hatodik meccs tiltása, ingyenes oktatás lejárt kerettel, diagnosztikai export, valamint négy külön folyamat három teljes LAN- és online Relay-köre. Minden résztvevőnél pontosan egy meccs fogyott. A kiadott Mac-build főmenüjét külön is megnyitottuk és ellenőriztük.

**Ez a Windows-csomag keresztfordítással készült; a konkrét kiadás Windows gépen történő futtatása még ellenőrzésre vár.** A különböző fizikai gépeken és különböző hálózatokon történő vegyes Windows/Mac játék szintén közösségi tesztelést igényel.

A diagnosztika helyben mentődik; nincs automatikus feltöltés. A jelentést átnézés után kézzel csatolhatod. A GitHub-bejegyzés és a csatolmány nyilvános.

Az online szolgáltatások ingyenes kapacitása korlátozott. Nincs nyilvános játékoskereső vagy házigazdaváltás. A korlátlan fejlesztői és a visszajelzési build külön hálózati kiadás: mindenki ezt a pontos verziót használja.

A letöltések SHA-256 ellenőrzőösszegeit a mellékelt **SHA256SUMS.txt** tartalmazza.
