# DesafioControleFluxo

Este projeto é um exercício de controle de fluxo em Java. O programa recebe dois números inteiros como parâmetros via terminal e imprime uma série de números incrementados com base na diferença entre os dois parâmetros. Caso o primeiro parâmetro seja maior que o segundo, uma exceção personalizada é lançada.

## Funcionalidades

- Solicitar dois números inteiros do usuário via terminal.
- Imprimir números incrementados baseados na diferença dos parâmetros.
- Lançar uma exceção personalizada se o primeiro parâmetro for maior que o segundo.

## Estrutura do Projeto

O projeto contém duas classes principais:

- `Contador`: Contém a lógica principal do programa.
- `ParametrosInvalidosException`: Define a exceção personalizada que é lançada quando o segundo parâmetro é menor que o primeiro.

## Como Executar o Projeto

### Requisitos

- Java Development Kit (JDK) instalado.
- Um ambiente de desenvolvimento como Visual Studio Code, IntelliJ IDEA ou Eclipse.

### Passo a Passo

1. **Clone o repositório ou baixe os arquivos:**
    ```sh
    git clone https://github.com/leolsm12/desafiocontrolefluxo.git
    ```
    Ou baixe o arquivo zip e extraia em um diretório de sua escolha.

2. **Navegue até o diretório do projeto:**
    ```sh
    cd desafiocontrolefluxo/src
    ```

3. **Compile o código:**
    ```sh
    javac Contador.java ParametrosInvalidosException.java
    ```

4. **Execute o código:**
    ```sh
    java Contador
    ```

5. **Siga as instruções no terminal para inserir os números:**
    - Digite o primeiro parâmetro:
    - Digite o segundo parâmetro:

## Exemplo de Uso

#### Entrada

```shell
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
```

#### Saída

```shell
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
...
Imprimindo o número 18
```

### Se o primeiro parâmetro for maior que o segundo:

#### Entrada

```shell
Digite o primeiro parâmetro:
12
Digite o segundo parâmetro:
30
```

#### Saída

```shell
O segundo parâmetro deve ser maior que o primeiro
```