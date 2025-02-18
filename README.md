# Controle de Fluxo

Este projeto é uma aplicação Java simples que recebe dois números inteiros como entrada via terminal e imprime uma sequência de números incrementados com base na diferença entre esses dois números. Se o primeiro número for maior que o segundo, uma exceção personalizada será lançada.

## Funcionalidades

- Recebe dois números inteiros como entrada via terminal.
- Calcula a diferença entre os dois números.
- Imprime uma sequência de números incrementados com base na diferença.
- Lança uma exceção personalizada (`ParametrosInvalidosException`) se o primeiro número for maior que o segundo.

## Estrutura do Projeto

- **Contador.java**: Classe principal que contém a lógica de contagem e manipulação das entradas.
- **ParametrosInvalidosException.java**: Classe que representa uma exceção personalizada para validação de parâmetros.

## Como Executar

1. Certifique-se de ter o Java instalado no seu sistema.
2. Clone este repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/Janainaramos/ControleDeFluxo.git
Navegue até o diretório do projeto:

bash
cd ControleDeFluxo
Compile o projeto:

bash
javac Contador.java
Execute o projeto:

bash
java Contador
Exemplo de Uso
Ao executar o programa, você será solicitado a digitar dois números inteiros:

Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
O programa então imprimirá a sequência de números incrementados:

Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
Se o primeiro parâmetro for maior que o segundo, uma exceção será lançada:

Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12
O segundo parâmetro deve ser maior que o primeiro
Contribuição
Se você deseja contribuir com este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para qualquer dúvida ou sugestão, entre em contato:

Nome: Janaina Ramos

Email: janainajcr.ramos@gmail.com
