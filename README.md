# Julia

## Jak to spustit

### Na windows

Nainstalujte si [julii](https://julialang.org/downloads/), [vs code](https://code.visualstudio.com/) a [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter#review-details) a pak [Julia extension](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia). Otevřete notebook `about_julia.ipynb`, a snad v `Select kernel` uvidíte julia vs code extension a půjdu i vybrat. Pokud chcete používat z julie Rko nebo python, musíte si je nainstalovat, a adekvátně upravit buňky 2 a 3. Pak kliknete na `Run all`. Možná to bude fungovat.

### Na linuxu

Víte, co děláte.

## Poznatky

Jeden julia proces zabírá 200-300MB RAM(načítá nějaké tabulky pro násobení matic apod.), což nelze jednodušše vypnout,
a všechny funkce se před jejich prvním spuštěním musí předzkompilovat(tím se optimalizují a pak jsou rychlejší, ale tento proces trvá čas),
a proto i malé programy prostě nepoběží méně než 10 sekund. Ze stejných důvodů může docela dlouho trvat spuštění julie samotné.
Připojit se k debuggeru(ladícímu programu) trvá z nějakého důvodu také extrémně dlouho.

## Použití

Současné použití je ve vzdělávání a ve vědě. Kvůli výše zmíněným vlastnostem je zatím naprosto nevhodná pro webové aplikace
a mikrokontrolery.

## Verdikt

Toto je můj názor™.

- Julia může být doporučena jako první programovací jazyk.
- Rychlost běhu programu, kterou se julie prezentuje, je v mnohých ohledech zavádějící.
- Lepší chybové hlášky než python a Rko.
- S trochou cviku je postačující(a plnohodnotnou) náhradou za python a R.
- Je zadarmo a open source.

## Užitečné odkazy

- [julia dokumentace](https://docs.julialang.org/en/v1/)
- [julia balíčky](https://juliapackages.com/)
