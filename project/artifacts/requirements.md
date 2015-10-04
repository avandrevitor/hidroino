#Requisitos

### Funcionais

- registrar de tempo em tempo os valores capturados pelos sensores e atuadores envolvidos.

- exibir os valores capturados em forma de gráficos para acompanhamento visual dos operadores do sistema.

- emitir avisos ( warnings ) , visuais e auditivos , locais e remotamente para a equipe de operadores responsáveis por aquela estufa.

- exportar de forma cronológica, completa ou resumida os dados capturados , para realização de avaliação por um especialista / agronomo.

- fornecer api pública para acesso a dados coletados por estufas, que tenham habilitado esta api para realização de estudos por terceiros interessados.

- permitir parametrizar as configurações de controle da estuda.

- possibilitar o registro visual de evolução das plantas.

- fornecer interface visual para administração/controle do sistema de estufas.

- registrar o consumo de hardware, principalmente dos dispositivos mais sensíveis como os sensores, atuadores, arduino e raspberry para controle períodico de manutenção.

- emitir em forma de relatório os dados acumulados do consumo de hardware e periféricos.

### Não Funcionais

- Possibilitar o backup do sistema sem travamento ( deadlock ) .

- Deve-se utilizado a plataforma linux como sistema operacional.

- Deve-se utilizar como microcomputador a plataforma RaspBerry PI.

- Deve-se utilizar como microcontrolador a plataforma Arduino UNO.

- O Sistema deve conter interface responsiva, para acesso dos operadores e administradores por dispositivos moveis.

- Deve fornecer uma API para consumo livre de informações coletadas e disponibilizadas por algumas estufas.

### Postergados

- emitir relatório períodico sobre as estatísticas de economia de recursos em comparação ao sistema tradicional.
