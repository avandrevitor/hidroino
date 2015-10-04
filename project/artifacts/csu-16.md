|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-16](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Visualizar relátorio do consumo de hardware|
|**Objetivo:**|Apresentar informações sobre o consudo de hardware do Sistema|
|**Pré-Condição do Caso de Uso:**|Não há|
|**Ator(es):**|Operador|
|**Evento inicial do Caso de Uso:**|Não há|
|**Fluxo Principal:**|<ul><li>Ator informa periodo que deseja visualiar informações.</li><li>Sistema verifica validade dos dados coletados.</li><li>Sistema reune informações e apresenta relatório de consumo.</li></ul>| 
|**Fluxo Alternativo:**|<ul><li>Sistema verifica validade dos dados coletados.</li><li>Sistema inicia nova coleta de dados, realizando caso de uso: '*Exportar Dados Capturados do Consumo de Hardware*'.</li><li>Sistema reune informações e apresenta relatório de consumo.</li></ul>|
|**Fluxo de Exceção:**|FE01:<ol><li>Periodo informado por Ator para visualização de informações, não possui dados coletados.</li></ol>|
|**Pós-Condição do Caso de Uso:**|Não há|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|[CSU-11](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-11.md)|
|**Regras de Negócios Relacionadas:**|Não há|
