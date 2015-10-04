|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-15](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Visualizar gráfico de acompanhamento do sistema|
|**Objetivo:**|Apresentar informações sobre o status do Sistema|
|**Pré-Condição do Caso de Uso:**|Não há|
|**Ator(es):**|Operador|
|**Evento inicial do Caso de Uso:**|Não há|
|**Fluxo Principal:**|<ul><li>Ator informa periodo que deseja visualiar informações.</li><li>Sistema verifica validade dos dados coletados.</li><li>Sistema reune informações e apresenta gráfico de acompanhamento</li></ul>| 
|**Fluxo Alternativo:**|<ul><li>Sistema verifica validade dos dados coletados.</li><li>Sistema inicia nova coleta de dados, realizando caso de uso: '*Exportar Dados Capturados das Estufas*'.</li><li>Sistema reune informações e apresenta gráfico de acompanhamento.</li></ul>|
|**Fluxo de Exceção:**|FE01:<ol><li>Periodo informado por Ator para visualização de informações, não possui dados coletados.</li></ol>|
|**Pós-Condição do Caso de Uso:**|Não há|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|[CSU-10](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-10.md)|
|**Regras de Negócios Relacionadas:**|Não há|
