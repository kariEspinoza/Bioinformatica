
# Laboratorio 01 - Bases de datos biológicas
Nombre: Karina Espinoza
Curso: BIOL
Profesor: 

### Parte 1: Enfermedades genéticas y genes
---

**1.** Nombra y describe brevemente la enfermedad que escogiste, qué la causa y cuáles son sus consecuencias. [3]

**TMRA** o THIAMINE-RESPONSIVE MEGALOBLASTIC ANEMIA SYNDROME (síndrome de Rogers). Enfermedad autosómica recesiva que se caracteriza por presentar tres componentes clínicos principales: diabetes mellitus, anemia megaloblástica e hipoacusia neurosensorial. El síndrome se debe a un defecto genético de una proteína transportadora de tiamina codificada por el gen SLC19A2. Las mutaciones en el gen provocan deficiencia de tiamina en las células beta del páncreas y en otros tejidos afectados, lo que produce defectos en el metabolismo celular, estrés celular y apoptosis. 

**2.** ¿Cuál(es) gene(s) han sido relacionados con esta enfermedad? [1]

SLC19A2 GEN codificante para proteina transportadora de tiamina.

Esta informacion se obtubo de [OMIM](http://www.omim.org/entry/249270).

---
		
**3.** ¿Tiene nombres alternativos el gen? ¿Cuáles? [1]

TC1, THT1, TRMA, THMD1 Y THTR1

**4.** ¿En qué cromosoma está? ¿Cuántos exones tiene? [1]

Localizado en el cromosoma 1q24.2.

![S_1](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_1.jpg)


**5.** ¿Cuántas isoformas de transcritos? [2]

Dos isoformas

* NM_001319667.1 → NP_001306596.1  thiamine transporter 1 isoform 2
* NM_006996.2 → NP_008927.1  thiamine transporter 1 isoform 1
![S_2](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_2.jpg)

**6.** ¿Qué tipo de proteina es codificada por este gen? ¿Cuál es su número EC? [2]

Codifica Thiamine transporter 1 (060779.2) 
![S_3](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_3.jpg)


**7.** ¿Qué genes están inmediatamente río arriba/abajo? [1]

rio arriba : F5
rio abajo : LOC105371605
![S_4](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_4.jpg)
---

**8.** ¿Cuál es la longitud de tu gen? [2]

No se ha encontrado la información.

**9.** ¿Cuántas variantes de tu gen hay descritas y qué tipo de variantes son? [2] 

Respercto a [NCBI](https://www.ncbi.nlm.nih.gov/clinvar/?term=SLC19A2[gene]) se encuentran descritas 81 variantes clasificadas en los siguientes tipos:

1. Deletion (15)
2. Duplicacion (9)
3. Indel (1)
4. Insertion (6)
5. Single nucleotido (56)

**10.** ¿Las sustituciones (i.e. cambio de un nucleótido) corresponden a cambios sinónimos o no sinónimos? [2]

Corresponden a 

**11.** ¿Existen ortólogos de tu gen en otras especies? ¿Cuántos? [1]

Si, en ratones y 230 especies mas.
![S_5](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_5.jpg)

**12.** ¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos? [1]

No se an encuentran registros respecto a estos para este gen.

---

### Parte 2: Rutas y procesos metabólicos
---

**13.** Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por KEGG? ¿Cuáles? [1]

No se encuentran nuevos nombres en la plataforma KEGG.

**14.** ¿Cuál es el número de identificación de tu gen (_entry number_)? [1]

Número de identificación 10560.

**15.** ¿En qué rutas metabólicas participa la proteína codificada por tu gen? [1]

Participa en Vitamin digestion and absorption (hsa04977)

![S_6](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_6.jpg)

**16.** ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso? [1]

El gen se puede encontrar en las siguientes bases de datos:
- NCBI-GeneID: 10560
- NCBI-ProteinID: NP_008927
- OMIM: 603941
- HGNC: 10938
- Ensembl: ENSG00000117479
- Vega: OTTHUMG00000035452
- Pharos: O60779(Tbio)
- UniProt: O60779 A0A024R928

![S_7](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_7.jpg)
información recopilada de [KEEG](https://www.kegg.jp/dbget-bin/www_bget?hsa:slc19a2)

---
**17.** Escoge una ruta metabólica y seleccionala para ver el diagrama correspondiente, toma una captura de pantalla e incluyela en tu informe. [1]

Ruta metabolica de la digestión y absorción de vitaminas.
![S_8](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_8.jpg)

**18.** ¿Qué significan los cuadros verdes en el diagrama? (Pista: haz clic en `Help`) [2]

Los cuadros verdes se hipervinculan a las entradas GENES convirtiendo los identificadores KO en identificadores génicos en la vía de referencia, es decir, evidencia la presencia de genes en el genoma y la integridad de la ruta.

**19.** ¿Con qué otra(s) ruta(s) se cruza la ruta metabólica que escogiste? [2]

Se cruza con _Tight junction_(hsa04530), _Pantothenate and CoA biosynthesis_(ko00770), _Riboflavin metabolism_(ko00740), _Bile secretion_(hsa04976) y _Retinol metabolism_ (ko00830).

---

**20.** ¿Cuáles son las principales ontologías o dominios que conforman Gene Ontology? [2]

Compilaciones neutras de anotaciones de gene products en una amplia variedad de formas de vida.

**-** Ve a "_Tools_" --> "_AmiGO 2_" y escribe en la casilla de búsqueda: "GO:0006096".  

**21.** ¿A qué corresponde este término y qué otra información te entrega la página? [3]

Procesos glucolíticos, documentos de tipo gene ontology, etc.

**-** Haz clic en "Graph Views" y examina el gráfico.

**22.** Escribe 10 categorías GO a la cual GO:0006096 pertenece. [2]

No se encuentra la información.

---

### Parte 3: Descargando secuencias, convirtiendo formatos
---

**23.** ¿Cuántos items fueron encontrados? ¿cuántos en animales? [1]

Fueron encontrados 72821 items y en animales 14116 items.
![S_9](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_9.jpg)

**-** Probablemente tus resultados fueron una mezcla de fragmentos de genes, regiones codificantes parciales, genes completos, etc. Filtra tus datos por mRNA, animales, RefSeq. Haz clic en la entrada para la secuencia de GAPDH de _Danio rerio_. 
		
**24.** ¿Cuál es la longitud del gen? [1]

Es de 1328 bp
		
**25.** ¿Cuál es la referencia bibliográfica más reciente? [1]

Chlorella diet alters mitochondrial cardiolipin contents differentially in organs of Danio rerio analyzed by a lipidomics approach.

**26.** ¿Cuál es el número de acceso? [1]

PUBMED: 29494608

![S_10](https://github.com/kariEspinoza/Bioinformatica/blob/master/Screenshot_10.jpg)

**27.** Descarga la secuencia en formato [FASTA](http://www.bioinformatics.nl/tools/crab_fasta.html) y agrégala a tu informe. [1]

Danio rerio glyceraldehyde-3-phosphate dehydrogenase (gapdh), mRNA
NCBI Reference Sequence: NM_001115114.1

>NM_001115114.1 Danio rerio glyceraldehyde-3-phosphate dehydrogenase (gapdh), mRNA
ACTCACACCAAGTGTCAGGACGAACAGAGGCTTCTCACAAACGAGGACACAACCAAATCAGGCATAATGG
TTAAAGTTGGTATTAACGGATTCGGTCGCATTGGCCGTCTGGTGACCCGTGCTGCTTTCTTGACCAAGAA
AGTGGAGATCGTGGCCATCAATGACCCATTCATTGACCTTGATTACATGGTTTACATGTTCCAGTACGAC
TCCACCCATGGAAAGTACAAGGGTGAGGTTAAGGCAGAAGGCGGCAAACTGGTCATTGATGGTCATGCAA
TCACAGTCTATAGCGAGAGGGACCCAGCCAACATTAAGTGGGGTGATGCAGGTGCTACTTATGTTGTGGA
GTCTACTGGTGTCTTCACTACTATTGAGAAGGCTTCTGCTCACATTAAGGGTGGTGCAAAGAGAGTCATC
ATCTCTGCCCCAAGTGCAGATGCCCCCATGTTTGTCATGGGTGTCAACCATGAGAAATATGACAACTCTC
TCACAGTTGTAAGCAATGCCTCCTGCACCACCAACTGCCTGGCTCCTTTGGCAAAGGTCATCAATGATAA
CTTTGTCATCGTTGAAGGTCTTATGAGCACTGTTCATGCCATCACAGCAACACAGAAGACCGTTGATGGG
CCCTCTGGGAAGCTGTGGAGGGATGGCCGTGGTGCCAGTCAGAACATCATCCCAGCCTCCACTGGGGCTG
CCAAGGCTGTAGGCAAAGTAATTCCTGAGCTCAATGGCAAGCTTACTGGTATGGCCTTCCGTGTCCCCAC
CCCCAATGTCTCTGTTGTGGATCTGACAGTCCGTCTTGAGAAACCTGCCAAGTATGATGAGATCAAGAAA
GTCGTCAAGGCTGCAGCTGATGGGCCCATGAAAGGAATTCTGGGATACACGGAGCACCAGGTTGTGTCCA
CTGACTTCAATGGGGATTGCCGTTCATCCATCTTTGACGCTGGTGCTGGTATTGCTCTCAACGATCACTT
TGTCAAGCTGGTCACATGGTATGACAATGAGTTCGGTTACAGCAACCGTGTATGTGACCTGATGGCACAC
ATGGCCTCCAAGGAGTAGATGTGACCCCTTTGCTGTTTCTTTTTTTTGATACGCGACCATTCTCCCATCT
GGTTGAATGTTTGCACCACGTGCCTGGAAGGAAATTACATGCTTAAATTGAAGACCAATATTATTTTTAT
ATACTCTGTTCTGTTTCGTGTGTGAGGTTAAAAATAAATGTTGACTTCAAAGGCTTTTCTGTCTGTTAAC
AACTTGCGATGGAATAAAAGTCCTCTGTTTGTGAGAAATGAAAAAAAAAAAAAAAAAAAAAAAAAAAAA

**28.** Adjunta la secuencia en formato NEXUS a tu informe. [1]
[Secuencia en formato NEXUS](https://www.ebi.ac.uk/Tools/services/rest/emboss_seqret/result/emboss_seqret-I20180810-044651-0598-64715736-p2m/out)

---

### Parte 4: Buscando artículos científicos en línea

---

**29.** En tu informe, incluye una captura de pantalla de tu alerta. Si es que recibes una alerta en tu correo electrónico, también puedes adjuntarla en tu informe. [1]



---

**30.** En tu informe agrega una captura de pantalla de tu suscripción o del correo electrónico de confirmación. [1]

---

Para finalizar esta parte vamos a prácticar el uso de **operadores de búsqueda en Google Scholar**. Entra a [Google Scholar](https://scholar.google.com).

---

**-** Haz una búsqueda, por ejemplo, busca "Human Microbiome" (puedes buscar cualquier otro término).

**-** Ahora usa comillas para realizar tu búsqueda "Human Microbiome".
			
**31.** ¿Son los resultados idénticos o no? [1]

El uso de comillas restringe los resultados a resultados donde la frase que buscas aparece de manera exacta.

**-** También puedes usar `*` para representar una palabra que falta, e.g., "Human Microbiome" *.

**32.** ¿En qué cambiaron los resultados de la búsqueda? [1]

**-** También puedes condicionar tus búsquedas a rangos de números como precios, años, etc. Prueba escribiendo lo siguiente en google.com: 14 inch...17 inch laptops.

**33.** ¿Qué encuentras en los resultados? Prueba sin el rango también. [1]

**-** Para buscar artículos científicos también es útil restringir los resultados de búsqueda a tipos de archivo. Prueba escribiendo: "human microbiome" filetype:pdf.

**34.** Describe tus resultados. [1]

**-** Otro truco útil es usar signos `-` y `+`. Por ejemplo, trata buscar: "PCR amplification" +temperature. Y luego: "PCR amplification" -temperature.

**35.** ¿En qué cambian los resultados de la búsqueda? [1]

**-** Finalmente, prueba los operadores _Boolean_ que representan opciones de inclusión. Por ejemplo, trata con: Soil OR Human pathogens. Y luego trata con: Soil AND Human pathogens.

**36.** De nuevo, ¿en qué cambian los resultados de la búsqueda? [1]
