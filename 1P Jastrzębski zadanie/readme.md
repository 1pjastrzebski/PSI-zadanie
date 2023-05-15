# Zadanie na zaliczenie

## HTML

**Jeśli zdecydujesz się na użycie klas lub identyfikatorów (nieśmiało przypomnę, że odwoływanie się do identyfikatorów w CSS to nie jest dobra praktyka) nadawaj im nazwy znaczące, podobnie jak nazwy pól formularza. Nazwy takie jak "elem1", "a", "pierwszy" nie wpłyną korzystnie na uzyskaną przez Ciebie ocenę w odróżnieniu od "article_header", "article_content" czy "submitBtn" lub np. "btn_submit"**

1. Utwórz plik index.html w nim kontener, wewnątrz którego wykorzystując znaczniki sekcji, utwórz 5 paneli
1. Zawartość pierwszego panelu - w nagłówku pierwszego stopnia tekst _Zaliczenie przedmiotu PSI_
1. Zawartość drugiego panelu:
   - 3 artykuły z tytułami w nagłówkach 2 stopnia z tekstem _Tytuł artykułu 1_ i _Tytuł artykułu 2_ _Tytuł artykułu 3_
   - obrazem (_img1.jpg_ i _img2.jpg_ _img3.jpg_) z tekstem alternatywnym _przykładowe zdjęcie_
   - akapitem z tekstem _Lorem ipsum_ (30 wyrazów)
   - paragrafem w stopce z tekstem _Autor XXI w._
1. Zawartość trzeciego panelu:
   -sekcję z 2 artykułami zawierającymi tytuł w nagłówku 3 stopnia i tekst "Lorem ipsum" w paragrafie

- sekcję zawierającą formularz z polami (wszystkie pola powinny mieć powiązane z nimi etykiety i atrybut name, pierwsze pole powinno mieć "podpowiedź" _wprowadź imię_):
  1.  pole imię (tekstowe, ograniczone do 15 znaków, odpowiednia "podpowiedź" (wpisz imię))
  1.  pole wiek (liczbowe ograniczone do 3 znaków z wartością minimalną 5 i maksymalną 100, wartość domyślna 18)
  1.  zgrupowane za pomocą odpowiedniego znacznika pola pojedyńczego wyboru (jak na zrzucie), domyślnie wybrane drugie pole
  1.  pole typu zakres od 1 do 6 z wartością domyślną równą 5
  1.  odpowiedniego typu pola formularza do czyszczenia i wysyłania formularza

1. Zawartość czwartego panelu:
   - 3 artykuły z tytułem (np. "Wpis 1") w nagłówku 3 stopnia obrazami (img7.jpg, img8.jpg, img9.jpg) i tekstem alternatywnym "zdjęcie", paragrafem z tekstem "Lorem ipsum"
1. Zawartość piątego panelu:
   - paragraf ze znakiem (encją) praw autorskich Twoim imieniem, nazwiskiem i klasą

## CSS

- **jeśli nie jest podano innej wartości w treści zadania** - podstawową wielkością wewnętrznych i zewnętrznych marginesów elementów, odległości między panelami w kontenerze jest wartość równa wielkości wielkości czcionki podstawowej dokumentu (root),

- **_układ elementów na stronie zgodny z załączonymi zrzutami ekranu, należy użyć o właściwości modułów CSS (flexbox i/lub grid) odpowiednich do rozmieszczenia paneli i elementów wewnątrz nich_**

- kolor tła strony: czarny (zapisany w trybie szesnastkowym)
- czcionka Verdana lub dowolna czcionka bezszeryfowa w kolorze #eee
  maksymalna szerokość kontenera 100px, ramka w postaci ciągłej linii o szerokości 1 piksela w kolorze #ddd, wewnętrzny margines, odstępy między panelami równe wielkości wielkości czcionki podstawowej dokumentu
- wszystkie panele w kontenerze mają ustawiony podstawowy margines wewnętrzny
- pierwszy panel: czcionka w kolorze czerwonym, wyśrodkowana, wewnętrzy margines, litery zamienione na wielkie, szerokość 100%
- drugi panel: szerokość 60%, kolor tła o wartościach R=127, G=127, B=127, przeźroczystość 0.3, formularz wyśrodkowany w obydwu osiach; wielkość czcionki paragrafu 1,3 wielkości czcionki podstawowej dokumentu, stopka artykułu wyrównana do prawej strony,
  w tytule odstępy międzi znakami równe 8px, czcionka zapisana kapitalikami (wszystkie litery zapisane kapitalikami z zachowaniem wielkich liter), odległość między wierszami w paragrafie 1.5 wielkości czcionki podstawowej rodzica, tekst w paragrafie wyjustowany, dodany margines dolny i górny artkułu oraz margines wenętrzny,
- trzeci panel:szerkość - taka aby wypełnił pozostałe dostępne miejsce w kontenerze, dodany wewnętrzny margines, kolor tła: R=150, G=150, B=122557, przeźroczystość 0.3, sekcje wewnątrz rozmieszczone jak na zrzucie ekranu
- formularz: dodany margines górny i dolny do wszystkich elementów formularza, elementy formularza są wyśrodkowane, podstawowy margines wewnętrzny dla elementu grupującego pola jednokrontnego wyboru elementy wewnątrz niego wyśrodkowane, szerokość "przycisków" formularza 5 wielkości czcionki podstawowej dokumentu
- czwarty panel: ustawiony wewnęytrzny margines, odległość między wierszami w paragrafie 1.5 wielkości czcionki podstawowej rodzica, artykuły wewnątrz rozmieszczone jak na zrzucie ekranu
- piąty panel:margines wewnętrzny, kolor tła o wartościach R=255, G=255, B=0, przeźroczystość 0.3, czcionka w kolorze żółtym (szesnastkowo!), pogrubiona, wyrównana do środka,

**_Tekst lorem ipsum_**

- 50 wyrazów

  _Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates quos impedit tempore neque laboriosam quasi dolorum dignissimos iusto nam non, nesciunt iste officiis eveniet obcaecati. Ullam, illo nam! Quidem quia eius assumenda sapiente. Vero repudiandae neque fuga eum quas voluptate sit vitae ipsum distinctio consequatur deleniti libero, perspiciatis, inventore rerum._

- 30 wyrazów

  _Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolor molestias dolore inventore architecto velit ipsam exercitationem veniam sed? Dolorem, id? Animi a necessitatibus officia est, iusto veniam id ducimus consectetur._
