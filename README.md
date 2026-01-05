# Chá de Fraldas – Ana Lívia

Projeto Front-end desenvolvido para organizar e visualizar uma rifa de Chá de Fraldas de forma simples, intuitiva e responsiva.  
A aplicação foi criada com foco em fundamentos de desenvolvimento Front-end, boas práticas de organização de código e experiência do usuário.

O projeto possui uma interface pública para visualização dos dados e uma interface administrativa para gerenciamento das informações.

---

## Visão Geral

- Interface pública em modo somente leitura
- Interface administrativa para cadastro, edição e remoção de registros
- Design mobile-first, priorizando a experiência em dispositivos móveis
- Layout centralizado que simula uma tela de celular mesmo no desktop
- Interface simples, clara e funcional

---

## Tecnologias Utilizadas

- HTML5
- CSS3
  - Flexbox
  - Grid Layout
  - Media Queries
  - Mobile-first
- JavaScript Vanilla (ES6+)
- JSON como fonte de dados
- GitHub Pages para hospedagem

---

## Estrutura do Projeto

/
├── index.html # Interface pública (somente leitura)
├── admin.html # Painel administrativo
├── dados.json # Base de dados dos números
└── README.md


---

## Funcionalidades

### Interface Pública (index.html)

- Exibição dos números de 1 a 100
- Destaque visual para números disponíveis e ocupados
- Exibição de informações ao passar o mouse ou tocar no número
- Layout responsivo para celular, tablet e desktop

### Interface Administrativa (admin.html)

- Leitura dos dados diretamente do arquivo `dados.json`
- Funcionalidades de:
  - Cadastro
  - Edição
  - Remoção de registros
- Destaque visual para números já preenchidos
- Geração do JSON atualizado para versionamento manual

**Observação:**  
Por estar hospedado no GitHub Pages, não é possível salvar alterações diretamente no arquivo `dados.json`.  
As alterações feitas no painel administrativo são realizadas em memória e o JSON gerado pode ser copiado e atualizado manualmente no repositório.

---

## Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

- Praticar HTML, CSS e JavaScript puro
- Trabalhar com consumo de dados via `fetch`
- Desenvolver interfaces responsivas
- Aplicar conceitos básicos de experiência do usuário
- Simular um fluxo real de manutenção de dados em aplicações Front-end

---

## Conceitos e Aprendizados

- Manipulação do DOM
- Consumo de arquivos JSON
- Organização de código Front-end
- Separação de responsabilidades entre visualização e administração
- Responsividade e adaptação para diferentes tamanhos de tela
- Limitações e soluções em ambientes estáticos

---

## Melhorias Planejadas

- Implementação de back-end com Node.js e Express
- Persistência dos dados em banco de dados
- Salvamento direto das alterações feitas no painel administrativo
- Autenticação para acesso ao painel administrativo
- Criação de uma API REST
- Filtros por categoria e melhorias de usabilidade

---

## Autor

Desenvolvido por **Caio Alves**  
Projeto Front-end com foco em aprendizado, prática e fundamentos.
