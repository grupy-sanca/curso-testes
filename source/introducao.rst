Introdução
==========

O que são testes?
-----------------

Testes são verificações de confiabilidade e qualidade da aplicação perante 
critérios pré estabelecidos.

Na prática, são scripts que verificam se a aplicação apresenta o comportamento 
esperado em diferentes cenários. 

Qual é a importância dos testes?
--------------------------------

Do ponto de vista de produto, testes feitos de maneira sistemática geram 
credibilidade quanto ao cumprimento dos requisitos, estabelecendo um nível de 
garantia do funcionamento esperado ao cliente/usuários.

Do ponto de vista de desenvolvimento, testar uma aplicação dá aos 
desenvolvedores uma visão mais clara e estruturada dos diferentes cenários 
sobre os quais a aplicação gera diferentes resultados. Isso torna o 
desenvolvimento mais organizado e garante que determinado resultado foi 
atingido por uma execução esperada de passos intermediários, e não por 
coincidência lógica, assim diminuindo drasticamente as possibilidades de erros. 

Do ponto de vista financeiro, testes reduzem custos, pois diminuem a ocorrência 
de bugs e custos com manutenção no longo prazo. 

Do ponto de vista de gestão, testes aprimoram o planejamento de execução 
rastreabilidade da maturidade e desenvolvimento das diferentes partes do 
software. Por exemplo, é possível definir previamente quais componentes 
requerem maior confiabilidade e alocar recursos de testes para os mesmos, bem 
como acelerar o desenvolvimento de componentes menos críticos. 

Quais são os tipos de testes?
-----------------------------

Testes podem ser aplicados em diferentes camadas da aplicação. Os principais 
tipos de teste são o Unitário, de Integração e de Sistema. 

Os Testes Unitários verificam um módulo, parte pequena e isolada do software, 
identificando erros de lógica e implementação. 

Testes de Integração verificam a interação entre diferentes módulos do sistema. 

Já o Teste de Sistema verifica a aplicação como uma camada de abstração maior 
de maneira a testar seu todo, assim validando o cumprimento dos requisitos, sem 
se preocupar em como estão sendo implementados internamente, o que já deve ter 
sido testando em testes unitários e de integração.

Exemplo simples
---------------


Conceitos importantes
---------------------

.. TODO

- cobertura
- TDD
- código testável vs. código não testável (escrever o código com testes em mente)
- automatizar testes

Exemplos de frameworks
----------------------

unittest, pyunit, pytest, doctest...

Livros, artigos, links
----------------------
