# Model generujący bajkę dla dzieci

## Wybrane teksty do nauki modelu – Bajki braci Grimm
❖Braciszek i siostrzyczka
❖Czerwony kapturek
❖Jaś i Małgosia
❖Jednooczka, Dwuoczkoa, Trzyoczka
❖Kopciuszek
❖Król Drozdobrody
❖Król Żab
❖O czterech muzykantach z Bremy
❖Paluszek
❖Roszpunka
❖Stoliczku, nakryj się!
❖Śnieżka
❖Titelitury

Źródło bajek: Strona internetowa WolneLektury.pl https://wolnelektury.pl/katalog/lektury/basnie-bajki-bajeczki/

## Proste statystyki dotyczące bajek
Ilość bajek: 13. 
Ilość słów we wszystkich bajkach 22747. 
Ilość zdań we wszystkich bajkach 1491

## Zastosowane techniki
1. Biblioteka spaCy (podział tekstu na słowa i na zdania oraz przypisywanie POS tagów).
2. N-gramy (stworzenie trigramów oraz bigramów).
3. Stworzenie słownika z prawdopodobieństwami przejść (wyznaczenie prawdopodobieństwa
wystąpienia danego trzeciego słowa po dwóch podanych –trigramy; lub prawdopodobieństwa
wystąpienia drugiego słowa po jednym podanym – bigramy).
4. Hierarchiczne wybieranie kolejnego słowa (w przypadku gdy nie istnieje trigram zawierający dwa
poprzednie słowa kolejne słowo wybierane jest w oparciu o istniejący bigram).
5. Tworzenie zdań o losowej długości (losowano z rozkładu Gaussa o średniej i odchyleniu
standardowym obliczonym dla długości zdań we wszystkich bajkach).
6. Dodano możliwość zaczynania zdań od konkretnych dwóch słów (np. Pewnego razu).

## Przykład wygenerowanego tekstu (bez zadanego początku)
Niej pewnego razu przyszły do niej i rzekła — posiedźcie tu dzieci a. Znowu wreszcie jednak siły jego wyczerpały się i uradował bardzo
ale oni byli bardzo życzliwi i. Fałszywa królowa kiedy nadeszła północ i wszyscy posnęli piastunka siedząca nad kołyską ujrzała nagle jak otwierają się drzwi i zawołała — u tego pięknego młodzieńca lepiej by mi było niż u starej czarownicy ”. Rzuciły się ojcu na szyję a z sitowia ukręciła miękki sznur uwiązała zwierzątko i ruszyła z. Las tymczasem wilk pobiegł prosto do domku babci i zapukał do drzwi i wchodzi prawdziwa królowa wyjęła dziecko z kołyski i nakarmiła je potem poprawiła mu poduszeczkę ułożyła je. Stajni uprowadził
złotodajnego osiołka i podstawił innego nazajutrz młodzieniec wyruszył ze swoim osiołkiem w dalszą drogę ale do miasta było. Gwiazdy
na niebie. Ci zaraz z oczu co powiedziawszy wlazła na drzewo ale i z całych sił uderzyła nią o ścianę — teraz możemy się posilić ja zjem sobie kawałek dachu a ty weźmiesz mnie na. Stamtąd malca — ach trudno jej z drogi bo mogłabyś upaść i stłuc butelkę kiedy zaś
przyszedł karzełek i. Już gotowa to ci szczęście przyniesie mądra kobieta odeszła. Ziemię poczęły się osiołkowi sypać z pyska i spod ogona złote dukaty — ej rycerzu z czerwonym rumieńcem ty zjesz a tę żółtą zjem. Zupełnie opuszczony domek „ tutaj możemy zamieszkać ” — i kazał żonie wstać i zabrać się do roboty tylko je zbierał z ziemi gdziekolwiek przyszedł przyjmowano go chętnie gdyż zawsze miał pełną sakiewkę kiedy. Zmartwiła się ale twarde patyki pokrwawiły jej delikatne ręce — widzę stół nakryty a na to uwagi śpieszyła do domu i prosi siostry — za. Podarunku stolik który wyglądał jak każdy inny stolik ale miał jedną. Gałąź którą przywiązał drwal do drzewa i którą wiatr uderzał o drzewo po pewnym czasie ujrzeli kota siedzącego na drodze z miną strapioną — no cóż. Murem i nikt. Tyle ile tylko mógł zmieścić w kieszeniach kamyki po chwili ujrzeli oświetlone okno domu. Przeto nieuznawana przez siostry ale nie wiem jak wejść do mnie następnym razem przynieś z sobą chustkę karczmarz był ciekaw co to ma znaczyć pobiegł. Chustkę pełno dukatów zaproś tylko
wszystkich krewnych i przyjaciół a wnet zjawią się na przyszłość po czym zawołał — stoliczku nakryj się w ten sposób że zawsze trafiała w próżnię co widząc dwuoczka rzecze — wejdę i ja tego. Tuż przy jej.

## Przykład wygenerowane tekstu (z zadanym początkiem "Pewnego razu")
Pewnego razu stał za drzewem ujrzał czarownicę która zawołała szyderczo — aha przybyłeś po swą ukochaną ale ptaszek nie śpiewa już. I
zdało mu się nagle i ukazał się w ten sposób pozbędziemy się ich — nie dawajcie mi więcej siana nie dawajcie mi więcej siana nie dawajcie mi więcej siana służąca doiła właśnie krowę. Czekał go inny los tak na świecie zdarzają się różne nieszczęścia o świcie musimy
wyprowadzić dzieci do lasu gdzie ją rozszarpały dzikie zwierzęta i tak przebrana poszła za. Tu jeszcze dwa razy powtarzać a co
najdziwniejsza że gdy się zbliżył do niej dwie ubogie kobiety z prośbą o wsparcie dwuoczka przyjrzała im się z. Paszy dwuoczka od razu
bo więcej nic. Wysypała z fartuszka perły i drogie kamienie które potoczyły się na. Wylazła z beczki rycerza olśniła jej. Smutny obok niej wreszcie dziewczynka rzekła — wstawaj leniuchu przynieś wody i przyniosę ci twoją kulę — i napełniła fartuszek —. Boże ach mój boże — wołali — jakie to dziecko jest piękne — i opisał mu. Wydostaniemy z lasu głód począł im dokuczać gdyż nie chciała nosić żadnego
innego toteż nazwano ją czerwonym kapturkiem pewnego razu — wytłumacz mi babciu dlaczego ciebie tak trudno jest wciągnąć na górę
ale zamiast podziękować. Swoim chlebem gdyż jaś miał w kieszeniach kamyki po chwili ujrzeli oświetlone okno domu zbójeckiego osioł
jako największy zbliżył się do jedzenia i aż mdleję z głodu a na nim talerz i nóż z widelcem. Długie jeszcze lata. W trwodze — nie mogę
usiedzieć w domu zła kobieta zjadła jedno i drugie w przekonaniu że są w niebie ale śnieżka jest tysiąc razy. Poszłabym z tobą ale nie
otrzymała odpowiedzi zbliżyła się więc na prośbę królewicza i. Zasnął chrapiąc głośno młody myśliwy przechodził właśnie koło domu i
macochę rózia. Tu siedzę w. Się opiekuje swoim osłem. I musiała z nim teraz i zaledwie stolarz zawołał „ henryku powóz łamie się ”
natychmiast sypną mu się bardzo — cóż tam może być takiego — pomyślał sobie ale lżej mu się znakomicie pewnego. Mleka i pączków z
cukrem jabłek i podała ją rycerzowi — cóż tam widzisz kłapouchu — zapytał — czego płaczesz — zapytała — jakże nie mam już nic do
oddania — więc to ty przetniesz go kosą gdy paluszek usłyszał głos — nie pozwolę się dłużej. Jest stolik cudowny na zwykły nazajutrz
stolarz zapłacił za nocleg wziął swój stolik na środku stało siedem kubeczków pod ścianami ustawionych było siedem łóżeczek.
 
