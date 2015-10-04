|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-07](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Desativar Cluster de Estufas|
|**Objetivo:**|Cluster de Estufa em modo stopped|
|**Pré-Condição do Caso de Uso:**|Cluster de Estufas em modo running|
|**Ator(es):**|Administrador|
|**Evento inicial do Caso de Uso:**|Ator inicia desligamento em Cluster de Estufas|
|**Fluxo Principal:**|<ul><li>Sistema realiza algoritmo de checagem de comunicação com estufas</li><li>Sistema executa caso de uso: 'Desativar Coleta de Dados' para cada estufa conectada plugada.</li><li>Sistema realiza algoritmo de checagem de comunicação com sistema central</li><li>Sistema informa ao processo de desativação ao Sisteam Central</li><li>Sistema responde Ator com resposta afirmativa</li><li>Sistema realiza operação de `shutdown`</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|<ul><li>FE01:<ol><li>Algoritmo de checagem da checagem de comunicação com estufas retorna erro.</li><li>Sistema não altera status para running.</li><li>Sistema realiza caso de uso 'Enviar Aviso Visual e/ou Auditivo'.</li><li>Sistema responde sinal do Ator com sinal com resposta negativa.</li></ol></li><li>FE02:<ol><li>Algoritmo de checagem da checagem de comunicação com Sistema Central retorna erro</li><li>Sistema não altera status para running.</li><li>Sistema realiza caso de uso 'Enviar Aviso Visual e/ou Auditivo'.</li><li>Sistema responde sinal do Ator com sinal com resposta negativa.</li></ol></li></ul>|
|**Pós-Condição do Caso de Uso:**|Cluster de Estufa em modo stopped|
|**Casos de Uso Incluídos:**|[**CSU-08**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-08.md)|
|**Casos de Uso Estendidos:**|[CSU-09](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-09.md)|
|**Regras de Negócios Relacionadas:**|<ol><li>[**RNG-02**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li><li>[**RNG-03**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li></ol>|
