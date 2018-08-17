# Laboratorio 02 - Alineamiento de secuencias

#### Nombre: Karina Espinoza

### Parte 1: Colectar genes homólogos

---  
		
**1.** ¿Qué función cumple el gen SRY? [2]

Determinación sexual en mamíferos localozado en el cromosoma Y, codifica para la proteina TDF, es decir, factor determinante de los testículos.

**2.** ¿Cuántos genes ortólogos están anotados en esa base de datos? [1]

Están anotados 29 genes ortólogos en la base de datos NCBI
![S_1](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_1.png?raw=true)

---
### Parte 2: Alineamiento múltiple

--- 

**3.** ¿Qué es el EMBL-EBI? [2]

> Es el instituto Europeo de Bioinformática, pertenece al Laboratorio Europeo de Biología Molecular o EMBL. Es una colaboración con científicos e ingenieros de todo el mundo, por medio del desarrollo de bases de datos, herramientas y software que hacen posible alinear, verificar y visualizar los diversos datos producidos en la investigación hacer que la información esté disponible libremente para todos. 

**4.** ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas? [2]

    MUSCLE es una de las herramientas de MSA es especialmente buena con proteinas y adecuado para alineaciones medianas 
![S_2](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_2.png?raw=true)

**5.** ¿Qué otros tipo de herramientas ofrece EMBL-EBI? [2]

    Ofrece diversas herramientas de MSA adecuadas a diferentes tamaños de alineaciones como: **Clustal**, **Omega** y **Very fast**.
    
    Y otros como:
    
    - Alineación de secuencia múltiple mediante el programa **MView**.
    
    - **T-Coffee** es una herramienta MSA que intenta mitigar los riesgos de los métodos de alineación progresiva. Pequeñas alineaciones.
    
    - **WebPRANK** es un nuevo programa de alineamiento múltiple. Hace uso de información evolutiva.

---

**6.** ¿Cuál es el costo de abrir un gap? [1]

    1.53 puntos de penalización

**7.** ¿Cuál es el costo de extender un gap? [1]


    0.123 puntos de penalización

---

		
**8.** ¿Cuál es la longitud total del alineamiento? [1]

    La longitud total es de 771

![S_4](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_4.png?raw=true)

---
		
**9.** ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos? [2]


    Piliocolobus tephrosceles 0.00135

**10.** ¿Cuál es el más lejano? [2]

    Bos indicus 0.00109 y Bison bison 0.00326 son los mas lejanos

**11.** ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro? [2]

    Equus przewalskii 0.00047 es la especie mas cernana al burro

![S_3](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_3.png?raw=true)

---
		
**12.** ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye? [3]
    
    En el alineamento si el costo aumenta probablemente se abriran menos gap y la longitud total será menor, si disminuye ocurriría lo contrario.

**13.** ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye? [3]

    En el alineamento si el costo aumenta probablemente se preferirá abrir gap si el costo de este último es menor, si disminuye ocurriría lo contrario.

---

- Prueba aumentando el costo de abrir gaps cambiando el valor de 1.53 a 2.0.

---
		
**14.** ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento? [2]

La longitud se mantuvo.

**15.** Prueba lo mismo, pero esta vez **disminuyendo al mínimo el costo de extender un gap**. Describe cómo cambia el alineamiento. [2]

---

#### Parte 3: Diseño de partidores

Secuencia utilizada [SRY](https://www.ncbi.nlm.nih.gov/nuccore/NM_003140.2?from=139&to=753&report=fasta)

---

**16.** Agrega a tu informe una lista de los "_LEFT PRIMER_" y "_RIGHT PRIMER_" que obtuviste usando Primer3. [3]
![S_5](https://github.com/kariEspinoza/Bioinformatica/blob/master/imageneslab2/Ss_5.png?raw=true)
Aqui abjunto la lista de los [partidores](https://github.com/kariEspinoza/Bioinformatica/blob/master/PRIMER_L_R.txt)

---

**17.** Indica los partidores _forward_ y _reverse_ que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano. [5]

    Elegi los partidores:
    AGAGTGAAGCGACCCATGAA
    CGAAGATGCTGCCGAAGAAT


**18.** ¿Cuál es el largo del amplicón? ¿Y la temperatura de _annealing_ sugerida? [3]


	
---