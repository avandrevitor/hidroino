|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-04](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Coletar dados Agregados de Cluster de Estufas|
|**Objetivo:**|Obter Conjunto de dados registrados e armazenados em Cluster de Estufas|
|**Pré-Condição do Caso de Uso:**|Cluster de Estufas em modo running|
|**Ator(es):**|Timer do Sistema Central|
|**Evento inicial do Caso de Uso:**|Não há|
|**Fluxo Principal:**|<ul><li>Ator enviar pedido solicitando dados ao Sistema.</li><li>Sistema autentica Ator</li><li>Sistema reune informações solicitadas e retorna dados com resposta positiva</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|FE01:<ul><li>Autenticação do Ator falha.</li><li>Sistema realiza caso de uso 'Enviar Aviso Visual e/ou Auditivo'.</li><li>Sistema responde sinal do Ator com sinal com resposta negativa.</li></ul>|
|**Pós-Condição do Caso de Uso:**|Não há|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|[CSU-09](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/csu-09.md)|
|**Regras de Negócios Relacionadas:**|<ol><li>[**RNG-04**](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_of_business_rules.md)</li></ol>|
