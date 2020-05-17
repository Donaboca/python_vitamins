# python_vitamins
Käsitellään elintarvikkeiden ravintotietoja ja tehdään niistä jonkinlaista analytiikkaa.

Lähtökohtana on yli 2000 elintarviketta sisältävä Excel-tiedosto, joka on peräisin Ruotsista (Swedish food agency). Kyseinen Excel luetaan Pythonilla Pandas data frameen ja tehdään muokkauksia, jotta lopulliseen dataframeen saadaan vain halutut sarakkeet. Lisäksi rivejä karsitaan listan avulla, jotta lopputuloksessa on vain valikoidut elintarvikkeet (lähinnä hedelmiä, kasviksia, marjoja ja pähkinöitä). Lopputulos tallennetaan uuteen Exceliin.

