Bardzo szkicowy przegląd środowisk do pythona, z których będziemy korzystać na warsztatach:

| używaj | gdy |
|-----|------|
| python console | gdy żadne inne środowisko nie jest dostępne |
| ipython console | przede wszystkim do prostych, szybkich spraw - ipython uruchamia się szybko a jest wygodniejszy od domyślego terminala pythona |
| jupyter qt consle | też uruchamia się bardzo szybko, ale jest wygodniejsze od ipython console |
| jupyter notebook | uruchamia się trochę wolniej, ma spro fajnych opcji, najbardziej przydaje się gdy chcemy udokumentować to, co robimy w kodzie aby np. później podzielić się z innymi. Niektórzy jednak wszystko robią w notebooku. |
| spyder | otwiera się wolniej, ale stanowi całe zintegrowane środowisko do kodowania (IDE), na początku ilość guzików, menu i okien może nieco przestraszyć, ale szybko okazuje się że gdy planujemy dłuższą posiadówkę z pythonem - spyder potrafi być wygodniejszy od jupyter notebooka. Tryb debugowania spydera bardzo się przydaje. |
| [rodeo](https://www.yhat.com/products/rodeo) | IDE w stylu R Studio, bardziej ograniczone od spydera (przynajmniej na razie) ale niektórym może przypaść do gustu większą prostotą i przejrzystością. |

Na warsztatach będziemy korzystać przede wszystkim z:
* jupyter qt console
* jupyter notebook
* spyder

inne narzędzia:
* Atom - zaawansowany edytor tekstowy, wraz z pakietem [Hydrogen](https://atom.io/packages/hydrogen) działa podobnie do `jupyter qt console` ale edycja kodu jest dużo wygodniejsza, zresztą sami zobaczcie: http://tinyurl.com/zvn3k5p  
* sublime text (zaawansowany, wszechstronny edytor tekstowy, Atom jest nim inspirowany, sublime jest jednak znacznie szybszy)
* PyCharm (złożone IDE)
* Python IDLE (jest, ale chyba nie ma sensu go używać :) )

## Skróty klawiszowe
Jupyter notebook:
ctrl+enter -  
shift+enter -  
alt+enter?  

esc - wychodzimy z trybu edycji do trybu nawigacji  
w trybie nawigacji:  
a - utwórz komórkę powyżej obecnie aktywnej  
b - utwórz komórkę poniżej obecnie aktywnej  
dd - usuń aktywną komórkę  
x - wytnij aktywną komórkę  
v - wklej wyciętą komórkę  
m - zmień typ komórki na markdow   
l - pokaż numery linii w aktywnej komórce  
h - help, wyświetla wszyskie skróty klawiszowe  

Spyder:
F9 - uruchom plik  
ctrl+F5 - uruchom plik w trybie debugowania  
ctrl+shift+F11 - uruchom plik i zatrzymaj przy najbliższym breakpoincie (czerwonej kropce)  

