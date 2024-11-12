# Gerenciamento de Inventário para Loja de Instrumentos Musicais 🎸🎷

## Descrição
Este projeto é um sistema de gerenciamento de inventário de instrumentos musicais, desenvolvido em Python para fins educacionais na disciplina de **Programação Orientada a Objetos (POO)**. O software permite gerenciar o estoque de instrumentos, como guitarras, mandolins, banjos e saxofones, com funcionalidades de pesquisa baseadas em características específicas dos itens.

## Funcionalidades Principais
- **Cadastro de Instrumentos**: Adiciona novos instrumentos ao inventário com informações detalhadas.
- **Busca Personalizada**: Pesquisa instrumentos por características como fabricante, tipo de madeira, modelo, etc.
- **Exibição de Resultados**: Mostra sugestões de instrumentos correspondentes aos critérios de busca.

## Estrutura do Projeto
- **Enums**: Define valores fixos para fabricantes, tipos de instrumentos, estilos, etc.
- **Classes**:
  - `Instrument`: Representa um instrumento musical com atributos como número de série e preço.
  - `InstrumentSpec`: Define especificações dos instrumentos para comparação de características.
  - `Inventory`: Gerencia a lista de instrumentos e permite adicionar e buscar itens no inventário.

## Como Executar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/FabioPYAug/Projeto-GT.git
