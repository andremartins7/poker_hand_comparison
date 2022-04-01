# <h1 align="center"> Poker Hand Comparison </h1>
![poker](https://user-images.githubusercontent.com/29736240/161343803-3c2f3540-f8ff-448e-bb4c-f9876ef39731.jpeg)

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

![GitHub Org's stars](https://img.shields.io/github/stars/camilafernanda?style=social)

## Contexto

Um famoso cassino de repente enfrenta um grande declínio de sua receita. Então eles decidem oferecer uma versão online do jogo de Poker. Podemos ajudá-los escrevendo um algoritmo para ranquear as mãos de Poker.

## Resumo

Este programa feito em python representa uma mão de Poker chamada "PokerHand" e possue os métodos/classes para comparar uma mão de Poker com outra e definir a vencedora.
Ele possui um construtor que aceita uma String contendo 5 cartas.

Originalmente o projeto foi eleborado em formato de Notebook utilizando o Google Colab, posteriormente foi adaptado para o formato `.py`.

## ✔️ Técnicas e tecnologias utilizadas

- `Python 3.0`
- `Google Colab`
- `VSCode`
- `Biblioteca random`
- `Conceitos de POO`
- `Conceitos de TDD`

## :hammer: Funcionalidades do projeto

- `hand_dist`: Função de distribuição de mãos das cartas usando dicionário
- `hand_rank`: Função para classificação de mão para um conjunto de cartas
- `compare_hands`: Função de comparação entre duas mãos
- `show_compare_hands`: Função que apresenta a comparação entre as duas mãos

## 🛠️ Abrir e rodar o projeto

### Usando o arquivo `.py` na sua máquina local:
No Terminal, cd neste repositório e execute o seguinte: `python pokerhand_andre.py`

Isso gerará aleatoriamente tabuleiros de cinco cartas, mais duas mãos de amostra de duas cartas cada. Ele então lhe dirá qual deles ganhou e qual é o valor de cada mão.

### Usando o Google Colab:

Abra o arquivo `.ipynb` e click no ícone ![Screenshot_35](https://user-images.githubusercontent.com/29736240/161349610-a3e600d2-2109-46e7-af40-5d78590ba4c8.jpg)

Isso irá abrir um notebook no navegador onde se poderá executar células individualmente. 

## Informações importantes:

- Uma mão de Poker é composta por 5 (cinco) cartas;
- Cada carta possuirá uma string com 2 (dois) valores.
  - Primeiro caractere será o valor da carta e pode conter um dos valores abaixo descritos. Os itens abaixo estão ordenados do menor valor para o maior valor:
    - 2
    - 3
     - 4
    - 5
    - 6
    - 7
     - 8
    - 9
    - T (10)
     - J (Valete)
    - Q (Rainha)
    - K (Rei)
    - A (Ace)
   
  - Segundo caractere é o naipe da carta e pode conter um dos abaixo descritos.
    - S (Espadas) 
    - H (Copas)
    - D (Ouros)
    - C (Paus)

- As regras de ordenação de cartas do Poker estão listadas na figura abaixo.

![image](https://user-images.githubusercontent.com/29736240/161346385-2252bb66-a201-4fd8-91c3-c633a7c182b0.png)
