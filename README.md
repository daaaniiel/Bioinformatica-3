# Laboratorio Bioinformatica 3

#####  Daniel león Guajardo
 
> Parte 1: El artículo genoma

##### ¿Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?
 
 Han sido depositados 14.052 genomas en gold. Si, son los mismos que en GENBANK, cabe destacar que GENBANK es dependiente de NCBI, por lo tanto se puede inferir que poseen cantidad de genomas similares, a diferencia que NCBI posee la particularidad de tener además bases no curadas (por lo tanto, es mas grande). 
#####	¿Cuál es la distribución de procariontes y eucariontes secuenciados?
Eucariontes 410, procariontes 9843
##### ¿Qué es el N50, L50, NG50?
El N50 se define como el contigs con la longitud de secuencia más corta al 50% del genoma.
Por lo tanto, si poseo un conjunto de contigs, donde cada uno posee su propia longitud, el contigs de longitud más corta con respecto al conjunto que da el 50%, será el N50.
El L50  se define como el menor número de contigs cuya suma cubra la mitad del genoma.
Finalmente NG50 es un concepto similar a N50, a diferencia que NG50 considera el tamaño real del organismo.
 
#####	¿Cuál es el propósito de calcular estas estadísticas?
 El propósito radica en lo objetivo y realista que puede ser un resultado.
 
#####	¿Cuál es el genoma que escogiste? Adjunta la referencia.
El genoma escogido es el de Oryza brachyantha.
https://www.ncbi.nlm.nih.gov/genome/?term=txid4533[Organism:noexp]
 
#####	¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?
El N50 del genoma escogido es de 20448, cabe destacar que L50 es de 3584, sin embargo no se reporta el NG50.
#####	¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?
El tipo de tecnología utilizado para secuenciar el genoma fue la plataforma Illumina GA II, el cual utiliza un enfoque de secuencias de escopeta de genoma completo.
 
##### ¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?

El organismo escogido es la  Oryza brachyantha. Posee 12 cromosomas y una longitud total (Mb) : 259.908

> Parte 2: Predicción de genes
##### ¿Cuántos ORF o genes encontró ORFfinder?
ORFfinder encontró 7 ORF.
#####	¿Cuántos ORF o genes encontró Glimmer?
Glimmer encontró 10 ORF.
#####	¿Alguno de los genes predichos por estas herramientas coinciden?
No, pero cabe destacar que en el caso del ORF 3 de ORFfinder, posee la misma posición STOP que G10 en Glimmer, sin embargo, poseen aperturas diferenes.	
##### ¿En qué hebra están codificados?
Primeramente con los resultados de ORFfinder, ORF1,2 y 3 se encuentran en la hebra templada, por otra parte, ORF 4, 5, 6 y 7 se encuentran en la hebra retrasada. Con Glimmer, G1, G6, G7 Y G10 se encuentran en la hebra templada, y G2, G3, G4, G5, G8 Y G9, pertenecen a la hebra retrasada. 	
##### ¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?
Es un programa capaz de encontrar genes en DNA microbiano( especialmente bacterias, archeas y virus). Además utiliza modelos de Markov interpolados (IMM), y de esta manera poder identificar las regiones de codificación y distinguirlas del ADN no codificante. Se utiliza Ab initio como técnica.

