<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">DEPARTAMENTO ACADÉMICO DE INGENIERÍA DE SISTEMAS E INFORMÁTICA</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">GUÍA DE LABORATORIO</span><br />
</div>


<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Estructura de Datos y Algoritmos</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Revisión de elementos de programación (Parte I)</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>02</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA INICIO::</td><td>09-May-2022</td><td>FECHA FIN:</td><td>13-May-2022</td><td>DURACIÓN:</td><td>02 horas</td>
</tr>
<tr><td colspan="6">RECURSOS:
    <ul>
        <li>https://www.w3schools.com/java/</li>
    </ul>
</td>
</<tr>
<tr><td colspan="6">DOCENTES:
<ul>
<li>Richart Smith Escobedo Quispe - rescobedoq@unsa.edu.pe</li>
</ul>
</td>
</<tr>
</tdbody>
</table>

# Revisión de elementos de programación

[![License][license]][license-file]
[![Downloads][downloads]][releases]
[![Last Commit][last-commit]][releases]

[![Debian][Debian]][debian-site]
[![Git][Git]][git-site]
[![GitHub][GitHub]][github-site]
[![Vim][Vim]][vim-site]
[![Java][Java]][java-site]

#

## OBJETIVOS TEMAS Y COMPETENCIAS

### OBJETIVOS

- Realizar ejercicios en temas de Estructuras de datos, tipos de datos abstractos, bucles, Arrays, Listas enlazadas, Recursión.

### TEMAS
- TAD
- Arrays

<details>
<summary>COMPETENCIAS</summary>

- C.m. Construye responsablemente soluciones haciendo uso de estructuras de datos y algoritmos, siguiendo un proceso adecuado para resolver problemas computacionales que se ajustan al uso de los recursos disponibles y a especificaciones concretas.

</details>

## CONTENIDO DE LA GUÍA

### MARCO CONCEPTUAL

- https://www.w3schools.com/java/

## EJERCICIO RESUELTO POR EL DOCENTE

#
- ArrayList
- Iterador
- Array de Array

## EJERCICIOS PROPUESTOS
- 1. Invertir un matriz de enteros (2 pts)

    - Ejemplo:
    - A=[1 2 3]	->	Ain=[3 2 1]


    -   ```sh 
        public int[] invertirArray(int[] A){
            /** */
            //Procedimiento para invertir la matriz
            /** */
            return Ain;
        }
        ```


- 2. Rotación a la Izquierda (3 pts)

    - Ejemplo:
    - Si d=2
    - A=[1 2 3 4 5]	->	Aiz=[3 4 5 1 2]

    -   ```sh 
        public int[] rotarIzquierdaArray(int[] A){
            /** */
            //Procedimiento para rotar la matriz
            /** */
            return Aiz;
        }
        ```

- 3. Triángulo recursivo (4 pts)

    - Ejemplo:
    - b=5
    -   ```sh 
        *
        **
        ***
        ****
        *****
        ```

    -   ```sh 
        public void trianguloRecursivo(int base){
            /** */
            //Procedimiento para imprimir triángulo
            /** */
        }
        ```

- 4. Lista (11 pts)
    - Implementa una Lista usando POO con tipos genéricos siguiendo los estándares de Java. (Los métodos para una lista).

    - https://docs.oracle.com/javase/7/docs/api/java/util/List.html

    - Puede ignorar los siguientes métodos:
        - hashCode()
        - iterator()
        - listIterator()
        - listIterator(int index)
        - retainAll(Collection<?> c)
        - toArray()
        - toArray(T[] a)

    - (i) Implemente una clase Node<T> donde T es un tipo genérico, esta clase debe contener al menos dos propiedades. 

    - https://docs.oracle.com/javase/tutorial/java/generics/types.html

    - 1. T data: la información almacenada en el nodo
    - 2. Node<T> nextNode: una referencia al siguiente nodo

    - (ii) Implementar una clase List<T> esta clase debe contener al menos esta propiedad
    - 1. Node<T> root: la referencia sobre el nodo inicial

#

## CUESTIONARIO
- ¿Que diferencia hay entre un List y un ArrayList en Java?

#

## REFERENCIAS
- https://www.w3schools.com/java/

#

[license]: https://img.shields.io/github/license/rescobedoq/pw2?label=rescobedoq
[license-file]: https://github.com/rescobedoq/pw2/blob/main/LICENSE

[downloads]: https://img.shields.io/github/downloads/rescobedoq/pw2/total?label=Downloads
[releases]: https://github.com/rescobedoq/pw2/releases/

[last-commit]: https://img.shields.io/github/last-commit/rescobedoq/pw2?label=Last%20Commit

[Debian]: https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white
[debian-site]: https://www.debian.org/index.es.html

[Git]: https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white
[git-site]: https://git-scm.com/

[GitHub]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[github-site]: https://github.com/

[Vim]: https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white
[vim-site]: https://www.vim.org/

[Java]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white
[java-site]: https://docs.oracle.com/javase/tutorial/


[![Debian][Debian]][debian-site]
[![Git][Git]][git-site]
[![GitHub][GitHub]][github-site]
[![Vim][Vim]][vim-site]
[![Java][Java]][java-site]

[![License][license]][license-file]
[![Downloads][downloads]][releases]
[![Last Commit][last-commit]][releases]