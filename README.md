# 🧀 Pão de Queijo Mineiro Tradicional — Receita Interativa

Página HTML de uma receita tradicional mineira, construída de forma incremental como exercício de aprendizado de recursos nativos do HTML (sem JavaScript ou CSS framework). Cada commit introduz uma funcionalidade nova, evoluindo a página de uma estrutura estática para uma experiência interativa.

## 📄 Sobre o projeto

O objetivo não é só apresentar a receita, mas explorar até onde o HTML puro consegue ir em termos de interatividade — usando elementos e atributos nativos modernos em vez de recarregar em JS para tudo.

## 🧠 Aprendizados por commit

| Commit | Descrição | O que foi aprendido |
|---|---|---|
| `4c719a7` | Create README.md | Início do repositório. |
| `96ecb21` | chore: cria estrutura inicial da página | Esqueleto HTML5 básico (`<!DOCTYPE html>`, `<head>`, meta tags de charset e viewport). |
| `bc25b3f` | feat: adiciona cabeçalho da receita | Uso de `<header>` semântico com título, descrição e imagem (`<img>` com `alt` para acessibilidade). |
| `9cac0d9` | feat: adiciona dica interativa da receita | **Popover API nativa**: `popovertarget` no `<button>` associado a um `<div popover>`, permitindo mostrar/esconder conteúdo sem nenhuma linha de JavaScript. |
| `b3bf537` | feat: adiciona ingredientes e acompanhamentos | Lista semântica (`<ul>`/`<li>`) para ingredientes e uso de `<datalist>` + `<input list="...">` para criar um campo de texto com sugestões de autocomplete nativas. |
| `70b7bac` / `019a2ce` | feat: adiciona modo de preparo interativo | Uso de `<ol>` com `<input type="checkbox">` em cada item, transformando o modo de preparo em uma checklist marcável pelo usuário. |
| `5299db1` | feat: adiciona área de anotações | Atributo `contenteditable="true"` para criar uma área de texto livre editável diretamente no HTML, sem `<textarea>`. |

## 🚀 Recursos HTML nativos demonstrados

- **Popover API** (`popover`, `popovertarget`) — conteúdo mostrado/ocultado sem JS
- **Datalist** — autocomplete nativo em campos de input
- **Checkboxes em listas** — checklist interativa
- **contenteditable** — edição de conteúdo diretamente na página
- **Elementos semânticos** — `<header>`, `<section>`

## 🛠️ Como usar

Basta abrir o arquivo `.html` em qualquer navegador atualizado (Chrome, Edge ou Safari recentes) — a Popover API e o `contenteditable` não exigem servidor nem build step.
