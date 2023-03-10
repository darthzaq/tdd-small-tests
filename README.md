<p align="center">
  <a href="https://codely.com">
    <img src="https://user-images.githubusercontent.com/10558907/170513882-a09eee57-7765-4ca4-b2dd-3c2e061fdad0.png" width="300px" height="92px"/>
  </a>
</p>

<h1 align="center">
  Refactoring from Code Smells to Clean Code
  <br />
  π§Όπ© π ππ¦
</h1>

<p align="center">
    <a href="https://github.com/CodelyTV"><img src="https://img.shields.io/badge/CodelyTV-OS-green.svg?style=flat-square" alt="CodelyTV Open Source"/></a>
    <a href="http://codely.tv/pro/cursos"><img src="https://img.shields.io/badge/CodelyTV-PRO-black.svg?style=flat-square" alt="CodelyTV Pro Courses"/></a>
</p>

<p align="center">
  Showcase of the refactorings and code smells catalog illustrated with practical examples in different programming languages.
  <br />
  <br />
  <a href="https://pro.codely.tv/library/refactoring-code-smells-clean-code-bloaters/">π₯ View refactoring course</a>
  Β·
  <a href="https://github.com/CodelyTV/refactoring-code-smells/stargazers">β­ Star this repository</a>
  Β·
  <a href="https://github.com/CodelyTV/refactoring-code-smells/issues">βοΈ Propose an example</a>
</p>

## π§  Concepts 

### π© Code Smells

These are what we could consider as potential bad practices. Things such as long methods, nested conditionals, feature envy, and so on π

The different Code Smells are grouped based on the following taxonomy ([source](https://mmantyla.github.io/BadCodeSmellsTaxonomy)) where you will find each one of the single examples:

* Bloaters: Something that has grown so large that it cannot be effectively handled
* Object-Orientation Abusers: Solutions that does not fully exploit the possibilities of object-oriented design
* Change Preventers: hinder changing or further developing the software
* Dispensables: Something unnecessary that should be removed from the source code
* Couplers: Promotes coupling (knowledge particularities) between different classes

### π§Ό Refactorings

π·β Work in progress

### π Examples

π·β Work in progress

## π€― How to explore this repository

You have the following 3 main folders:

* π© Code Smells
* π§Ό Refactorings
* π Examples

The purpose of this repository is to illustrate with some _π Examples_ how we can detect _π© Code Smells_ and evolve a specific code applying _π§Ό Refactorings_ technics.

That is the reason why the code will always be located in the _π Examples_ folder with a folder for each of its possible evolutions, and linked from the _π© Code Smells_ and _π§Ό Refactorings_ directories using symbolic links.

## π Examples completeness

The examples you will find in this repository are completely operational projects that you can open up in your IDE and start refactoring executing the provided test suite.

That is, we understand that in order to have a better learning experience, you must have the whole picture of the specific code snippet you actually want to analyze. This gives you the freedom to modify it right away after cloning this project without having to worry about _boilerplaty aspects_.

## π€ Contributing

Feel free to open an issue explaining how you want to contribute before starting out coding and we will help you figuring out the best way to approach it π


## π€ TDD tips

Existen 3 formas de dirigirnos hacia la soluciΓ³n:
     - Obvious iimplementation
     - Fake it
     - Triangulacion

Fases del TDD:
   - Fase roja: Hacer el test para cumplir un objetivo en concreto antes que el cΓ³digo (no generalizar)
   - Fase verde: Hacer el cΓ³digo justo para cumplir con el objetivo y pasar el test.
   - Fase azul: mejorar y generalizar el cΓ³digo y el test para hacerlo mΓ‘s mantenible.
     - Un nivel de indentaciΓ³n por mΓ©todo 
     - No uses la palabra clave else
     - Envuelve primitivos
     - Colecciones como clases de primer orden
     - Aplica la Ley de Demeter
     - No abrevies
     - MantΓ©n las entidades pequeΓ±as
     - Evita mΓ‘s de dos atributos de instancia
     - Evita getters y setters o atributos pΓΊblicos
     - Clases con estado: evita mΓ©todos estΓ‘ticos

