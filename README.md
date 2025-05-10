## TicTacToe Winner Checker

### Alkalmazás indítása és használata
Az alkalmazást a 'mvn spring-boot:run' paranccsal lehet futtatni.

Indulást követően a command lineban egy filenevet fog kérni és erre a filera vonatkozólag próbálja majd meg eldönteni a verseny nyertesét. Hiba esetén leírja a problémát.
Újabb és újabb fileneveket lehet megadni, majd a 'quit' szócskával ki lehet lépni.

### A bemeneti file tartalma
A bemeneti file a resources folderben kell elhelyezkedjen (itt megtalalható néhány teszt file). Először maga a játéktábla szerepel a fileban. A file utolsó sora a győzelemhez szükséges pontok számát jelöli.

### Megjegyzések
A test fileok tartalmának kigenerálásában használtam némi AI-t, ezek a fileok többször kicsit esetleneknek tűnnek és nem fednek le minden teszt esetet, de alapvető tesztelésre hasznosnak bizonyultak.
Következő lépésként még több teszt esetet kipróbálnék és lefedném a unit tesztekkel a még hiányzó részeket.