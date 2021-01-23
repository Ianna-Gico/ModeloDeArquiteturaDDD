**MODELO DE ARQUITETURA DDD**

**Camada Interface do Usuário**

Exibição de informações do sistema ao usuário + comandos do usuário.

Ex.: sistema para cadastro de produtos alimentícios.

**Camada de Aplicação**

Conecta a interface do usuário às camadas inferiores.

Ex.: ASP.NET Core + Visual Studio

**Camada de Domínio**

Conceitos, regras e lógica de negócios.

Ex.: compra e venda de produtos alimentícios.

**Camada de Infra-estrutura** 

Recursos técnicos para suporte das outras camadas.

Ex.: conexão com um banco de dados.



**A organização das pastas seriam feitas seguindo o modelo de inversão de dependência, onde todas as camadas dependem da Camada de Domínio. Para isso, interfaces são criadas e classes são atreladas a elas. Todas as interfaces devem ficar no Domínio e usa-se o “crossCutting” para a injeção de dependências.**