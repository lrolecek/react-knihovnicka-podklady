# Knihovnička - podklady

Podklady pro příklad Knihovnička, na kterém si zopakujeme základy Reactu.

## Postup

1. Vytvoř si nový prázdný repozitář na GitHubu. Nazvi ho třeba `react-knihovnicka`. Repozitář si naklonuj k sobě na počítač.

1. Otevři naklonovanou složku ve VS Code a přes terminál vytvoř startovací projekt v Reacu pomocí:
   ```
	 npx create-czechitas-app .
	 ```

1. Vymaž startovací kód v komponentě App i v CSS stylech.

1. V repozitáři, kde čteš toto README, najdeš podklady. Zkopíruj si do svého projektu do složky `src`:
   - soubor *style.css*
   - soubor *books.js*
   - složku *img*
   - složku *book-covers* zkopíruj do složky *assets*

1. Vytvoříme komponentu `Header` ve které bude text "Moje knihovnička" v modrém rámečku a v pravém horním rohu bude bílá ikonka s knihou v modrém kolečku.

   Komponentu vložíme do App.

1. Vytvoříme komponentu `Book`, která bude přijímat props `id`, `title`, `author`, `year`, `cover`, `read`.

   V komponentě připravíme HTML a CSS, které zobrazí obálku knihy a vedle ní název knihy, autora, rok vydání.

   Podle hodnoty `read` zobrazíme ikonku, zda je kniha přečtená nebo ne.

1. Do komponenty `App` si naimportujeme seznam knih ze souboru *books.js*.

1. Zobrazíme seznam knih za pomocí komponenty `Book` a nastylujeme seynam tak, aby byly vždy 3 knihy vedle sebe, případně uděláme seznam responzivní.

1. V komponentě kniha upravíme ikonku o přečtení knihy tak, aby fungovala jako tlačítka a měnila knihu na přečtenou/nepřečtenou.

   Změnu přečtenosti budeme muset komunikovat zpět do komponenty `App`, kde máme data o knihách.

1. Všechny provedené změny přidáme do Gitu, uděláme commit a pushneme na GitHub.

