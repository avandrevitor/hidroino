## Quadro Descritivo de Regras de Negócio

|Identificação|Descrição|
|---	|---	|
|RNG-01|No algoritmo de checagem da coleta de dados considera-se que o circuíto esta com erro, se qualquer um dos sensores ou atuadores conectados não responder dentro de um periodo hábil.|
|RNG-02|No algoritmo de checagem de comunicação com estufas considera-se que o circuíto esta com erro, se Cluster não conseguir ler sinal da Estufa registrada para o mesmo,dentro de um periodo hábil.|
|RNG-03|No algoritmo de checagem de comunicação com Sistema Central considera-se que o circuíto esta com erro, se Cluster não conseguir ler enviar sinal para o Sistema Central,dentro de um periodo hábil.|
|RNG-04|Sistema deve utilizar processo de autenticação por token, utilizando o protocolo ssh com par de chave pública para válidar acesso ao sistema. Caso ocorra falha na autenticação de algum usuário no sistema, o mesmo deve emitir alertas visuais e/ou auditivos para operadores do sistema. Desta regra visa proteger autenticação de usuário não autorizado o que poderia comprometer informações transmitidas no sistema.|
|   	|   	|
