---
tags:
    - Introduktion
    - Regneregler
    - Potenser
    - Rødder
    - Eksponenter
    - Logaritmer
    - Funktioner
    - Definitionsmængde
    - Værdimængde
    - Inverse funktioner
    - Sammensatte funktioner
---

<h1 align="center">Grundlæggende aritmetik og funktioner</h1>

I denne indledende session lægger vi fundamentet for den matematik, der anvendes i softwareudvikling. Vi starter med en gennemgang af kursusstruktur, læringsmål og forventninger. Herefter fokuserer vi på centrale regneregler og de grundlæggende egenskaber ved funktioner, som udgør grundlaget for de mere avancerede emner, der følger senere i kurset.

Sessionen omfatter forståelse og anvendelse af potensregler, rødder, eksponenter og logaritmer. Vi undersøger desuden definitionen af funktioner samt deres definitions- og værdimængder. Afslutningsvis introduceres begreberne inverse og sammensatte funktioner, som er væsentlige for det videre arbejde i kurset. Der er særlig fokus på logaritmer og deres anvendelse i softwareudvikling, da de spiller en central rolle i mange algoritmer og databehandlingsmetoder.

---

## Forberedelse

At forberede sig betyder ikke nødvendigvis at læse alt materiale fra start til slut. Det handler i stedet om at identificere og fokusere på det indhold, der er mest relevant for dig og din forberedelse til undervisningen. Jeg forventer dog, at du har gennemgået og forstået materialet fra videoerne. Du kan teste din viden i quizzen, hvor en forståelse anses som tilstrækkelig, hvis du kan svare korrekt på mindst 7 ud af 10 spørgsmål.

### Læsemateriale:

Brooks: [Kapitel 1](https://drive.google.com/file/d/1P9eidJb5qtlZgvHCtqu4uuPa5FFU0Zpn/view?usp=sharing).

### Ressourcer

[Noter fra videomateriale](https://drive.google.com/file/d/1IXTVyUP_TeX4co_uwSSlf6AHYYrln1fL/view?usp=drive_link)

[Andre materialer](https://viaucdk-my.sharepoint.com/:f:/g/personal/rib_viauc_dk/EtdW6vDKB6FHsPZdtO6XUhMB5n3uwC00IoyfXj5g1O6JlA?e=vAY78F)

### Videomateriale


#### 2.1. Introduktion til vektorer

<iframe width="560" height="315" src="https://www.youtube.com/embed/b7eFkSJsGkk?si=qxUa5Rxby1tC4d_j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### 2.2. Vektorer i koordinatsystemer

<iframe width="560" height="315" src="https://www.youtube.com/embed/jfLfH_7VGv8?si=QKjCyMkS23pZjUqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### 2.3. Regneregler

<iframe width="560" height="315" src="https://www.youtube.com/embed/inTTWR7KSVw?si=9-H0i2oSAhKyJ1x3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### 2.4. Længde, afstand og enhedsvektorer

<iframe width="560" height="315" src="https://www.youtube.com/embed/ksSWQhmF2uM?si=Ucus8SngnZglnLwT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### 2.5. Prikprodukt

<iframe width="560" height="315" src="https://www.youtube.com/embed/PiYqcXu4Ui8?si=Vz1lILPK3C9zajz-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### 2.6. Krydsprodukt

<iframe width="560" height="315" src="https://www.youtube.com/embed/N3YmZ247D7w?si=IuBmX6j12b6dJL9W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Quiz

<?quiz?>
question: Hvilken af følgende regneregler for potenser er korrekt?
answer: $a^m \cdot a^n = a^{m-n}$
answer-correct: $a^m \cdot a^n = a^{m+n}$
answer: $(a^m)^n = a^{m-n}$
answer: $a^m + a^n = a^{m+n}$
answer: $a^m / a^n = a^{m+n}$
content:
<p><strong>Forklaring:</strong> Ved multiplikation af potenser med samme grundtal lægges eksponenterne sammen: $a^m \cdot a^n = a^{m+n}$.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende funktioner er IKKE en funktion i matematisk forstand?
answer: $f(x) = x^2$
answer: $g(x) = \sqrt{x}$
answer: $h(x) = \frac{1}{x}$
answer-correct: $k(x) = \pm \sqrt{x}$
answer: $m(x) = 2x + 1$
content:
<p><strong>Forklaring:</strong> $k(x) = \pm \sqrt{x}$ kan give to værdier for samme $x$ og opfylder derfor ikke definitionen på en funktion.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende regneregler for logaritmer er korrekt?
answer: $\log(a+b) = \log(a) + \log(b)$
answer: $\log(a^b) = b + \log(a)$
answer-correct: $\log(ab) = \log(a) + \log(b)$
answer: $\log(a/b) = \log(a) \cdot \log(b)$
answer: $\log(a^b) = \log(a)/b$
content:
<p><strong>Forklaring:</strong> For produktet gælder: $\log(ab) = \log(a) + \log(b)$.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende ligninger er ækvivalent med $x = \log_3(y)$?
answer-correct: $y = 3^x$
answer: $y = \log_3(x)$
answer: $y = x^3$
answer: $x = y^3$
answer: $y = \log(x) + 3$
content:
<p><strong>Forklaring:</strong> Hvis $x = \log_3(y)$, så $y = 3^x$. Logaritme og eksponentialfunktioner er hinandens inverse.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilket udsagn om definitionsmængden for $f(x) = \sqrt{x-4}$ er korrekt?
answer: $f$ er defineret for alle $x$
answer: $f$ er defineret for $x > 0$
answer-correct: $f$ er defineret for $x \geq 4$
answer: $f$ er defineret for $x > 4$
answer: $f$ er defineret for $x < 4$
content:
<p><strong>Forklaring:</strong> Kvadratroden kræver, at $x-4 \geq 0$, altså $x \geq 4$.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende påstande om funktionen $f(x) = \ln(x)$ er korrekt?
answer: $f(x)$ er defineret for alle $x \in \mathbb{R}$
answer-correct: $f(x)$ er kun defineret for $x > 0$
answer: $f(x)$ er kun defineret for $x \geq 0$
answer: $f(x)$ er kun defineret for $x < 0$
answer: $f(x)$ er defineret for alle hele tal
content:
<p><strong>Forklaring:</strong> Den naturlige logaritme $\ln(x)$ er kun defineret for positive tal ($x > 0$).</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende beskriver bedst den inverse funktion til $f(x) = 2x-1$?
answer: $f^{-1}(x) = 2x+1$
answer: $f^{-1}(x) = x/2 - 1$
answer-correct: $f^{-1}(x) = (x+1)/2$
answer: $f^{-1}(x) = x/2+1$
answer: $f^{-1}(x) = 2(x-1)$
content:
<p><strong>Forklaring:</strong> Man løser $y = 2x-1$ for $x$: $x = (y+1)/2$, så $f^{-1}(x) = (x+1)/2$.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilket af følgende udsagn om sammensatte funktioner er korrekt?
answer-correct: $f(g(x))$ betyder, at man først anvender $g$ og derefter $f$
answer: $f(g(x))$ betyder, at man først anvender $f$ og derefter $g$
answer: $f(g(x)) = f(x) \cdot g(x)$
answer: $f(g(x)) = g(f(x))$
answer: $f(g(x))$ findes kun hvis $f$ og $g$ begge er lineære
content:
<p><strong>Forklaring:</strong> Ved sammensætning $f(g(x))$ regner man $g(x)$ først og bruger resultatet som input til $f$.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilket af følgende udsagn beskriver eksponentialfunktionens værdimængde $f(x) = 2^x$ bedst?
answer: $[0,\infty)$
answer-correct: $(0,\infty)$
answer: $(-\infty,\infty)$
answer: $[1,\infty)$
answer: $[0,1]$
content:
<p><strong>Forklaring:</strong> $2^x$ er altid positiv og kan antage alle værdier større end nul, men aldrig nul.</p>
<?/quiz?>

---

<?quiz?>
question: Hvilken af følgende regneregler gælder for rødder?
answer-correct: $\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$
answer: $\sqrt{a + b} = \sqrt{a} + \sqrt{b}$
answer: $\sqrt{a^b} = a^{b/2}$
answer: $\sqrt{a} \cdot \sqrt{b} = \sqrt{a + b}$
answer: $\sqrt{a}/\sqrt{b} = \sqrt{a-b}$
content:
<p><strong>Forklaring:</strong> Produktreglen for rødder er $\sqrt{a \cdot b} = \sqrt{a} \cdot \sqrt{b}$. Summen af rødder er ikke lig med roden af summen.</p>
<?/quiz?>



--------------------------

## Undervisning 1: Gennemgang af eksempler


I denne del gennemgår jeg eksempler, der understøtter og eksemplificerer de emner, vi har dækket i videoerne. Det er vigtigt at forstå, hvordan disse koncepter anvendes i praksis, og hvordan de kan hjælpe dig med at løse problemer inden for softwareudvikling. Denne session foregår synkront på Teams og I kan under undervisningen stille spørgsmål og deltage aktivt i diskussionen. Det er en god mulighed for at få afklaret eventuelle tvivlsspørgsmål og få en dybere forståelse af emnerne. Videoen lægges op efterfølgende, så du kan se den igen, hvis du ønsker det. Jeg gennemgår følgende eksempler:

#### Eksempel 1: Løs ligninger vha. regneregler for eksponenter og logaritmer

Løs følgende ligninger:

1. $\frac{1}{x+1}=\frac{1}{2 x}$
2. $\frac{y+5}{y-7}-2=-\frac{y+7}{y-5}$
3. $\ln \sqrt{x+2}=1$
4. $4 \log _{10}(x-6)=11$
5. $8^{-x}=2^{x-8}$
6. $\left(\frac{1}{4}\right)^{x-1}=4^{2-3 x}$

??? answer "&nbsp;"

    1. $x=1$
    2. $y=6$
    3. $x=e^2-2$
    4. $x=10^{\frac{11}{4}}+6$
    5. $x=2$
    6. $x=\frac{1}{2}$


#### Eksempel 2: Isoleringsmetoden

Den fejl, der er forbundet med statistisk usikkerhed, er givet ved

$$
E=Z_{1-\alpha} \frac{\sigma}{\sqrt{n}}
$$

hvor $Z_{1-\alpha}$ er z-scoren forbundet med den standard normale fordeling, $\sigma$ er standardafvigelsen, og $n$ er stikprøvestørrelsen.

1. Omarranger ovenstående formel, så stikprøvestørrelsen, $n$ bliver subjektet:

    ??? answer "&nbsp;"

        $n = \left(\frac{Z_{1-\alpha} \cdot \sigma}{E}\right)^2$

2. Antag en z-score på 1,96 og en standardafvigelse på 2. Hvilken stikprøvestørrelse er nødvendig for at have en fejl på højst 0,5?

    ??? answer "&nbsp;"
        
        $$ 
        n = \left(\frac{1.96 \cdot 2}{0.5}\right)^2 = 61,47
        $$

        Stikprøvestørrelsen skal derfor være mindst 62 (afrundet opad).

#### Eksempel 3: Definitionsmængde og værdimængde
Bestem definitionsmængden og værdimængden for hver af de reelle funktioner nedenfor. Det er en god idé at plotte funktionerne ved hjælp af software (f.eks. Geogebra, WolframAlpha osv.):

1. $\\ f(x)=\frac{1}{x-5}$
2. $g(x)=\sqrt{2 x-4}$

    ??? answer "&nbsp;"

        a.  Definitionsmængde: $\mathbb{R} \backslash\{5\}$; Værdimængde: $\mathbb{R} \backslash\{0\}$

        b.  Definitionsmængde: $\mathbb{R}_{\geq 2}$; Værdimængde: $\mathbb{R}_{\geq 0}$

#### Eksempel 4: Sammensatte funktioner
Find hver af de følgende sammensatte funktioner:
1. $\\ g \circ f$ når $f(x)=3 x+1$ og $g(x)=x^2$.

    ??? answer "&nbsp;"

        $(g \circ f)(x)=9 x^2+1+6 x$

2. $f \circ g$ når $f(x)=x^2+1$ og $g(x)=\frac{1}{x}$.
    ??? answer "&nbsp;"

        $(f \circ g)(x)=\frac{1}{x^2}+1$

3. $\\ g \circ f$ når $f$ og $g$ er defineret som i øvelse (b).
    ??? answer "&nbsp;"

        $(g \circ f)(x)=\frac{1}{x^2+1}$

#### Eksempel 5: Inverse funktioner
Find den inverse funktion:
1. $\\ f(x)=\frac{6}{5-x}$

    ??? answer "&nbsp;"

        $f^{-1}(x)=5-\frac{6}{x}$

2. $\\ f(x)=-\ln (1-2 x)+1$
    ??? answer "&nbsp;"

        $f^{-1}(x)=\left(1-e^{1-x}\right) / 2$

---

## Øvelser
I skal lave øvelserne inden timerne torsdag. I kan med fordel lave dem i grupper og diskutere dem indbyrdes. Det er vigtigt, at I forstår opgaverne og kan forklare dem til hinanden. På torsdag diskuterer vi opgaverne, og I skal være klar til at præsentere dem for klassen.

#### Øvelse 1:

Løs følgende ligninger:

1. $\\ 2-\frac{4 x+3}{x+x^2}=\frac{2 x}{x+1}-\frac{5}{x}$
2. $\\ -2+2 \ln 3 x=17$
3. $\\ \ln (x+1)^2=2$
4. $\\ \ln \left(x^2+1\right)=8$
5. $\\ 5^{3 x+2}=25^{x-1}$
6. $\\ 2^{x+1}=4^{x-2}$

??? answer "&nbsp;"

   1. $x = -\frac{2}{3}$
   2. $x = \frac{e^{\frac{19}{2}}}{3}$
   3. $x = -1 \pm e$
   4. $x = \pm \sqrt{e^8 - 1}$
   5. $x = -4$
   6. $x = 5$

#### Øvelse 2:

Ifølge Einsteins relativitetsteori gives massen af en partikel ved:

$$
m=\frac{m_0}{\sqrt{1-\left(\frac{v}{c}\right)^2}}
$$

hvor
$m_0$ er massen af partiklen i hvile,
$v$ er partiklens hastighed, og
$c$ er lysets hastighed i vakuum.

a. Gør $v$ til subjektet i formlen givet $v>0$ (1)
{ .annotate }

1. $v=c \cdot \sqrt{1-\left(\frac{m_0}{m}\right)^2}$

b. Find den hastighed, der er nødvendig for at øge massen af en partikel til tre gange dens hvilemasse. Giv værdien for $v$ som en brøkdel af $c$ (eller som en decimal).(1)
{ .annotate }

1. $v=0.943 c$

#### Øvelse 3
Bestem definitionsmængden og værdimængden for hver af de reelle funktioner nedenfor. Det er en god idé at plotte funktionerne ved hjælp af software (f.eks. Geogebra, WolframAlpha osv.):

a. $\\ f(x)=\frac{1}{x-7}$

??? answer "&nbsp;"

    Definitionsmængde: $\mathbb{R} \backslash\{7\}$;

    Værdimængde: $\mathbb{R} \backslash\{0\}$

b. $\\ f(x)=\sqrt{x+3}$

??? answer "&nbsp;"

    Definitionsmængde: $\mathbb{R}_ {\geq-3}$;

    Værdimængde: $\mathbb{R}_ {\geq 0}$

#### Øvelse 4
Find hver af de følgende sammensatte funktioner:

a. $\\ g \circ f$ når $f(x)=3 x+1$ og $g(x)=x^2$.

??? answer "&nbsp;"

    $(g \circ f)(x)=9 x^2+1+6 x$

b. $f \circ g$ når $f(x)=x^2+1$ og $g(x)=\frac{1}{x}$.

??? answer "&nbsp;"

    $(f \circ g)(x)=\frac{1}{x^2}+1$

c. $\\ g \circ f$ når $f$ og $g$ er defineret som i øvelse (b).

??? answer "&nbsp;"

    $(g \circ f)(x)=\frac{1}{x^2+1}$

#### Øvelse 5
Find den inverse funktion:

a. $\\ f(x)=\frac{6}{5-x}$

??? answer "&nbsp;"

    $f^{-1}(x)=5-\frac{6}{x}$

b. $\\ f(x)=-\ln (1-2 x)+1$

??? answer "&nbsp;"

    $f^{-1}(x)=\left(1-e^{1-x}\right) / 2$

c. $\\ f(x)=2 \cdot 10^{3 x}-1$

??? answer "&nbsp;"

    $f^{-1}(x)=\frac{\log \left(\frac{x+1}{2}\right)}{3}$

#### Øvelse 6

En bakteriekultur starter med 1000 bakterier ved tiden $t=0$, og antallet fordobles hver 40. minut.

a. Find et funktionelt udtryk for antallet af bakterier ved tiden $t$ (målt i minutter).

??? answer "&nbsp;"
    $f(t)=1000 \cdot 2^{t / 40}$

b. Find antallet af bakterier efter en time.

??? answer "&nbsp;"

    $f(60) \approx 2828$

c. Efter hvor mange minutter vil der være 50000 bakterier?

??? answer "&nbsp;"

    ca. 225.75 minutter