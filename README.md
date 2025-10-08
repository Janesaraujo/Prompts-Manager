Prompt Manager 
Um gerenciador de prompts desenvolvido como uma aplicação web moderna e responsiva, projetado para facilitar a organização, busca e utilização de seus comandos e instruções de IA. Este projeto foi concebido para ser uma ferramenta rápida e intuitiva para quem trabalha com modelos de linguagem e precisa de acesso imediato aos seus prompts mais utilizados.

 **Visão Geral e Funcionalidades**
O Prompt Manager oferece uma interface limpa e intuitiva, inspirada em padrões modernos de aplicativos de produtividade, para:

Organização Centralizada: Gerencie e visualize sua lista de prompts em uma barra lateral dedicada **(.sidebar)**.

Busca Rápida: Utilize o campo de busca por título **(#search-input)** para filtrar e encontrar prompts instantaneamente.

Edição Direta: A interface principal permite editar o título **(#prompt-title)** e o conteúdo **(#prompt-content)** diretamente na página, graças ao atributo **contenteditable="true"**.

Ações Essenciais: Botões claros para Salvar **(#btn-save)** o prompt e Copiar **(#btn-copy)** seu conteúdo para a área de transferência com um clique.

Design Responsivo: A barra lateral é colapsável, otimizando o espaço em telas desktop, e adota o padrão **Off-Canvas** em mobile para uma excelente usabilidade em qualquer dispositivo.

**Análise Técnica (Stack & Estrutura)**
O projeto é uma aplicação Frontend Pura, focada em performance e usabilidade, construída com as seguintes tecnologias e técnicas:

**Estrutura (HTML)**
HTML5 Semântico: Uso de tags como **header**, **aside** e **main** para estruturar a aplicação de forma lógica e acessível.

**Interatividade via JS**: A lógica da aplicação, como a gestão da lista **(#prompt-list)**, e o comportamento dos botões de menu **(#btn-open, #btn-collapse)** são controlados por um arquivo JavaScript externo **(script.js)**.

**UX com contenteditable**: Os campos de título e conteúdo utilizam o atributo **contenteditable="true"** para edição direta, e **data-placeholder** junto com classes de estado **(.is-empty)** para exibir o texto de sugestão **(placeholder)**.

**Estilização (CSS)**
O design foi arquitetado para ser consistente e manutenível:

Variáveis CSS **(:root)**: Uso de **Custom Properties** para definir um Sistema de Design centralizado, controlando paleta de cores **(destaque: --accent-600, base: --gray-*)** e tipografia. Isso facilita a rápida personalização do tema.

**Layout Moderno**: O layout é primariamente baseado em **Flexbox (display: flex)** para o posicionamento dinâmico dos componentes principais **(.app, .sidebar, .main)**.

**Componentização de UI**: Padrões claros para botões **(.btn-primary, .btn-outline)** e estados de hover com transições suaves **(transition: 0.5s)**.

**Media Queries**: O projeto utiliza uma **media query em $$(max-width: 950px)$$** para implementar um design responsivo completo, transformando a barra lateral em um menu lateral **(Off-Canvas) para dispositivos móveis**.

**Desenvolvimento e Ferramentas**
Este projeto demonstra a capacidade de integrar fluxos de trabalho de design e desenvolvimento com o auxílio de Inteligência Artificial:

**Design Base**: O layout e a interface foram baseados em um projeto de design original da Rocketseat no Figma.
**https://www.figma.com/community/file/1554529095872857492**

**Aceleração com IA**: O processo de codificação da estrutura inicial foi fortemente auxiliado pelo GitHub Copilot no Visual Studio Code (VSCode).

**Integração Figma**: Foi utilizado o **MCP Server (Multi-Cursor Platform/Figma Server)** para permitir que o Copilot acessasse o contexto do design do Figma, traduzindo elementos visuais diretamente em código HTML/CSS, otimizando a fase de Design-to-Code.

**Como Rodar o Projeto**
Como o Prompt Manager é uma aplicação Frontend pura (HTML, CSS, JS), você não precisa de backend ou dependências complexas para executá-lo.

**Pré-requisitos**
Um navegador web moderno (Chrome, Firefox, Edge, etc.).

**Instruções**
Clone o Repositório:

Bash

git clone **https://github.com/Janesaraujo/Prompts-Manager**
cd prompt-manager
Abra no Navegador:

Localize o arquivo index.html dentro da pasta clonada.

Dê um duplo clique no arquivo, ou clique com o botão direito e selecione "Abrir com..." (seu navegador preferido).

**O Prompt Manager está hospedado no GitHub Pages e pode ser acessado publicamente**:

**https://janesaraujo.github.io/Prompts-Manager/**

**Alternativa (Recomendado para Devs)**:

Se você tiver o VSCode, instale a extensão Live Server.

Abra o projeto no VSCode e clique em "Go Live" no canto inferior direito para rodar o projeto em um servidor local com hot reload.

O projeto estará acessível em seu navegador, pronto para ser usado!
