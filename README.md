# 📊 Organizador de Declaração de Imposto de Renda (IRPF) em Excel

Projeto desenvolvido como desafio da trilha da **DIO (Digital Innovation One)**, com o objetivo de aplicar na prática os conceitos de Excel abordados nas aulas, criando uma ferramenta funcional para organizar as informações necessárias na declaração de Imposto de Renda de Pessoa Física.

## 🎯 Sobre o desafio

O desafio propõe a criação de um agregador de dados no Excel que ajude o usuário a reunir e controlar, de forma organizada e validada, as informações essenciais para a declaração do IR — utilizando recursos como menus de navegação, validação automática de dados e funcionalidades extras (como links rápidos), tudo dentro do próprio Excel.

## 🗂️ Estrutura da planilha

O arquivo [`INFORME.xlsx`](./INFORME.xlsx) é dividido em 4 abas:

| Aba | Conteúdo |
| --- | --- |
| **TÍTULAR** | Dados pessoais do declarante: nome, CPF, data de nascimento, título de eleitor, cônjuge, endereço, CEP, telefone, celular e e-mail (com link `mailto` já configurado). Inclui também campos de SIM/NÃO (via lista suspensa) para alterações na entrega anterior, dependente cônjuge e residência no exterior. |
| **INFORMES** | Rendimentos bancários informados por banco (nome do banco, valor atual e anexo do comprovante em PDF), com soma automática do total via fórmula (`=SOMA(...)`). |
| **NOTAS** | Lançamento mês a mês das entradas de receita, com data, categoria (lista suspensa: HOLERITE, CNPJ ou FREELANCE) e valor. |
| **TABELAS** | Lista de referência com os códigos e nomes de bancos brasileiros, usada para padronizar o preenchimento das outras abas. |

## ⚙️ Recursos do Excel utilizados

- **Validação de dados** (listas suspensas) para padronizar respostas (SIM/NÃO, categorias de receita);
- **Fórmulas de soma automática** para totalizar os valores informados;
- **Hyperlink** de e-mail para contato rápido direto na planilha;
- **Abas organizadas por tema**, funcionando como um menu de navegação do processo de declaração.

## 🚀 Como usar

1. Baixe o arquivo [`INFORME.xlsx`](./INFORME.xlsx);
2. Preencha a aba **TÍTULAR** com os dados pessoais;
3. Registre os rendimentos bancários na aba **INFORMES**;
4. Lance as receitas mês a mês na aba **NOTAS**;
5. Use a aba **TABELAS** como apoio para consulta dos códigos de banco.

## 🛠️ Tecnologias

- Microsoft Excel

## 📸 Imagens

Capturas de tela do preenchimento podem ser adicionadas na pasta [`/images`](./images).

## ✍️ Autora

Projeto desenvolvido durante os estudos na trilha de Excel da [DIO](https://www.dio.me/).
