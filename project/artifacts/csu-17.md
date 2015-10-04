|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-17](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Visualizar relátorio de histórico visual da esfuta|
|**Objetivo:**|Apresentar histórico Visual das Estufas|
|**Pré-Condição do Caso de Uso:**|Não há|
|**Ator(es):**|Operador|
|**Evento inicial do Caso de Uso:**|Não há|
|**Fluxo Principal:**|<ul><li>Ator informa periodo e estufa que deseja visualiar informações.</li><li>Sistema verifica validade dos dados coletados.</li><li>Sistema reune informações e apresenta relatório cronologico e visual da estufa.</li></ul>| 
|**Fluxo Alternativo:**|<ul><li>Sistema verifica validade dos dados coletados.</li><li>Sistema inicia nova coleta de dados, realizando caso de uso: '*Coletar dados Agregados de Cluster de Estufas*'.</li><li>Sistema reune informações e apresenta relatório cronologico e visual da estufa.</li></ul>|
|**Fluxo de Exceção:**|FE01:<ol><li>Periodo informado por Ator para visualização de informações, não possui dados coletados.</li></ol>|
|**Pós-Condição do Caso de Uso:**|Não há|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|[CSU-04](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-04.md)|
|**Regras de Negócios Relacionadas:**|Não há|
