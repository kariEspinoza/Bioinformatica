# Laboratorio 03 - Ensamblaje de genomas y predicción de genes 

Nombre: Karina Espinoza

### Parte 1: El artículo genoma

---

**1.** ¿Cuántos _Sequencing Projects_ y _Analysis Projects_ hay depositados en GOLD? ¿Cuál es la diferencia entre ambos? [2]

    Sequencing Projects = 215.124
    Analysis Projects = 174.491

    La difenrencia esta en que Sequencing es una recopilación o base de datos de genomas y Analysis describe el ensamblaje y anotaciones del anterior proyecto mensionado.

![S_1](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_1.png?raw=true)

**2.** ¿Cuál es el dominio más representado en la base de datos, _archea_, _bacteria_, _eukaryote_, o _virus_? [1]

    El dominio más representado Bacteria.

![S_2](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_2.png?raw=true)

**3.** ¿Cuáles son los _phyla_ más representados entre los proyectos de genomas bacterianos en la base de datos? [1]


    El _phyla_ más representados en la base de datos son Proteobacterias con un 37,3%

![S_3](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_3.png?raw=true)

**4.** ¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.) [1]


    La mayor cantidad de genomas bacterianos depositados en GOLD son proyectos de tipo medico.
![S_4](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_4.png?raw=true)

---

#### A continuación, vamos a trabajar con el genoma del Bonobo [(_Pan paniscus_)](https://www.ncbi.nlm.nih.gov/genome/?term=txid9597[Organism:noexp]).
---  

**5.** ¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma) [2]


    El artículo orginal donde se reporta el genoma del Bonobo es _The bonobo genome compared with the chimpanzee and human genomes._ Prüfer K, et al. Nature 2012 Jun 28
![S_5](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_5.png?raw=true)

**6.** Explica, qué es el N50, L50, y NG50. [3]

    N50 es una estadistica mediana ponderada, de tal forma que el 50% de todo el conjunto está en contigs o scaffolds igual o mas largos.
    L50 se define como el menor número de contigs, dado que el largo de sus sumas es igual a N50.
    NG50 es igual a N50, excepto que es el 50% del tamaño del genoma conocido o estimado que debe ser de la longitud NG50 o más. Esto permite comparaciones significativas entre diferentes conjuntos. 
    

**7.** ¿Cuál es el propósito de calcular estas estadísticas? [3]

    Para exponer la "integridad" de un conjunto de genoma, pero esencialmente se utilizan para describir la frecuencia de la longitud de los contigs.

**8.** ¿Cuántos _contigs_ conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los _contigs_) [3]

    121.356 contigs conforman el genoma
    N50 = 66.676
    L50 = 11.048

**9.** ¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

    El largo total de la secuencia es de 3286.64 Mb.
    Porhttps://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_7.png?raw=truecentaje GC indica la cantidad de guanina y citosina, este es de 42.3185%.
![S_7](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_7.png?raw=true)

**10.** ¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?

    Sequencing technology es 454 GS FLX; 454 GS FLX Titanium.
    Es un programa que funciona principalmente con la detección de la luz. Esta técnica se basa en la secuenciación por síntesis, donde la intensidad de la señal es proporcional al número de nucleótidos. Toma cientos de imagenes y las convierte en una base de datos.

![S_6](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_6.png?raw=true)
---

### Parte 2: Predicción de genes

-  Tienes misión es predecir qué gene(s) está(n) codificado(s) en la secuencia a continuación.
		
		ATGAGTATCAAAATCTTATCTGAATCAGAAATTAAACAAGTAGCAAATTCATATCAAGCCCCAGCGGTTTTATTTGCCAATCCTAAAAATCTTTACCAACGCAGAGCGAAACGTTTAAGAGACTTAGCACAAAATCATCCTCTATCTGATTATTTATTATTTGCTGCAGACATAGTTGAAAGCCAACTTTCCACGTTAGAAAAAAATCCTTTACCGCCACAACAGCTTGAACAGTTAAATACTATCGAGCCACTAAATGCCAAAACCTTTAAGAGAAACAGTATCTGGCGTGAATACTTAACAGAAATTCTTGATGAAATAAAGCCCAAAGCTAACGAGCAAATTGCTGCAACAATTGAATTTCTTGAAAAAGCCTCTTCCGCTGAATTAGAAGAAATGGCAAATAAACTCTTAGCACAAGAATTTAACTTAGTCAGCAGTGATAAAGCCGTCTTTATTTGGGCTGCACTTTCCCTTTATTGGTTACAAGCAGCTCAACAAATTCCTCATAATAGCCAAGTTGAAAACGCTGAAAATTTACATCACTGCCCTGTTTGTGGTTCTTTACCTGTGGCAAGTATGGTACAAATTGGTACATCACAAGGTTTACGCTACTTACATTGTAATTTATGTGAAAGTGAATGGAATTTGGTACGCGCACAATGCACCAATTGTAATAGTCATGACAAACTCGAAATGTGGTCACTAAATGAAGAACTTGCGCTTGTTCGTGCCGAAACCTGTGGTAGTTGTGAAAGTTACTTGAAAATGATGTTCCAAGAAAAAGATCCTTACGTAGAACCTGTAGCCGATGATTTGGCTTCTATTTTCTTAGATATTGAAATGGAAGAAAAAGGTTTCGCCCGAAGTGGATTAAATCCATTTATTTTTCCTGCAGAAGAAGCATAAAAATATAGCCTAGAAATATCTAGGCTAATTATTTAAATCTATAGATAACACGCCATTACCACTGCATTTTCTCGTCCACCACTGGGTTTCGGATAATAATTTTTCCGAATATCCACTTCATTAAAACCAATTTTTTCATACAAGAAACGAGCAGAGTTAGACTCTCTGACTTCTAGCCATAAGGTTTGGACACCTTTTTCCTTTAATTGAAAGATTAATTTTCCTAACAATAATTTGCCAAATCCACAACCTTGATAAGTAGGCAAAATCGCAATATTAAACAAAGTCGCTTCATCCAATACTGTTTGGCAAATAGCAAAACCGATAATCTGATTATTCTCTATTAATTTTAAATTGAGATAACGCTCCCCTTGATTATTTTTTAACGTACCAAATGACCAAGGCACCAGATGGGCTTGCTGTTCGATTTCATACAATCGCTCGAAATCACAGGCTTCAATTTGAGAAATAATAGACATAATTAAGGCTGCTGAATTTGTTGCCACAACGCTCGTTTGGCTTGATGATTAGATTGAAATTGCTGCCAACTTGGCGAGCGATAAACCTGCTCAGCCTGCTTGCAAAATGGCAAAGTGCGGTCAATTTGGTCGCTATTTTCTGATAGTAACCAATAACGAATAGGCTGTTTACATTCCATATGCTGGATTTGATCGTAATTCAAACATAAACAATTTTCTTTTTTAAGATTAAGGCTTAACAGCACATCAGCCAACAAAGGCGAGCTACTGATATTTTCATCGGAAACAGTGATAAGGCGAATATTCTCTGCCACACTAATTCCTACTGAACCTTGCAGTACCTCGGGGCGATATAATTCCCACTGGGAAATGCCCATTTCTTGTAAAAGAAGATCGCGTCTGTTCATAAGTGAATTTTTAAAAACGTTGCTTGAAAAATAGTGTTAATTTCTTTTATTAATCTTTGCTAAAATGGTGCGTAATTTTAACCAATAACCCACAGGATTCAAAGCG

---

**11.** Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [_start_] y término [_stop_])? [3]

    7 ORFs encontrados.
    1-3-2 en hebra + y 4-5-6-7 en hebra -.
    largos:
    ORF1 (909|302), ORF2 (78|25), ORF3 (99|32), ORF4 (441|146), ORF5 (405|134), ORF6 (84|27) y ORF7 (144|47).
    Se sobreponen 1-7, 4-6, 3-5 y 4-2.
![S_8](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_8.png?raw=true)

**12.** ¿Qué tipo de programa es ORFfinder, _Ab initio_ o por homología? [2]

    ORFfinder es de tipo _Ab initio_

---

Utilizamos **[BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi)** 

---

**13.** ¿A qué organismo pertenece la secuencia en cuestión? [2]

Pertenece a Haemophilus influenzae
![S_9](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_9.png?raw=true)

**14.** ¿Qué gen(s) está(n) codificados en la secuencia? [2]

FdhE superfamily, NAT_SF superfamily y DNA_III_psi superfamily.
![S_10](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_10.png?raw=true)

**15.** Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)? [3]

Utilizando BLAST y ORFfinder en conjunto se identificÓ que:
ORF1 = FdhE superfamily
ORF4 = NAT_SF superfamily
ORF5 = DNA_III_psi superfamily

Estos corresponderian a los correctos, ya que para los ORFs restantes no se encontro dominio.


Los ORFs correctos son

---

##### No olvides enviar tu informe de laboratorio al correo electrónico de la profesora ayudante: kat.mendez@uandresbello.edu. Tienes plazo hasta las 23:59 hrs del día jueves de la semana siguiente.
##### También, recuerda estudiar las lecturas designadas para la próxima semana. Puedes revisarlas en "Controles de entrada y lecturas" de la página del curso, [aquí](https://github.com/bioinf-biotec/labs_bioinf). 
