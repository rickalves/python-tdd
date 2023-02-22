# TDD com Python

`Projeto de estudo do TDD com a linguagem Python.`


## **O que é o ```TDD```** ?
>**TDD** é uma sigla para (**Test Driven Development**), ou *Desenvolvimento Orientado a Testes*. A ideia do TDD é que você trabalhe em ciclos. Estes ciclos ocorrem na seguinte ordem:

1. Primeiro, ***escreva um teste unitário*** que inicialmente irá falhar, tendo em vista que o código ainda não foi implementado;
   
2. ***Crie o código*** que satisfaça esse teste, ou seja: implemente a funcionalidade em questão. Essa primeira implementação deverá satisfazer imediatamente o teste que foi escrito no ciclo anterior;
   
3. Quando o código estiver implementado e o teste satisfeito, ***refatore o código*** para melhorar pontos como legibilidade. Logo após, execute o teste novamente.

   
## **Fluxo do TDD**
#
   
<div style="text-align:center">
    <img alt="ciclo tdd" src="./img-tdd.png" width="400px">
</div>

#

* <span style="color:red">**Red:**</span> escreva um pequeno teste automatizado que, ao ser executado, irá falhar;
  
* <span style="color:green">**Green:**</span> implemente um código que seja suficiente para ser aprovado no teste recém-escrito;
  
* <span style="color:purple">**Refactor:**</span>  refatore o código, a fim dele ser melhorado, deixando-o mais funcional e mais limpo.
  
## **Quas os benefícios do `TDD` ?**

* Existem diversos benefícios ao escrevermos os testes antes mesmo de realizar uma implementação.
   
*  Um dos benefícios é que, como você vai saber o que o código precisa fazer antecipadamente, evitando escrever código complexo ou que não siga os pré-requisitos de negócio.
*  Além disso, se você for deixar para testar as funcionalidades do seu código depois, você pode acabar não realizando os testes como deveria.
  
#
## **Como fazer testes unitários?**
  * Existem diversas ferramentas para realização de testes unitários. Alguns exemplos para diferentes linguagens são:



> Linguagem   | Ferramenta
> --------- | ------
> .NET | `NUnit`
> PHP  | `PHPUnit`
> Node.js | `Jest`
> Java | `JUnit`
> Python | `Pytest`
#
## **Como fazer TDD em Python ?**
* O **```Pytest```** é a ferramenta mais utilizada para fazer testes unitários com o Python! 
  
* O pytest é um framework de teste para python que provê soluções para executar testes e fazer validações diversas, com a possibilidade de estender com plugins e até rodar testes do próprio unittest do python.
* É o queridinho da comunidade por sua flexibilidade, pela forma que usa fixtures e pela facilidade de estender suas funcionalidades.
* Para instalar é tão simples quanto um:
  
#
### **Instalação do Pytest :**
~~~~
pip install pytest
~~~~
  



