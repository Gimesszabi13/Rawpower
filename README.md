Gimes Szabolcs

https://gimesszabi13.github.io/Rawpower/Index.html

A Rawpower oldala az erőemelés sportját ünnepli és ad róla ismertetőt. Emellett egy képzeletbeli nyereményjátékra is lehet jelentkezni, emellett ki tudja számolni az általunk maximális megmozgatható súlyt.

A nyereményjáték.html oldalon található egy nem jqueryvel elkészített galéria, amelyet még a jquery előadás előtt csináltam és nem akartam, 
hogy kárba vesszen a munka. Funkcionálisan ugyanazt tudja, mint a jquery-s változat csak saját kóddal próbáltam megoldani. 
A kód a changePhoto függvényt haszálja, hogy az offsetként megadott paramétrrel navigáljon pozitív vagy negatív irányba. A logika mögötte saját ötlet volt, az offset paraméter használatát StackOverflowról kerestem ki.
A nyilak onClick eseményt kaptak amely hatására meghívódik a changePhoto függvény negatív irányba(bal nyíl) vagy pozitív irányba(jobb nyíl).

A onerepmax_kalkulátor oldalon pedig egy elég rövid és egyszerű javascript kód található, amely a formban megadott adatokat egy változóba tárolja, amelyből a weight változót kiszedi és a Brzycki-formulával
egy ismétléses maximumot ad vissza. A result.innerHTML kiírja a az általunk válaszott gyakorlatban a one rep maxot.

Az egész dokumentumban a font típus a google fonts-ról kiválasztott 'Poppins';'sans-serif' van használatban.

A css-ben a .photo tagben az overflow: hidden; formázás w3schoolsról került be, mert csak így tudtam megoldani hogy az egyes képek ne folyjanak túl a helyükön, ha túl nagyok.
position:relative is w3schoolsról lett bemásolva photo container esztétikus pozicionálására.

.nav-arrow {
    font-size: 32px; 
    color: #e8491d;
    cursor: pointer;                 
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
}

chatgpt segítségét kértem, hogy generáljon a nyílnak css formázást, mert nekem nem sikerült
