
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plusy i minusy jonów</title>
    <link rel="stylesheet" href="124styl.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Plusy i minusy jonów</h1>
            <p>Aniony, kationy i przewodzenie prądu przez roztwory</p>
        </div>
    </header>

    <main>
	
	  <section class="slide">
            <h2>Plusy i minusy... co?</h2>
            <p>Nazywając jony „plusami” i „minusami”, mamy na myśli ich ładunek elektryczny. Jony to nic innego jak atomy mające ładunek. Zachowują się więc jak elektrody, i dzielimy je na kationy i aniony.</p>
            <div class="img">
                <img src="img/3.jpg" alt="Wizualizacja jonów">
            </div>
        </section>
	
	<div class="double-container">
    <div class="box">
        <h3>„Plusy”, czyli kationy</h3>
        <p>Kationy to jony o dodatnim ładunku elektrycznym. Powstają w wyniku oderwania się jednego lub więcej elektronów od atomu.</p>
		<p>Na⁺ (sód)</p>
        <p>Ca²⁺ (wapń)</p>
        <p>H⁺ (proton, często spotykany w kwasach)</p>
    </div>
    <div class="box">
        <h3>„Minusy”, czyli aniony</h3>
        <p>Aniony to jony o ujemnym ładunku elektrycznym. Są to atomy, które przyjęły jeden lub więcej elektronów.</p>
        <p>Cl⁻ (jon chlorkowy)</p>
        <p>OH⁻ (jon wodorotlenowy)</p>
        <p>SO₄²⁻ (jon siarczanowy)</p>
	</div>
</div>

	
        <!-- Slajd 1: Wprowadzenie do dysocjacji elektrolitycznej -->
        <section class="slide">
            <h2>Co to jest dysocjacja elektrolityczna?</h2>
            <p>Dysocjacja elektrolityczna to proces, w którym cząsteczki substancji rozkładają się na jony pod wpływem rozpuszczalnika, zwykle wody. Substancje, które ulegają dysocjacji, nazywane są elektrolitami i mogą przewodzić prąd elektryczny w roztworze.</p>
            <p>Przykład reakcji: NaCl → Na⁺ + Cl⁻. Chlorek sodu (NaCl) rozdziela się na jony sodu (Na⁺) i chlorku (Cl⁻), co pozwala roztworowi przewodzić prąd elektryczny.</p>
            <div class="img">
                <img src="img/4.jpg" alt="Wizualizacja jonów">
            </div>
        </section>

        <!-- Slajd 2: Dysocjacja elektrolityczna - trzy podstawowe rodzaje -->
        <section class="slide">
            <h2>Rodzaje dysocjacji elektrolitycznej</h2>
            <p>Istnieją trzy główne typy dysocjacji elektrolitycznej:</p>
            <ul>
                <li><button class="info-btn" onclick="toggleEquation('salt')">Dysocjacja soli</button></li>
                <li><button class="info-btn" onclick="toggleEquation('acid')">Dysocjacja kwasu</button></li>
                <li><button class="info-btn" onclick="toggleEquation('base')">Dysocjacja zasady</button></li>
            </ul>
            <div id="salt-equation" class="hidden">
                <p><strong>Przykład dysocjacji soli:</strong></p>
                <p>NaCl → Na⁺ + Cl⁻</p>
                <p><strong>Anion:</strong> Cl⁻ (jon chlorkowy)</p>
                <p><strong>Kation:</strong> Na⁺ (jon sodowy)</p>
            </div>
            <div id="acid-equation" class="hidden">
                <p><strong>Przykład dysocjacji kwasu:</strong></p>
                <p>HCl → H⁺ + Cl⁻</p>
                <p><strong>Anion:</strong> Cl⁻ (jon chlorkowy)</p>
                <p><strong>Kation:</strong> H⁺ (jon wodoru)</p>
            </div>
            <div id="base-equation" class="hidden">
                <p><strong>Przykład dysocjacji zasady:</strong></p>
                <p>NaOH → Na⁺ + OH⁻</p>
                <p><strong>Anion:</strong> OH⁻ (jon wodorotlenowy)</p>
                <p><strong>Kation:</strong> Na⁺ (jon sodowy)</p>
            </div>
        </section>

        <!-- Slajd 3: Wyjątki w dysocjacji zasad -->
        <section class="slide">
            <h2>Wyjątki w dysocjacji zasad</h2>
            <p>Niektóre zasady, takie jak KOH (wodorotlenek potasu) i Ca(OH)₂ (wodorotlenek wapnia), ulegają specjalnym reakcjom dysocjacji:</p>
            <ul>
                <li><strong>KOH:</strong> KOH → K⁺ + OH⁻</li>
                <li><strong>Ca(OH)₂:</strong> Ca(OH)₂ → Ca²⁺ + 2OH⁻</li>
            </ul>
            <p>W przypadku tych związków, różna liczba jonów wodorotlenowych (OH⁻) uwalnia się podczas dysocjacji, co wpływa na ich właściwości chemiczne.</p>
        </section>

        <!-- Pozostałe slajdy -->
        <section class="slide">
            <h2>Przewodnictwo prądu przez roztwory elektrolitów</h2>
            <p>Roztwory elektrolitów zawierają jony, które mogą poruszać się pod wpływem pola elektrycznego. Kiedy taki roztwór jest podłączony do źródła prądu, jony zaczynają przemieszczać się w kierunku odpowiednich elektrod, umożliwiając przewodzenie prądu.</p>
            <p>W przeciwieństwie do elektrolitów, substancje nieelektrolityczne (np. cukier, alkohol) nie dysocjują na jony i nie przewodzą prądu.</p>
        <img src="img/5.jpg" alt="">
		</section>
		
		<section class="slide">
            <h2>Właściwości elektrolitów i nieelektrolitów</h2>
            <table class="properties-table">
                <thead>
                    <tr>
                        <th>Rodzaj</th>
                        <th>Przewodnictwo elektryczne</th>
                        <th>Przykłady</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Elektrolity</td>
                        <td>Przewodzą prąd elektryczny</td>
                        <td>Kwasy (HCl), zasady (NaOH), sole (NaCl)</td>
                    </tr>
                    <tr>
                        <td>Nieelektrolity</td>
                        <td>Nie przewodzą prądu elektrycznego</td>
                        <td>Cukier, alkohol, woda destylowana</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Slajd 4: Eksperymenty przewodzenia prądu -->
        <section class="slide">
            <h2>Eksperymenty z przewodnictwem prądu</h2>
            <p>Eksperymenty z przewodnictwem prądu przez roztwory pozwalają na badanie, jak różne substancje przewodzą prąd elektryczny w roztworach wodnych.</p>
            <ul>
                <li><strong>Roztwór NaCl:</strong> NaCl w wodzie rozdziela się na jony Na⁺ i Cl⁻, co pozwala na przewodzenie prądu.</li>
                <li><strong>Roztwór cukru:</strong> Cząsteczki cukru nie dysocjują na jony, dlatego roztwór nie przewodzi prądu.</li>
            </ul>
        </section>
		
		 <section class="slide">
            <h2>Nie uwierzę, dopóki tego nie zobaczę!</h2>
            <p>Możesz to sprawdzić sam! Czy wiesz, że można stworzyć wlasną baterię z owocu? </p>
            <p>W tym ekperymencie wykorzystujemy właściwości jonów. Elektrody, takie jak cynk (działający jako elektroda ujemna) i miedź (elektroda dodatnia), zanurzamy w kwaśnym środowisku, takim jak sok z cytryny, jabłka czy ziemniaka.</p> 
			<p>Kwas lub inne elektrolity w owocu pozwalają na przemieszczanie się jonów pomiędzy elektrodami, co generuje prąd.</p>
            <li>Cynk działa jako anion (utlenianie- utrata elektronów).</li>
            <li>Miedź działa jako kation (redukcja - przyjmowanie elektronów).</li>
            <p>Wynik? Niewielkie napięcie, które można zmierzyć dołączonym woltomierzem, a nawet zasilić małą diodę LED. </p>
			<img src="img/2.jpg" alt="Eksperyment">
        </section>
		
		<section class="slide">
            <h2>Podsumowanie</h2>
            <p>Jony, czyli naładowane atomy lub grupy atomów, odgrywają kluczową rolę w chemii i fizyce. </p>
            <p>Kationy (dodatnie) i aniony (ujemne) powstają przez utratę lub przyjęcie elektronów. </p>
			<p>Dysocjacja elektrolityczna pozwala substancjom, takim jak kwasy, zasady i sole, rozpadać się na jony w wodzie, co umożliwia przewodzenie prądu.</p>
			<p> Jony są nie tylko nośnikami ładunku, ale także kluczowym elementem reakcji chemicznych, które napędzają życie codzienne i technologie, np. tworzenie prądu w eksperymentach z owocami.</p>
        </section>
		
        <!-- Примерный код для всех слайдов выше... -->

        <!-- Slajd с заданиями -->
        <section class="slide">
            <h2>Czy napewno wszystko zrozumiał?</h2>
            <p>Spróbuj rozwiązać poniższe zadania:</p>
            <ol>
                <li>Podaj, czy roztwór NaOH będzie przewodził prąd i dlaczego?</li>
                <li>Co się stanie, gdy rozpuścimy w wodzie alkohol etylowy? Czy będzie przewodził prąd?</li>
            </ol>

            <button class="info-btn" id="answer1Btn">Odpowiedź do zadania 1</button>
            <div class="answer hidden" id="answer1">
                <p>Roztwór NaOH przewodzi prąd, ponieważ NaOH dysocjuje na jony Na⁺ i OH⁻ w wodzie, umożliwiając przepływ prądu.</p>
            </div>

            <button class="info-btn" id="answer2Btn">Odpowiedź do zadania 2</button>
            <div class="answer hidden" id="answer2">
                <p>Alkohol etylowy nie przewodzi prądu, ponieważ nie dysocjuje na jony w wodzie, a więc nie ma swobodnych nośników ładunków elektrycznych.</p>
            </div>
        </section>

        <!-- Slajd с кнопкой źródła -->
        <section class="slide">
		                <h2>Dziękujemy za uwagę!</h2>
						 <img src="img/1.gif" alt="">
            <button class="source-btn" id="sourceBtn">Źródła</button>
            <div class="source-list hidden" id="sourceList">
				<ul>
                    <li><a href="https://zsp10.pless.pl/2024/02/plusy-i-minusy-jonow/" target="_blank">Źródło 1</a></li>
                    <li><a href="https://www.youtube.com/@PistacjaChemia" target="_blank">Źródło 2</a></li>
					<li><a href="https://chemmaster.pl/dysocjacja-jonowa-i-elektrolityczna-roznice-zastosowanie-typy-dysocjacji/?srsltid=AfmBOoq48aRNfosDPil7rsP-FWbEXbrJ3so_Wsv-YApwqGFKCaYnAkGK" target="_blank">Źródło 3</a></li>
					<li><a href="https://zpe.gov.pl/a/przeczytaj/DOvDdfyjM" target="_blank">Źródło 4</a></li>
                    <li><a href="https://chatgpt.com" target="_blank">Źródło 5</a></li>
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024. Adyrova, Oliinyk 3TI</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

