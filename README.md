# Sistema de Gestão de Pedidos - Loja Online

Aplicação web desenvolvida como requisito da disciplina de Teste de Software (N1 AT2) do curso de Ciências da Computação da Universidade Católica de Brasília (UCB). O foco do projeto é a implementação e validação rigorosa de regras de negócio de um e-commerce.

## Funcionalidades

* Cadastro, edição e exclusão de produtos.
* Listagem e busca de produtos por ID.
* Operações de carrinho de compras, cálculo do subtotal e aplicação de cupons de desconto.
* Cálculo de frete e fechamento de pedido.

## Regras de Negócio Validadas

* Bloqueio de preço negativo e estoque negativo.
* Impedimento de adicionar produto sem estoque ao carrinho.
* Bloqueio de fechamento de pedido com carrinho vazio.
* Validação de cupons e aplicação de frete grátis conforme o valor da compra.

## Tecnologias Utilizadas

* **Linguagem Principal:** JavaScript.
* **Interface:** HTML e CSS.
* **Testes Automatizados:** Jest.
* **Ambiente:** Node.js.

## Testes e Qualidade

A estratégia adotada consistiu na realização de testes unitários automatizados utilizando a biblioteca Jest, organizados por módulos. 

* **Total de Casos de Teste:** 51 executados e 51 aprovados.
* **Taxa de Falhas:** 0%.
* **Cobertura de Código (Coverage):** 100% de cobertura alcançada nas instruções (Statements), decisões (Branches), funções (Functions) e linhas executadas (Lines).

## Como Executar o Projeto
1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>

2. **Acesse a pasta do projeto e instale as dependências:**
   ```bash
   nmp install
3. **Execute a interface gráfica:**
   ```bash
   Abra o arquivo index.html diretamente em qualquer navegador web.
4. **Execute os testes automatizados:**
   ```bash
   npm test ou npx jest --coverage

