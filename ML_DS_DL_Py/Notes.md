
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

# STANDARD DEVIATION AND VARIANCE

Les desviacions estandard ($\sigma$) s'utilitzen com a mesures per trobar els outliers en les distribucions de punts. Els valors a un màxim d'una desviació estandard de la mitjana es consideren valors típics, més enllà són valors atípics (outliers).

# PROBABILITY MASS FUNCTION AND DENSITY FUNCTION

Mass function --> si tenim dades discretes no contínues (histograma)
Density/probability function --> si tenim dades contínues (corva)

# COMMON DATA DISTRIBUTIONS

## UNIFORME

Tots els valors dins d'un rang tenen una probabilitat constant (uniforme) d'assolir-se
--> la funció de densitat és una línia constant a 1 en aquest rang de valors

## NORMAL/GAUSSIANA


## EXPONENCIAL

pdf = probability density function

## BINOMIAL

dades discretes

## POISSON

si tens la mitjana d'esdeveniments que passen en un període de temps

# PERCENTILES

S'ordenen les dades --> quin és el percentatge menor a un valor?
Percentil 50 = mitjana

# MOMENTS

Mesures de la forma de la funció de densitat (no depenent d'on estan els valors assolits)
1r moment = mitjana
2n moment = variancia
3r moment = biaix (skew) --> si la corba te la cua desplaçada cap algun costat
4t moment = curtosis --> l'amplada del pic de la corva
