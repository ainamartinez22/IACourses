
# MEAN, MEDIAN AND MODE

Si les dades son skewed (esbiaixades) i tenim algun outlier molt extrem, la mitja quedarà molt afectada per aquest, mentre la mitjana es mantindrà estable <br/>
(*Exemple: mitjana de fills a les famílies d'un poble, una família amb 100 fills afectaria molt en la mitjana però pot en la mediana*) <br/>
(*Exemple: mitjana de beneficis per estatunidenc, és molt alta però la mediana molt més baixa pq els pocs rics afecten en l'estimador*) <br/><br/>

**NECESSITEM UN ESTIMADOR ROBUST**

Per això es important escollir un bon estimador i comprovar la distribució de les dades

**NO eliminar mai els outliers** --> provocaríem un sesgo en la mostra, modificaríem les inferències obtingudes (la variancia per ex) i la mida de la mostra

Els outliers s'han de justificar o almenys, disminuir la influencia d'aquests sobre les dades

Outliers afecten a:
- Tests d'hipotesis

- Correlacions

- Regressions

Els metodes robustos s'utilitzen quan les dades presenten aprox un distribució normal amb alguns outliers, si no és així, si són dades més sesgades o amb una altra distribució, no s'han d'utilitzar.