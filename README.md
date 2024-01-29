
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# ClickClub

### Problemática
A experiência educacional contemporânea enfrenta desafios significativos relacionados à comunicação e interação entre os alunos. A falta de uma plataforma centralizada e dedicada para facilitar a conexão e colaboração entre estudantes pode resultar em diversas questões, como: 

Desconexão Social: Muitos alunos, especialmente em ambientes de ensino remoto, podem sentir uma falta de conexão social. A ausência de interações informais e oportunidades para conhecer colegas com interesses semelhantes pode prejudicar o senso de comunidade;

Dificuldade na Formação de Grupos de Estudo: A formação de grupos de estudo pode ser um desafio, especialmente quando os alunos não têm uma plataforma específica para encontrar colegas com interesses acadêmicos comuns. Isso pode afetar negativamente a qualidade da colaboração e do aprendizado em grupo;

Comunicação Descentralizada: As ferramentas de comunicação existentes muitas vezes não são adaptadas para as necessidades específicas dos estudantes. A dispersão de informações em diferentes canais pode levar à perda de mensagens importantes e à dificuldade de acompanhar as atividades e notícias relevantes;

Falta de Envolvimento em Atividades Estudantis: Alunos podem se sentir desconectados das atividades extracurriculares e dos clubes existentes devido à falta de uma plataforma unificada que os incentive a participar e contribuir para a vida estudantil.

### Solução proposta:
O ClickClub visa resolver essas questões proporcionando uma solução abrangente que unifica a comunicação, facilita a formação de grupos de estudo, promove a colaboração em clubes e mantém os alunos informados sobre notícias relevantes. Ao fornecer uma plataforma centralizada e amigável, o projeto visa criar uma experiência mais integrada, atendendo às necessidades sociais e acadêmicas dos estudantes. A implementação do ClickClub busca, assim, fortalecer a coesão da comunidade estudantil, melhorando significativamente a qualidade da interação e colaboração entre os alunos.
## Funcionalidades
### Requisitos funcionais
- Temas dark e light
- CRUD de grupos:
    - Criação de Grupo: POST /grupos
    - Leitura de Grupos: GET /grupos
    - Atualização de Grupo: PUT /grupos/:id
    - Exclusão de Grupo: DELETE /grupos/:id
- CRUD de publicações:
    
    - Criação de Post: POST /posts -- APENAS OS LIDERES DOS GRUPOS;
    - Leitura de Posts: GET /posts,;
    - Atualização de Post: PUT /posts/:id;
    - Exclusão de Post: DELETE /posts/:id.

- CRUD de conta:
    - Criação de Conta: POST /contas
    - Leitura de Contas: GET /contas
    - Atualização de Conta: PUT /contas/:id
    - Exclusão de Conta: DELETE /contas/:id

- 

### Requisitos não funcionais

- Compatibilidade;
- Usabilidade;
- Manutenibilidade;
- Desempenho.
## Rodando localmente

Clone o projeto

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run start
```
    
