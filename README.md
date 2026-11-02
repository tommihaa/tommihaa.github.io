# tommihaa.github.io

Henkilökohtainen portfolio-sivusto, näkyy osoitteessa <https://tommihaa.github.io/>.

Tässä repossa on kolme käsin kirjoitettua sivua ilman buildia, JavaScriptiä, riippuvuuksia
tai ulkoisia pyyntöjä. Pelit ja sovellukset ovat omissa repoissaan, ja portfolio linkittää
niihin. Repon sivut:

- `index.html`: portfolio suomeksi.
- `en/index.html`: sama englanniksi. Kieliversiot linkittävät toisiinsa ja kertovat
  toisistaan `hreflang`-merkinnöillä.
- `dg-android/index.html`: DG Android -sovelluksen suljetun testin liittymisohje
  (englanniksi). Kuvakaappaukset ovat kansiossa `dg-android/kuvat/`.

Portfolion kieliversiot jakavat tyylit (`styles.css`) ja ikonin (`favicon.svg`).
Testisivulla on omat tyylit sivun sisällä.

`.nojekyll` estää Jekyll-käsittelyn, joka muuten ajettaisiin oletuksena ja toisi
templaattimoottorin ilman että sitä valittiin.

**Julkaisu:** push `master`-branchiin. GitHub Pages palvelee juurta suoraan.

Lisenssi: GPL-3.0, ks. `LICENSE`.
