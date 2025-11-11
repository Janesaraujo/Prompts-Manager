# Prompt Manager

Gerenciador de prompts desenvolvido como uma aplicação web moderna e responsiva. Ideal para quem trabalha com modelos de linguagem e precisa organizar, buscar e utilizar comandos de IA com rapidez.

![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Status: Frontend Only](https://img.shields.io/badge/status-frontend--only-green.svg)
![Tech: HTML/CSS/JS](https://img.shields.io/badge/tech-HTML%2FCSS%2FJS-orange.svg)

## Visão Geral

O Prompt Manager oferece:

- Organização centralizada em uma barra lateral (`.sidebar`)
- Busca rápida por título (`#search-input`)
- Edição direta com campos `contenteditable`
- Botões para salvar (`#btn-save`) e copiar (`#btn-copy`)
- Design responsivo com layout Off-Canvas em mobile

## Tecnologias Utilizadas

- **HTML5 semântico** (`header`, `aside`, `main`)
- **CSS com variáveis e Flexbox**
- **JavaScript** para lógica de interface (`script.js`)
- **Media Queries** para responsividade

## Design e Desenvolvimento

- Interface baseada em [design da Rocketseat no Figma](https://www.figma.com/community/file/1554529095872857492)
- Codificação assistida por GitHub Copilot no VSCode
- Integração com MCP Server para conversão de design em código

## Como Rodar o Projeto

Pré-requisitos: navegador moderno

```bash
git clone https://github.com/Janesaraujo/Prompts-Manager
cd Prompts-Manager
```

Abra o arquivo `index.html` no navegador ou use o Live Server no VSCode para rodar localmente.

Versão online: [janesaraujo.github.io/Prompts-Manager](https://janesaraujo.github.io/Prompts-Manager/)

## Contribuição

Contribuições são bem-vindas! Para colaborar:

1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'Nova funcionalidade'`
4. Push para sua branch: `git push origin minha-feature`
5. Abra um Pull Request

## Roadmap

- [x] Interface responsiva
- [x] Busca por título
- [x] Edição inline com `contenteditable`
- [ ] Suporte a tags nos prompts
- [ ] Exportação de prompts em JSON
- [ ] Modo escuro

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
