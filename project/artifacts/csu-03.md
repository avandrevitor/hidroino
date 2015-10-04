|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-03](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Ativar Cluster de Estufas|
|**Objetivo:**|Cluster de Estufa em modo running|
|**Pré-Condição do Caso de Uso:**|Não há|
|**Ator(es):**|Administrador|
|**Evento inicial do Caso de Uso:**|Ator inicia started em Cluster de Estufas|
|**Fluxo Principal:**|<ul><li>Sistema realiza algoritmo de checagem de comunicação com estufas</li><li>Sistema realiza algoritmo de checagem de comunicação com sistema central</li><li>Sistema responde Ator com resposta afirmativa</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|<ul><li>FE01:<ol><li> Algoritmo de checagem da checagem de comunicação com estufas retorna erro</li><li> Sistema não altera status para running</li><li> Sistema responde sinal do Ator com sinal com resposta negativa</li></ol></li><li>FE02:<ol><li> Algoritmo de checagem da checagem de comunicação com Sistema Central retorna erro</li><li> Sistema não altera status para running</li><li> Sistema responde sinal do Ator com sinal com resposta negativa</li></ol></li></ul>|
|**Pós-Condição do Caso de Uso:**|Cluster de Estufa em modo running|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|Não há|
|**Regras de Negócios Relacionadas:**|<ol><li>[**RNG-02**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li><li>[**RNG-03**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li></ol>|
