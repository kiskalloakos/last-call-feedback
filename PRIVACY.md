# Adatkezelés — magyar közösségi teszt

A Last Call visszajelzési kiadása nem tölt fel automatikusan hibajelentéseket, diagnosztikai naplókat vagy véleményeket.

A gépeden menti az elhasznált meccsek számát és az utolsó meccs véletlen azonosítóját. Ez akadályozza meg, hogy az újraindítás vagy a visszacsatlakozás új keretet adjon. Az azonosító nem a nevedből vagy a hardveredből készül. A játék a megmaradt keretet a házigazdának is elküldi a meccsindítás ellenőrzéséhez.

Helyben korlátozott műszaki napló készül az aktuális és az előző indításról. A jelentés buildazonosítót, verziót, platformot, operációs rendszert, GPU-nevet, UTC időpontokat, meccskeretet, játékszakaszokat, kapcsolatstatisztikát és megtisztított hibahívási láncokat tartalmazhat. Az önkényes hibaüzenetek és a forrásfájlok útvonalai nem kerülnek a diagnosztikai exportba. A játék szokásos Unity-logja ettől külön létezik; az export azt nem másolja át.

A **Diagnosztika mentése** gomb szövegfájlt hoz létre a játék helyi adatmappájának `FeedbackEdition/Reports` almappájában. Te döntöd el, hogy beküldöd-e. A mentett jelentéseket bármikor törölheted. A jelentések mappáját a gomb megnyitja. A helyi adatok nem kerülnek hozzánk a fájl kézi feltöltése nélkül.

A GitHub Issues felületre beküldött szöveget és csatolmányokat bárki láthatja. Beküldés előtt ellenőrizd a tartalmukat. A GitHub saját adatkezelési feltételei is érvényesek: [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Online játékhoz Unity Authentication és Relay, a hangkommunikációhoz Vivox kapcsolódhat. A játékhang a hangchat működéséhez továbbításra kerül; a visszajelzési funkció nem készít hangfelvételt. A szolgáltatók műszaki adatkezelése külön történik: [Unity Privacy Policy](https://unity.com/legal/privacy-policy).

Adatkezelési kérdéshez használhatod a hibajelentő felületet, de nyilvános bejegyzésben ne adj meg személyes adatokat.
