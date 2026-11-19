# Certificados

Repositorio de certificados profissionais organizados por area de conhecimento.

O diretorio serve como acervo documental e como fonte para o site pessoal
`guicorrea93.github.io`, onde os certificados podem ser exibidos de forma
navegavel.

## Como adicionar um certificado

1. Crie uma pasta por formação (ex.: `Power Bi/`) e coloque os PDFs dentro.
   O certificado da formação inteira deve ter "Formação" no nome do arquivo
   (ex.: `Power Bi - Formação.pdf`); ele vira a capa do card.
2. Crie um `README.md` na pasta com este cabeçalho (é a fonte oficial dos textos do site):

```markdown
---
id: power-bi
titulo: Power BI
tipo: Formação
instituicao: Alura
categoria: Business Intelligence
duracao: 55 horas
ano: "2023"
destaque: false
competencias:
  - Power BI
  - DAX
---

## 📌 Descrição curta

Uma ou duas frases para o card. **Negrito** funciona.

## 📖 Descrição completa

Texto do modal do certificado.
```

3. Envie para o GitHub. O robô do site (toda segunda, ou pelo botão em
   *Actions* do repositório do site) gera miniaturas e dados e abre um pedido
   de aprovação. Sem README, a formação entra com textos provisórios marcados
   para revisão.

> **Cuidado com dados pessoais:** não suba PDF com CPF, RG ou telefone visíveis.
> O validador do site bloqueia CPF/RG/telefone no texto do PDF; PDFs
> digitalizados (imagem) precisam ser conferidos a olho.

Categorias que viram filtros no site: Business Intelligence, Power BI, Excel e
Business Intelligence, Excel e Análise de Dados, Data Science, Estatística e Data
Science, Machine Learning, Banco de Dados, Programação, Ferramentas de
Desenvolvimento, Inteligência Artificial, Metodologias Ágeis, Agilidade, Gestão
Ágil e Projetos, Governança e Gestão de TI, Processos e Governança, Soft Skills,
Liderança e Comunicação, Negociação e Comunicação, Liderança e Gestão (entre outras).

## Estrutura

Cada subpasta representa uma formacao, trilha ou tema. Dentro de cada pasta ficam
os arquivos dos certificados e, quando disponivel, um `README.md` com o resumo da
categoria.

## Categorias Mapeadas

| Categoria | Observacao |
| --- | --- |
| `Agilidade abordagens e praticas avancadas` | Agilidade e praticas avancadas. |
| `Avancando em Data Science com Python` | Trilhas de Python e Data Science. |
| `BI e Data Warehouse com SQL Server e Power BI` | BI, DW, SQL Server e Power BI. |
| `Business Agility` | Agilidade aplicada a negocios. |
| `Business Intelligence com Excel` | BI com Excel. |
| `Comunicacao` | Comunicacao profissional. |
| `Comunicacao para lideres` | Comunicacao em lideranca. |
| `Data Science` | Fundamentos e praticas de Data Science. |
| `Data Science Academy` | Cursos da Data Science Academy. |
| `Digital & Agile Thinking` | Transformacao digital e pensamento agil. |
| `Dominando o Power BI` | Power BI. |
| `Empreendedorismo Digital` | Empreendedorismo e negocios digitais. |
| `Estatistica com Python` | Estatistica aplicada com Python. |
| `Excel` | Excel e analises. |
| `Ferramentas essenciais para Devs` | Ferramentas de desenvolvimento. |
| `Gestao Agil de Projetos` | Gestao de projetos e agilidade. |
| `Governanca de TI` | Governanca e gestao de tecnologia. |
| `Lean, Governanca e Agilidade Escalada` | Lean, governanca e escala agil. |
| `Linguagem C` | Programacao em C. |
| `Machine Learning com Python - Regressao` | Regressao linear, arvores e XGBoost. |
| `Machine Learning na pratica` | Machine Learning aplicado. |
| `Microsoft SQL Server 2022` | SQL Server. |
| `Modelagem de dados` | Modelagem e bancos de dados. |
| `Modelagem e melhorias de processos de negocios` | Processos e melhoria continua. |
| `Negociacao` | Negociacao e comunicacao. |
| `Pensamento Estrategico` | Estrategia. |
| `Power Bi` | Power BI. |
| `Python para Data Science` | Python aplicado a dados. |
| `refuturiza` | Formacoes Refuturiza. |
| `SQL com MySQL Server da Oracle` | SQL e MySQL. |
| `Tableau` | Tableau e visualizacao. |
| `Times de alta performance` | Lideranca e times. |

## Manutencao

- Ao adicionar uma nova pasta, inclua um README simples dentro dela.
- Use nomes claros para os arquivos de certificado.
- Evite salvar informacoes sensiveis alem dos proprios certificados.
- Quando atualizar o portfolio, verifique se o site principal le corretamente os
  novos arquivos/metadados.

