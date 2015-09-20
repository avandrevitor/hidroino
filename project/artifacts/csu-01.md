|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-01](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Ativar Coleta de Dados|
|**Objetivo:**|Iniciar o registro da coleta de dados|
|**Pré-Condição do Caso de Uso:**|Arduinos devem estar no modo waiting|
|**Ator(es):**|RaspBerry PI|
|**Evento inicial do Caso de Uso:**|Ator envia sinal para inicio de caputa|
|**Fluxo Principal:**|<ul><li> Ator identifica arduino em status waiting</li><li> Ator envia sinal para arduino coletar informações</li><li> Arduino inicia algoritmo de checagem da coleta de dados</li><li> Arduino altera status waiting para running</li><li> Arduino responde sinal do Ator com sinal com resposta afirmativa</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|<ul><li> Se algoritmo de checagem da coleta de dados retornar erro</li><li> Arduino não altera status waiting para running</li><li> Arduino responde sinal do Ator com sinal com resposta negativa</li></ul>|
|**Pós-Condição do Caso de Uso:**|Arduino em status running|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|Não há|
|**Regras de Negócios Relacionadas:**|<ol><li>[**RNG-01**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li></ol>|
