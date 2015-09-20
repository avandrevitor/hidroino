|   	|	    |
|---	|---	|
|**Identificação do Caso de Uso:**|[CSU-02](https://github.com/avandrevitor/hidroino/blob/master/project/artifacts/table_use_of_cases.md)|
|**Nome do Caso de Uso:**|Desativar coleta de dados|
|**Objetivo:**|Finalizar o registro da coleta de dados|
|**Pré-Condição do Caso de Uso:**|Arduinos devem estar no modo running|
|**Ator(es):**|RaspBerry PI|
|**Evento inicial do Caso de Uso:**|Ator envia sinal para finalizar de caputa de dados|
|**Fluxo Principal:**|<ul><li> Ator identifica arduino em status running</li><li> Ator envia sinal para arduino parar de coletar informações</li><li> Arduino alterna de status running para waiting</li><li> Arduino responde sinal do Ator com sinal com resposta afirmativa</li></ul>| 
|**Fluxo Alternativo:**|Não há|
|**Fluxo de Exceção:**|Não há|
|**Pós-Condição do Caso de Uso:**|Arduino em status waiting|
|**Casos de Uso Incluídos:**|Não há|
|**Casos de Uso Estendidos:**|Não há|
|**Regras de Negócios Relacionadas:**|Não há|
