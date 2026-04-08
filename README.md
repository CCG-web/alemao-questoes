# 🚀 Alemão Questões

Um simulador de questões offline, rápido e totalmente focado em produtividade para aprovação em concursos públicos. 

Este sistema permite gerenciar, responder e revisar milhares de questões diretamente no navegador, sem depender de internet, rodando tudo em um banco de dados local.

## ✨ Funcionalidades Principais

* **Banco de Dados Offline:** Usa IndexedDB para armazenar questões localmente de forma rápida e segura.
* **Modos de Treino:** Alternância entre "Modo Estudo" (mostra gabarito na hora) e "Modo Simulado" (avaliação de desempenho no final).
* **Integração em Lote:** Suporte para importar pastas inteiras de arquivos JSON de uma só vez.
* **Exportação Ninja:** Gere importações formatadas para o Anki, listas em TXT, impressões em PDF e até apresentações de PowerPoint (PPTX) com as questões.
* **Comentários em Massa:** Adicione anotações a múltiplas questões instantaneamente usando o formato "ID - Texto".
* **Backup no GitHub:** Ferramenta nativa para puxar e salvar seu banco de dados diretamente em um repositório na nuvem.

## 🛠️ Tecnologias Utilizadas

* HTML5, CSS3 e JavaScript (Vanilla)
* IndexedDB (Armazenamento local do navegador)
* PptxGenJS (Geração nativa de slides)
* html2pdf.js e FileSaver.js (Manipulação de arquivos)

## 🚀 Como Usar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` no seu navegador (Chrome, Edge, Firefox).
3. No menu lateral, clique em **Escolher arquivos** e selecione a sua pasta local contendo os arquivos `.json` com as questões.
4. O sistema vai carregar e salvar tudo no banco offline automaticamente.
5. Crie seus filtros, escolha o modo de resolução e bons estudos!
