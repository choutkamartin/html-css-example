# Popis ke stránce
## Třídy, ID
Třídy a ID jde jinak teda samozřejmě dávat i k jednoduchým elementům např:
```html
<button class="button-lg">Mám třídu button-lg</button>
```

Jinak největší prioritu má teda ID, které musí být ale jedinečné, poté je třída (class), která může být u několika elementů a až poté je element.
Pokud ale uděláme 
```css
#konkretniText {
  color: red;
}

#konkretniText {
  color: green;
}
```
Tak bude mít element s ID `konkretniText` barvu zelenou. Proč? Protože v tomhle případě `color: green` přepisuje `color: red`, protože je v CSS dokumentu později. Pozdější změny přepisujou ty změny dřívější.
##
