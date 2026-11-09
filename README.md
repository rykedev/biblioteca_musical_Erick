# Sistema Musical

O **Sistema Musical** é uma interface web front-end desenvolvida em HTML5 e CSS3 para gerenciamento e navegação de acervos musicais, artistas e álbuns. O projeto conta com um design moderno, responsivo e adaptado para múltiplos dispositivos.

---

## Funcionalidades

- **Tela de Autenticação (Login):** Interface limpa para acesso ao sistema com credenciais de teste pré-configuradas.
- **Painel/Menu Principal:** Dashboard intuitivo para navegação rápida entre as seções da aplicação.
- **Gerenciamento de Artistas:**
  - Formulário para cadastro de novos artistas (nome, gênero, país de origem e foto).
  - Tabela explicativa com a listagem dos artistas cadastrados e atalhos para edição/exclusão.
- **Cadastro de Músicas:**
  - Formulário completo com suporte a vinculação por artista, título, álbum, gênero, link do YouTube, imagem de capa e letra.
  - Tabela integrada de músicas cadastradas.
- **Biblioteca Musical:**
  - Exibição de catálogo completo de faixas.
  - Filtros interativos por busca geral (título, álbum, artista), seleção por artista e gênero.
  - Acesso direto ao player de vídeo do YouTube e opções de gerenciamento.

---

## Estrutura de Arquivos

```text
.
├── index.html              # Menu principal / Dashboard
├── login.html              # Tela de login e autenticação
├── cadastro_artista.html   # Tela de cadastro e listagem de artistas
├── cadastro_musica.html    # Tela de cadastro e listagem de músicas
├── listagem_musicas.html   # Biblioteca musical com filtros de pesquisa
└── styles.css              # Folha de estilos global (CSS modularizado por aulas/sprints)
```

---

##  Layout e Estilização (`styles.css`)

A folha de estilos é centralizada em um único arquivo modularizado com as seguintes destaques:

* **Variáveis CSS (`:root`):** Facilidade de personalização de cores primárias, secundárias, estados de botões, sombras e bordas.
* **Layout Flexbox e Grid:** Utilização de `grid-template-columns` com `minmax` para adaptação automática do menu e dos formulários.
* **Design Responsivo:** Media queries otimizadas (`max-width: 768px`) para garantir boa usabilidade em smartphones e tablets.
* **Componentes Reutilizáveis:** Estilos padronizados para formulários, tabelas, botões de ação e alertas de mensagem.

---

##  Como Executar o Projeto

1. Faça o download ou clone o repositório em sua máquina local.
2. Abra o arquivo `login.html` no seu navegador de preferência.
3. Utilize as credenciais de teste exibidas na página para navegar no sistema:
   - **Usuário:** `admin`
   - **Senha:** `123`

---

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica de formulários, tabelas e layouts.
- **CSS3:** Estilização moderna utilizando CSS Variables, Flexbox, CSS Grid e Media Queries.
