# Projeto Tabela Fipe

O **projeto-TabelaFipe** é uma aplicação em Java que consulta dados de veículos com base na Tabela Fipe. Através de uma interface de linha de comando, o usuário pode obter informações sobre carros, motos e caminhões, filtrando por marcas, modelos e anos.

## Funcionalidades

- **Consulta de Marcas**: O usuário pode selecionar o tipo de veículo (carro, moto ou caminhão) e visualizar as marcas disponíveis.
- **Modelos**: Após selecionar uma marca, é possível visualizar os modelos correspondentes.
- **Filtragem por Nome**: O usuário pode digitar um trecho do nome do veículo desejado para obter modelos semelhantes.
- **Anos Disponíveis**: Após selecionar um modelo, o aplicativo exibe os anos disponíveis para aquele veículo.
- **Informações Detalhadas**: A aplicação retorna detalhes dos veículos filtrados.

## Estrutura do Projeto

- **Pacotes**:
  - `br.com.limeira.TabelaFipe.principal`: Contém a classe `Principal`, que gerencia a interação com o usuário e a lógica principal da aplicação.
  - `br.com.limeira.TabelaFipe.model`: Define as classes de modelo, como `Dados`, `Modelos`, e `Veiculo`.
  - `br.com.limeira.TabelaFipe.service`: Contém serviços como `ConsumoApi`, que realiza chamadas à API da Tabela Fipe, e `ConverteDados`, que converte os dados recebidos.

## Tecnologias Utilizadas

- **Java**: Linguagem principal para o desenvolvimento da aplicação.
- **API da Tabela Fipe**: Utilizada para obter dados de veículos.
