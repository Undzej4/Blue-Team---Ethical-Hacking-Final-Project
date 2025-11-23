# Blue-Team---Ethical-Hacking-Final-Project
Ethical Hacking


Projekt realizował pełny cykl pracy pentestera, obejmując analizę plików, łamanie zabezpieczeń, skanowanie podatności, eksplorację systemu oraz eskalację uprawnień. Celem było praktyczne przećwiczenie najważniejszych etapów testów penetracyjnych zgodnych z realnymi scenariuszami spotykanymi w środowiskach laboratoryjnych i produkcyjnych. Zakres działań obejmował zarówno pracę narzędziową, jak i analizę uzyskanych danych, pozwalając na zbudowanie solidnych kompetencji w zakresie cyberbezpieczeństwa.

W projekcie zrealizowano cztery główne zadania: cracking plików, analizę danych, skanowanie podatności oraz eskalację uprawnień

Zakres pracy
1. Cracking Files

W pierwszym etapie projekt koncentrował się na złamaniu zabezpieczonych plików oraz analizie ich zawartości. Zadanie polegało na:

-identyfikacji typu szyfrowania lub zabezpieczenia,

-wykorzystaniu odpowiednich narzędzi do łamania haseł (np. John the Ripper, hashcat),

-analizie uzyskanych danych i wyciąganiu informacji przydatnych w dalszych etapach testów.

Celem było zrozumienie procesów związanych z bezpieczeństwem plików oraz słabości wynikających z niepoprawnego zarządzania hasłami.

2. File Investigation

Drugi moduł obejmował analizę plików i identyfikację danych mogących stanowić wektor ataku. W ramach zadania wykonano:

-analizę metadanych i struktury plików,

-identyfikację ukrytych informacji,

-weryfikację potencjalnych śladów pozostawionych przez użytkowników lub usług,

-pracę na poziomie systemowych atrybutów plików.

Zadanie rozwijało umiejętność zbierania informacji oraz wykrywania pozornie nieistotnych danych, które w rzeczywistych scenariuszach często stanowią kluczowy element w prowadzeniu udanego ataku.

3. Vulnerability Scanning

Trzeci etap polegał na przeprowadzeniu skanowania podatności maszyny docelowej. W ramach pracy:

-wykonano skanowanie sieci oraz portów,

-zidentyfikowano otwarte usługi i możliwe wektory ataku,

-przeprowadzono automatyczną i manualną analizę podatności.

Do dokumentacji wygenerowano raport w formacie XML z wykorzystaniem polecenia:

nmap –oX ~/Desktop/results.xml 192.168.1.102


Celem tego etapu było zrozumienie procesu mapowania infrastruktury i identyfikacji potencjalnych słabych punktów przed podjęciem próby włamania.

4. Privilege Escalation

Ostatni etap polegał na uzyskaniu wyższych uprawnień w zaatakowanym systemie. W ramach zadania:

-wykorzystano uzyskane wcześniej informacje z eksploracji systemu,

-przetestowano wybrane podatności lokalne,

-przeprowadzono eskalację za pomocą narzędzi takich jak Metasploit (adres maszyny zmienił się na 192.168.1.101 po restarcie),

-potwierdzono pełny dostęp administratorski.

Zadanie miało na celu kompleksowe zrozumienie metod przejmowania kontroli nad systemem oraz zabezpieczeń, które powinny chronić przed tego typu atakami.

Efekt końcowy

W efekcie realizacji projektu powstało kompletne środowisko testów penetracyjnych wraz z pełnym łańcuchem ataku:

-złamane i przeanalizowane pliki z zabezpieczeniami,

-zebrane informacje istotne z perspektywy exploitacji,

-szczegółowy skan podatności systemu,

-przeprowadzona eskalacja uprawnień do poziomu administratora,

-udokumentowany proces ataku, nadający się jako materiał do portfolio i dalszej specjalizacji w cyberbezpieczeństwie.

Projekt odzwierciedla pełen proces pracy pentestera – od rekonesansu, przez eksploatację, aż po przejęcie systemu i analizę powłamaniową.
