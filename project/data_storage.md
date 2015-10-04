## Armazenamento de Dados

Existe várias formas de se garantir o armazenamento correto dos dados em uma aplicação, visando um prototipo mais simplista e com um modelo de dados não tão complexo atualmente, pareceu ser mais assertivo a utilização do [**Table Data Gateway**](http://martinfowler.com/eaaCatalog/tableDataGateway.html) , padrão este explicado por Martin Fowler em seu livro *Patterns of Enterprise Application Architecture* como sendo uma boa abordagem para aplicações menos complexas, mas que necessitam de uma divisão clara entre o código é a camada de persistência.

Pode parecer meio presunçoso, porém utilizar Padrões de Projetos mesmo em pequenos prototipos como este pode facilitar a reconstrução, melhoramento, correção, prevenção do código. Isto fica transparente a partir da descrição de Erich Gamma em seu livro *Padrões de Projetos*: 

> Um Design Pattern sistematicamente nomeia, motiva e explica o design geral que identifica um problema recorrente no desenvolvimento de sistemas orientados a objetos. Ele descreve o problema, a solução, quando aplicar a solução e as consequências de seu uso. Também é possível que haja dicas de implementação e exemplos. A solução é um arranjo geral de objetos e classes que resolvem o problema. A solução é customizada e implementada para resolver o problema em um contexto particular.

Sendo assim o *Table Data Gateway* nós ajudará a evitar deescrever várias linhas de CRUD, permitindo que consultas mais complexas e rotinas mais trabalhosas ganhem mais tempo hábil para serem desenvolvidas.



