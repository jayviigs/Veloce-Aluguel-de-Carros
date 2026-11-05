# Modelos do sistema Veloce

Os diagramas de casos de uso, classes, pacotes e componentes e as histórias de usuário estão documentados em [`../README.md`](../README.md), na seção **Arquitetura e modelagem**. Este arquivo pode ser usado como índice de modelagem durante a revisão acadêmica.

## Regras representadas

- Somente clientes cadastrados criam pedidos.
- Cada cliente declara de uma a três fontes de renda; o protótipo permite editar renda principal e mantém rendas adicionais existentes.
- Um pedido pertence a um cliente e referencia um automóvel; um agente pode avaliá-lo e registrar nota de 1 a 5, parecer e status.
- A estimativa de aluguel é a diária multiplicada pela quantidade de dias do período.
- Os dados de clientes, rendas, automóveis, agentes e pedidos são persistidos nas coleções do JSON Server.
