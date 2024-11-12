# REPO03
 
Não consegui fazer o código funcionar

### Perguntas para Entrevista

1. **Qual a vantagem de usar o Prisma com NestJS em comparação a outros ORMs?**  
R: O Prisma oferece uma integração fácil com NestJS, fornecendo um cliente altamente eficiente para acessar o banco de dados. Ele também facilita o gerenciamento de migrações, validações de tipos e é mais rápido que outros ORMs, como Sequelize, devido à sua arquitetura otimizada.

2. **Como o NestJS facilita a separação de responsabilidades no desenvolvimento de APIs?**  
R: O NestJS utiliza um padrão modular, onde cada parte do aplicativo (como controladores, serviços e módulos) é separada em unidades distintas, facilitando a organização e manutenção do código.

3. **Explique como funciona o ciclo de vida do Prisma dentro do NestJS.**  
R: O Prisma é integrado ao NestJS por meio do PrismaService, que é responsável por gerenciar a conexão com o banco de dados. No ciclo de vida do NestJS, o Prisma é conectado ao banco de dados quando o módulo é inicializado (onModuleInit) e desconectado quando o módulo é destruído (onModuleDestroy).

4. **Quais são os principais benefícios do uso de SQLite para este projeto?**  
R: O SQLite é fácil de configurar, leve e ideal para desenvolvimento local e protótipos. Ele não requer configuração de servidor e pode ser uma boa opção para projetos de pequeno porte ou para testes.

5. **Qual a importância das validações no `UsersService` e onde você adicionaria essas validações?**  
R: As validações garantem que os dados fornecidos são corretos antes de interagir com o banco de dados, prevenindo erros e dados inconsistentes. As validações podem ser adicionadas no UsersService, especialmente nas funções de create e update, verificando, por exemplo, se o email é válido ou se o nome está presente.

6. **Como o NestJS implementa injeção de dependência e quais as vantagens disso?**  
R: O NestJS usa injeção de dependência para fornecer as dependências (como serviços) diretamente aos componentes que delas precisam, como controladores e outros serviços. Isso facilita o gerenciamento de dependências, promove a reutilização de código e torna o sistema mais flexível e testável.
