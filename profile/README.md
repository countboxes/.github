![Count Boxes (1)](https://github.com/user-attachments/assets/90c4ce22-e827-4040-93a7-4429d56fb813)

O CountBoxes tem como função auxiliar na contagem de cargas durante o carregamento ou descarregamento de mercadorias.

#### Ferramentas

- [Node.js](https://nodejs.org/pt)
- [PostgreSQL](https://www.postgresql.org)
- [PrismaORM](https://www.prisma.io)
- [Yup](https://www.npmjs.com/package/yup)

#### Sobre

O CountBoxes é um aplicativo desenvolvido com JavaScript, que visa otimizar a contagem de caixas durante o processo de carregamento e descarregamento de cargas em empresas. Ele integra um scanner para registrar e atualizar em tempo real o status dos produtos em ordens de pedidos, proporcionando maior eficiência e precisão na logística. Com o CountBoxes, o processo de contagem de caixas se torna auditável e totalmente digitalizado, facilitando o controle de inventário.

#### Funcionamento

1. O gerente cria uma nova ordem de pedidos, onde pode adicionar diversos produtos que serão carregados ou descarregados.
2. Os funcionários responsáveis pelo carregamento ou descarregamento podem visualizar as ordens de pedidos disponíveis para eles.
3. Ao selecionar uma ordem de pedido específica, o funcionário pode visualizar os produtos que precisam ser manipulados.
4. O funcionário inicia o processo de escaneamento, utilizando o scanner do aplicativo para registrar os produtos que foram carregados ou descarregados. Cada escaneamento atualiza automaticamente a contagem em tempo real.

#### Funcionalidades:

1. **Escaneamento de produtos**
   - O aplicativo permite o escaneamento de códigos de barra para registrar o produto correspondente e atualizar automaticamente a contagem de itens em uma ordem de pedido.
2. **Atualização em tempo real**
   - Cada vez que um produto é escaneado, a contagem é atualizada em tempo real, facilitando o acompanhamento do processo.
3. **Divisão de contas**
   - O aplicativo divide as contas entre funcionários e gerentes. Isso permite que apenas o gerente tenha acesso a funcionalidades específicas, como a criação de ordens de pedido ou a remoção de produtos.

