<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perché usare HTML?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }
        header {
            background-color: #12a417a4;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin-bottom: 20px;
        }
        nav a {
            margin: 0 10px;
            color: #333;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            margin-bottom: 20px;
        }
        h1, h2 {
            color: #333;
        }
        .category {
            background-color: #f9f9f9;
            padding: 15px;
            margin: 10px 0;
            border-left: 5px solid #4CAF50;
        }
        .category h3 {
            margin-top: 0;
        }
        .crimson {
            color: #DC143C; /* Crimson */
        }
        input[type="checkbox"] {
            display: none;
        }
        input[type="checkbox"] + label {
            cursor: pointer;
            display: block;
            font-weight: bold;
            margin-bottom: 10px;
        }
        input[type="checkbox"] + label + .category {
            display: none;
        }
        input[type="checkbox"]:checked + label + .category {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <h1>Perché usare HTML?</h1>
    </header>

    <nav>
        <a href="#come-funziona-html">Come funziona HTML?</a>
        <a href="#cosa-html">Cosa è HTML?</a>
        <a href="#come-nato-html">Come è nato HTML?</a>
        <a href="#realizzare-html">Cosa si può realizzare con HTML?</a>
        <a href="#app-html">Applicazioni di HTML</a>
    </nav>

    <section id="come-funziona-html">
        <h2>Come funziona HTML?</h2>
        <p>HTML, acronimo di HyperText Markup Language, è il linguaggio standard utilizzato per creare e strutturare contenuti sul web. Attraverso l'uso di tag e attributi, HTML permette di definire la struttura e il contenuto di una pagina web.</p>
    </section>
    
    <section id="come-funzionano-tag-html">
        <h2>Come funzionano i tag HTML?</h2>
        <p>I tag HTML sono elementi fondamentali utilizzati per definire la struttura e il significato del contenuto di una pagina web. Ogni tag ha un'inizio e una fine, e può contenere altri elementi al suo interno. Ecco alcuni esempi di tag HTML comuni:</p>
        <ul>
            <li><code>&lt;!DOCTYPE&gt;</code>: Definisce il tipo di documento e la versione di HTML utilizzata.</li>
            <li><code>&lt;html&gt;</code>: Rappresenta l'intero documento HTML.</li>
            <li><code>&lt;head&gt;</code>: Contiene metadati e collegamenti a fogli di stile e script.</li>
            <li><code>&lt;title&gt;</code>: Definisce il titolo della pagina.</li>
            <li><code>&lt;body&gt;</code>: Contiene il contenuto visibile della pagina.</li>
            <li><code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code>, ..., <code>&lt;h6&gt;</code>: Definiscono i titoli di diversi livelli.</li>
            <li><code>&lt;p&gt;</code>: Definisce un paragrafo di testo.</li>
            <li><code>&lt;a&gt;</code>: Crea un collegamento ipertestuale.</li>
            <li><code>&lt;img&gt;</code>: Inserisce un'immagine.</li>
            <li><code>&lt;ul&gt;</code>: Crea un elenco non ordinato.</li>
            <li><code>&lt;ol&gt;</code>: Crea un elenco ordinato.</li>
            <li><code>&lt;li&gt;</code>: Definisce un elemento di un elenco.</li>
            <li><code>&lt;div&gt;</code>: Crea una sezione logica o un contenitore.</li>
            <li><code>&lt;span&gt;</code>: Definisce una parte del testo con un comportamento speciale.</li>
            <li><code>&lt;input&gt;</code>: Crea un campo di input.</li>
            <li><code>&lt;form&gt;</code>: Crea un modulo per l'invio di dati.</li>
            <li><code>&lt;button&gt;</code>: Crea un pulsante.</li>
            <li><code>&lt;table&gt;</code>: Crea una tabella.</li>
            <li><code>&lt;tr&gt;</code>: Definisce una riga in una tabella.</li>
            <li><code>&lt;td&gt;</code>: Definisce una cella in una tabella.</li>
        </ul>
    </section> 
  
    <section id="cosa-html">
        <h2>Cosa è HTML?</h2>
        <p>HTML, acronimo di HyperText Markup Language, è il linguaggio standard utilizzato per creare e strutturare contenuti sul web. Attraverso l'uso di tag e attributi, HTML permette di definire la struttura e il contenuto di una pagina web.</p>
    </section>

    <section id="come-nato-html">
        <h2>Come è nato HTML?</h2>
        <p>HTML è stato sviluppato da Tim Berners-Lee, un informatico britannico, nel 1991. L'obiettivo era creare un modo per condividere documenti e informazioni attraverso Internet in modo semplice e accessibile. La prima versione di HTML includeva una serie di tag di base per la formattazione del testo, la creazione di collegamenti ipertestuali e l'inclusione di immagini.</p>
    </section>

    <section id="realizzare-html">
        <h2>Cosa si può realizzare con HTML?</h2>
        <p>Con HTML è possibile creare una vasta gamma di contenuti web, tra cui:</p>
        <ul>
            <li>Siti web statici e dinamici</li>
            <li>Blogs e articoli online</li>
            <li>Portfoli digitali</li>
            <li>Pagine di prodotto per ecommerce</li>
            <li>Form di contatto e moduli interattivi</li>
            <li>Presentazioni online</li>
            <li>Documenti di supporto e manuali</li>
        </ul>
    </section>
    <section id="app-html">
        <h2>Applicazioni di HTML</h2>

        <input type="checkbox" id="editor-toggle">
        <label for="editor-toggle">Editori online e editori di testo per modificare HTML</label>
        <div class="category">
            <h3>Editori online e editori di testo per modificare HTML</h3>
            <p>Ecco alcuni strumenti che ti permettono di modificare il codice HTML direttamente nel browser:</p>
            <ul>
                <li><strong>CodePen:</strong> Una piattaforma molto popolare per testare e mostrare frammenti di codice HTML, CSS e JavaScript. È ottima per condividere il lavoro e vedere i risultati in tempo reale. <a href="https://codepen.io/">Sito web: CodePen</a></li>
                <li><strong>JSFiddle:</strong> Un editor online che permette di modificare e testare codice HTML, CSS e JavaScript. Puoi vedere i risultati delle tue modifiche in tempo reale. <a href="https://jsfiddle.net/">Sito web: JSFiddle</a></li>
                <li><strong>JSBin:</strong> Un altro strumento simile a JSFiddle, che permette di modificare e testare codice HTML, CSS e JavaScript. <a href="https://jsbin.com/">Sito web: JSBin</a></li>
                <li><strong>Repl.it:</strong> Una piattaforma di sviluppo collaborativa che supporta molte lingue di programmazione, tra cui HTML, CSS e JavaScript. Offre anche funzionalità di collaborazione in tempo reale. <a href="https://replit.com/">Sito web: Replit</a></li>
                <li><strong>Playcode:</strong> Un editor online che offre un'interfaccia pulita e funzionalità avanzate per scrivere e testare codice HTML, CSS e JavaScript. <a href="https://playcode.io/">Sito web: Playcode</a></li>
                <li><strong>Thimble by Mozilla:</strong> Un editor di codice HTML, CSS e JavaScript online facile da usare, che è ottimo per i principianti. <a href="https://thimble.mozilla.org/">Sito web: Mozilla Thimble</a> (Nota: Thimble è stato chiuso nel 2018, ma alcune delle sue funzionalità sono state integrate in altre piattaforme Mozilla).</li>
            </ul>
        </div>

        <div class="category">
            <h3>Editori di testo per modificare HTML</h3>
            <p>Ecco alcuni editor di testo per modificare HTML:</p>
            <ul>
                <li><strong>Visual Studio Code:</strong> Un editor di codice molto potente e versatile, con molte estensioni che possono aiutarti nello sviluppo web. <a href="https://code.visualstudio.com/">Sito web: Visual Studio Code</a></li>
                <li><strong>Sublime Text:</strong> Un editor di testo semplice e leggero, ma molto potente, con molte funzionalità utili per la programmazione. <a href="https://www.sublimetext.com/">Sito web: Sublime Text</a></li>
                <li><strong>Atom:</strong> Un editor di testo open source sviluppato da GitHub, altamente personalizzabile. <a href="https://atom.io/">Sito web: Atom</a></li>
                <li><strong>Brackets:</strong> Un editor di testo open source specificamente progettato per il web design e lo sviluppo front-end. <a href="http://brackets.io/">Sito web: Brackets</a></li>
                <li><strong>Notepad++:</strong> Un editor di testo gratuito per Windows che supporta diverse lingue di programmazione. <a href="https://notepad-plus-plus.org/">Sito web: Notepad++</a></li>
                <li><strong>Dreamweaver:</strong> Un editor HTML professionale sviluppato da Adobe, ideale per chi preferisce un ambiente WYSIWYG (What You See Is What You Get). <a href="https://www.adobe.com/it/products/dreamweaver.html">Sito web: Dreamweaver</a></li>
            </ul>
        </div>

        <p class="crimson">Questi strumenti ti permetteranno di modificare il codice HTML e di vedere i cambiamenti in tempo reale (alcuni con l'ausilio di plugin o estensioni). Scegli quello che preferisci in base alle tue esigenze e al tuo livello di esperienza.</p>
    </section>
</body>
</html>
