# Sistema de Gerenciamento de Loja de Tênis

Este projeto foi desenvolvido em grupo durante as aulas de **PMI** no primeiro semestre da faculdade. O objetivo era criar um sistema para gerenciar as operações do dia a dia de uma loja de tênis. O sistema permite o cadastramento, atualização, remoção e consulta de produtos através de cinco planilhas: **Cadastro**, **Estoque**, **Vendas**, e **Pedidos**.

## Funcionalidades

### Planilha de Cadastro
- A planilha de Cadastro foi separada do Estoque e funciona como uma planilha de consulta.
- Produtos disponíveis no Estoque devem estar cadastrados na planilha de Cadastro, mas nem todos os produtos cadastrados precisam estar em estoque.

### Planilha de Estoque
- A planilha de Estoque permite o gerenciamento das quantidades de produtos, com funcionalidades automáticas para somar a quantidade de produtos pedidos pela loja e subtrair os produtos vendidos.
- Possui um sistema de alertas visuais: 
  - Linhas vermelhas indicam produtos com poucas unidades em estoque, sugerindo a necessidade de reposição.
  - Linhas verdes indicam produtos com excesso de unidades, sugerindo a criação de promoções para esses itens.

### Planilhas de Vendas e Pedidos
- As planilhas de Vendas e Pedidos registram as vendas realizadas e os pedidos feitos pela loja para reposição de estoque.
- **Em desenvolvimento**: Um recurso para gerar relatórios de vendas no Microsoft Word, com um resumo das vendas feitas até o período atual.

## Como Usar

1. **Cadastro de Produtos:** Utilize a planilha de Cadastro para adicionar novos produtos ao sistema.
2. **Gestão de Estoque:** Monitore as quantidades de produtos na planilha de Estoque, e aproveite os alertas visuais para tomar decisões rápidas.
3. **Registro de Vendas e Pedidos:** Mantenha as planilhas de Vendas e Pedidos atualizadas para garantir um controle eficiente do estoque.
4. **Geração de Relatórios**: Em breve, será possível gerar relatórios automáticos das vendas diretamente no Word. Esta funcionalidade ainda está em desenvolvimento.

## Requisitos

- Microsoft Excel (ou equivalente compatível com arquivos `.xlsx`)
- Microsoft Word (para a futura geração de relatórios)

## Contribuição

Este projeto é um trabalho acadêmico. Contribuições externas não estão sendo aceitas no momento.

## Licença

Este projeto não possui uma licença específica.

