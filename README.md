🛰️ Gerador de Proposta Comercial - Engesat

Link: https://felipeam96.github.io/Gerador-de-Propostas/

Um gerador de propostas comerciais automatizado, interativo e focado na experiência do usuário (UX). Desenvolvido para agilizar a criação de orçamentos complexos envolvendo imagens de satélite e modelos de elevação (Altimetria), exportando o resultado em .docx (Microsoft Word) ou copiando diretamente para a área de transferência com o formato preservado.

✨ Funcionalidades

Geração Automática de Documentos: Transforma inputs de formulário em um documento HTML formatado e pronto para exportação.

Exportação para MS Word: Utiliza html-docx-js para gerar arquivos .docx mantendo imagens, tabelas e estilos (compatível com MS Word e Outlook).

Gestão Dinâmica de Áreas: Permite adicionar ou remover múltiplas "Áreas de Interesse" dinamicamente.

Múltiplas Alternativas por Área: Para cada área, é possível adicionar várias opções de satélites, datas e custos.

Upload de Imagens via "Ctrl+V": Uma área de Paste Zone inteligente permite que o usuário simplesmente copie e cole imagens (Quick Looks) da área de transferência direto na proposta, sem precisar fazer upload de arquivos.

Legendas Inteligentes: Concatenação automática da legenda das imagens com base nos inputs (Área - Satélite - Data - Resolução), preservando edições manuais do usuário.

Cálculo e Resumo Financeiro: Gera automaticamente uma tabela de resumo de custos no final da proposta.

Notificações Toast: Feedback visual moderno sem o uso de alert() intrusivos.

Design Responsivo e Moderno: Interface de usuário construída com Tailwind CSS.

🚀 Tecnologias Utilizadas

Este projeto é Serverless e roda inteiramente no navegador do cliente, sem necessidade de backend.

HTML5 & CSS3

JavaScript (ES6+) - Vanilla JS puro, sem frameworks pesados.

Tailwind CSS - Via CDN para estilização rápida e responsiva.

html-docx-js - Biblioteca para converter o DOM HTML em arquivos Word compatíveis.

FileSaver.js - Para salvar os arquivos gerados no computador do usuário.

🛠️ Como executar o projeto localmente

Como o projeto utiliza tecnologias puramente Front-end (HTML, CSS e JS), não há processos complexos de build ou instalação de dependências (Node.js/NPM não são necessários).


📖 Como Usar a Aplicação

Dados Gerais: Preencha os dados do cliente, data, nome do projeto e comentários adicionais. Note que o nome do arquivo Word será preenchido automaticamente com o nome do cliente.

Áreas e Satélites: Adicione as áreas de interesse. Cole (Ctrl+V) a imagem de referência do polígono e preencha as opções de satélite.

Catálogo Global: Escolha quais satélites de referência aparecerão na seção de Especificações Técnicas. Se "Altimetria" for selecionada, o sistema abrirá campos extras de custos altimétricos globais.

Geração: Clique em "Construir Proposta Visual". A coluna da direita será preenchida com a visualização do documento em tempo real.

Exportação: * Clique em "Baixar Documento Word" para gerar o arquivo .docx.

Clique em "Copiar para Colar no Email" para copiar a proposta e colar no corpo de um e-mail (ex: Outlook) ou Google Docs, mantendo as imagens e formatações.




Este projeto foi desenvolvido para fins operacionais específicos.

Desenvolvido com 💡 e JavaScript.

Felipe AM - Engesat
