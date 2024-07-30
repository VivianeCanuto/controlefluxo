DesafioControleFluxo
Este projeto é um simples programa Java que demonstra o controle de fluxo e exceções personalizadas. 
O programa lê dois números inteiros do usuário e imprime uma sequência de números incrementados com base na diferença entre os dois números.
Se o primeiro número for maior que o segundo, uma exceção personalizada é lançada.

Classes
Contador
A classe Contador contém o método main, que lê os parâmetros de entrada do usuário e chama o método contar. 
Se o primeiro parâmetro for maior que o segundo, uma exceção ParametrosInvalidosException é lançada.

Métodos
public static void main(String[] args):
Lê os parâmetros de entrada e chama o método contar.

static void contar(int parametroUm, int parametroDois) throws ParametrosInvalidosException:
Valida os parâmetros e imprime a sequência de números incrementados.

ParametrosInvalidosException
A classe ParametrosInvalidosException é uma exceção personalizada que estende a classe Exception. 
Ela é lançada quando o primeiro parâmetro é maior que o segundo.

Como Executar
Clone o repositório:

bash
git clone <URL do repositório>

Navegue até o diretório src:
bash

cd src
Compile os arquivos Java:
bash

javac com/desafio/controlefluxo/*.java
Execute o programa:
bash

java com.desafio.controlefluxo.Contador
