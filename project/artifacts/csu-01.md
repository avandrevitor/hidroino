|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-01](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Ativar Coleta de Dados|
|**Objetivo:**|Iniciar o registro da coleta de dados|
|**Pré-Condição do Caso de Uso:**|Estufa devem estar no modo waiting|
|**Ator(es):**|Sitema Cluster de Estufas|
|**Evento inicial do Caso de Uso:**|Ator envia sinal para inicio de captura|
|**Fluxo Principal:**|<ul><li> Ator identifica Estufa em status waiting</li><li> Ator envia sinal para Estufa coletar informações</li><li> Estufa inicia algoritmo de checagem da coleta de dados</li><li> Estufa altera status waiting para running</li><li> Estufa responde sinal do Ator com sinal com resposta afirmativa</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|<ul><li> Algoritmo de checagem da coleta de dados retornar erro</li><li> Estufa não altera status waiting para running</li><li> Estufa responde sinal do Ator com sinal com resposta negativa</li></ul>|
|**Pós-Condição do Caso de Uso:**|Estufa em status running|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|Não há|
|**Regras de Negócios Relacionadas:**|<ol><li>[**RNG-01**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li></ol>|
