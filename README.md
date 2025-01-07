# Emissão de NFS-e

https://github.com/user-attachments/assets/84168a2e-8ae8-4124-95f7-9625d5b04dc7

## Descrição

A aplicação de **Emissão de NFS-e** foi desenvolvida para facilitar o processo de geração de Notas Fiscais de Serviço Eletrônica (NFS-e). Ela permite que o usuário insira o valor da venda, a descrição dos itens vendidos e as porcentagens dos impostos (IRPF, PIS, COFINS, INSS, ISSQN). Com esses dados, a aplicação calcula os impostos e exibe os valores detalhados da nota fiscal, incluindo o valor líquido após os descontos dos impostos.

## Funcionalidades

- **Inserção de Dados**: O usuário pode inserir o valor da venda, a descrição dos itens vendidos e as porcentagens de impostos.
- **Cálculo Automático de Impostos**: A aplicação calcula os impostos automaticamente com base nas porcentagens fornecidas.
- **Exibição de Resultados**: Exibe a Nota Fiscal Gerada com os detalhes de cada imposto, o total de impostos e o valor líquido.
- **Interface Responsiva**: A interface foi construída utilizando o **Bootstrap**, tornando-a responsiva e acessível em diferentes dispositivos.

## Tecnologias Utilizadas

- **HTML5** e **CSS3**: Para estruturação e estilização da interface.
- **Bootstrap 5**: Framework CSS para estilização e layout responsivo.
- **JavaScript**: Para manipulação de eventos e cálculos dinâmicos.
- **Fontes Google**: Uso da fonte **Roboto** para uma melhor legibilidade.

## Como Rodar

### Requisitos

Não há necessidade de backend para rodar este projeto, pois ele é uma aplicação frontend simples. O único requisito é um navegador moderno.

### Passos para Execução

1. **Clone o repositório** (se você estiver utilizando um repositório Git):

   ```bash
   git clone https://github.com/andressarodrigues2172dev/emissao-nfse.git

2. **Abra o arquivo HTML:**

Navegue até o diretório onde o arquivo index.html está localizado e abra-o em seu navegador preferido.

3. **A aplicação será carregada e estará pronta para uso.**

## Como funiona 

1.**Preenchimento dos Campos:** O usuário preenche os campos de valor da venda, itens vendidos e as porcentagens de impostos (IRPF, PIS, COFINS, INSS, ISSQN).

2.**Cálculo de Impostos:** Ao clicar no botão "Calcular Impostos", a aplicação realiza os cálculos e exibe os resultados em uma tabela.

3.**Exibição dos Resultados:** A tabela mostra a descrição de cada imposto, o valor calculado para cada um, o total de impostos e o valor líquido da venda.

## Exemplo de Uso

| Descrição            | Valor (R$)     |
|----------------------|----------------|
| Itens Vendidos       | Produto A, Produto B |
| Valor da Venda       | R$ 1000,00     |
| IRPF                 | R$ 100,00      |
| PIS                  | R$ 16,50       |
| COFINS               | R$ 76,00       |
| INSS                 | R$ 80,00       |
| ISSQN                | R$ 50,00       |
| Total de Impostos    | R$ 322,50      |
| Valor Líquido        | R$ 677,50      |

## Contribuindo

Sinta-se à vontade para contribuir com melhorias no código. Para isso, basta seguir os seguintes passos:

1.**Fork o repositório.**

2.**Crie uma branch para suas alterações** (git checkout -b feature/nova-funcionalidade).

3.**Faça commit das suas alterações** (git commit -m 'Adiciona nova funcionalidade').

4.**Push para a branch** (git push origin feature/nova-funcionalidade).

5.**Crie um Pull Request explicando as mudanças.**

## Lincença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
