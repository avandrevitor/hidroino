## Arquitetura Geral

![arquitetura geral](https://github.com/avandrevitor/hidroino/blob/master/project/images/arquitetural_geral.jpg)

### Proposta

Hidroino tem como objetivo ser uma plataforma aberta, livre e colaborativa. Definimos uma arquitetura inicial que segue as seguintes nomeclaturas:

- **Estufa**: Composição feita com Estufa Hidroponia, Arduino Uno, Sensores e Atuadores.
- **Cluster de Estufas**: Composição feita pelo Raspberry Pi e circuitos para comunicação com a *Estufa*.
- **Sistema Central**: Servidor Linux que recebe requisições dos *Operadores* e realiza comunicação, processamento e armazenamento das informações entre toda estrutura. É a partir dele que os Clusters de Estufas são gerenciados remotamente.
