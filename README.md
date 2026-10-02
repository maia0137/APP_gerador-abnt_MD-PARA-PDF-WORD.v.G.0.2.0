# 📄 ABNT Express

Um gerador de relatórios acadêmicos *Single-File* (arquivo único) que converte Markdown para o rigoroso padrão ABNT. Leve, sem dependências pesadas de backend e totalmente funcional offline.

O ABNT Express foi pensado para quem precisa focar na escrita e na análise de dados — seja estruturando um inventário florestal, um diário de campo ou um trabalho universitário — sem perder horas brigando com a formatação de processadores de texto convencionais.

## ✨ Funcionalidades

* **Conversão em Tempo Real:** Escreva em Markdown e visualize a formatação ABNT (recuos de 1.5cm, fontes, espaçamentos) imediatamente.
* **100% Offline e Arquivo Único:** Todo o sistema de interface, lógicas de conversão e estilização vivem em um único arquivo `.html`. Basta baixar e abrir no navegador.
* **Tabelas e Figuras ABNT:** Inserção facilitada de tabelas com formatação aberta nas laterais e suporte a imagens convertidas em Base64 para não quebrar referências externas.
* **Notas de Rodapé Automáticas:** Sistema customizado via Regex que organiza e numera notas de rodapé no final do documento.
* **Paginação Inteligente:** Suporte nativo a contagem de páginas pré-textuais e numeração visível a partir da introdução (via CSS *Counters*).
* **Exportação:** Geração de PDF nativa do navegador com preservação de margens (3cm/2cm).

## 🚀 Como usar

Como o projeto é *Single-File*, não há necessidade de `npm install` ou servidores locais.

1. Faça o download ou clone este repositório.
2. Dê um duplo clique no arquivo `index.html` (ou `ABNT-Express.html`).
3. O aplicativo abrirá no seu navegador padrão.
4. Escreva seu texto na área de edição utilizando a sintaxe Markdown.
5. Clique em **Gerar PDF / Exportar ABNT** na barra inferior.

## 🛠️ Tecnologias Utilizadas

* **Vanilla JavaScript** (Sem frameworks complexos, focado em performance)
* **HTML5 / CSS3** (Utilização avançada de `@page` e paginação via CSS)
* **[Marked.js](https://marked.js.org/)** - Para o parsing seguro de Markdown.
* **[DOMPurify](https://github.com/cure53/DOMPurify)** - Para sanitização do HTML gerado.

## 👨‍💻 Autor

Criado e mantido por **Evandro Maia Neves**. 

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes. Você é livre para usar, modificar e distribuir.
