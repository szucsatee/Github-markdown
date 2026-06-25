# Github Markdown

A GitHub Markdown (és a specifikus GitHub Flavored Markdown - GFM) segítségével formázhatod a szövegeket a README.md fájlokban, issue-kban és pull requestekben.

Íme a legfontosabb elemek gyors összefoglalója:

### Fejlécek
Használj `#` jeleket a sor elején. Minél több a `#`, annál kisebb a fejléc.

# Első szintű főcím (H1)
## Második szintű alcím (H2)
### Harmadik szintű alcím (H3)

### Szövegformázás
A szavak kiemeléséhez csillagokat (`*`) vagy alulvonásokat (`_`) használhatsz.

*Dőlt betűs szöveg* vagy _ez is dőlt_  
**Félkövér szöveg** vagy __ez is félkövér__  
***Félkövér és dőlt***  
~~Áthúzott szöveg~~

### Listák
Rendezett, rendezetlen és feladatlisták készítése.

* Első elem (vagy használhatsz - jelet is)
* Második elem
  * Alpont (2 szóköz behúzással)

1. Első számozott elem
2. Második számozott elem

- [x] Kész feladat
- [ ] Folyamatban lévő feladat

### Kódbeillesztés
Soron belüli kódhoz használj egy sormásodjelet (backtick: \`), nagyobb kódblokkokhoz hármat (\`\`\`), a programozási nyelv megnevezésével a szintaxis-kiemeléshez.

Soron belüli `kód` formázás.

```javascript
const üdvözlet = "Helló Világ!";
console.log(üdvözlet);
```

### Linkek és Képek
A linkeknél a szöveg megy szögletes zárójelbe, a képeknél pedig egy felkiáltójel (`!`) áll a kapocs előtt.

[GitHub Oldal](https://github.com)

![Kép leírása](https://github.com)
