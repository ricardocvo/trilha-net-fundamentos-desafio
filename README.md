# Trilha .NET - Fundamentos - Sistema de Estacionamento 🚗

Desafio de projeto desenvolvido como parte da trilha de fundamentos em .NET. O objetivo principal é fixar os conhecimentos adquiridos em C# e lógica de programação, simulando o gerenciamento de veículos em um estacionamento.

---

## 💻 Sobre o Projeto

O sistema consiste em uma aplicação de console desenvolvida em C# que gerencia a entrada, saída e listagem de veículos, além de calcular o valor total cobrado pelo período em que o carro permaneceu estacionado com base em uma taxa fixa inicial e um valor por hora.

### Principais Funcionalidades

*   **Cadastrar veículo:** Permite ao usuário digitar a placa de um veículo e adicioná-lo à lista de automóveis estacionados.
*   **Remover veículo:** Verifica se a placa informada está no pátio. Caso esteja, solicita o total de horas que o veículo permaneceu estacionado, realiza o cálculo de cobrança e remove o veículo do sistema.
*   **Listar veículos:** Exibe na tela todos os veículos atualmente estacionados. Caso o pátio esteja vazio, exibe uma mensagem informativa.
*   **Menu Interativo:** Menu em loop para facilitar a navegação do usuário pelas opções do sistema.

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** C#
*   **Plataforma:** .NET 
*   **Ambiente de Desenvolvimento:** Visual Studio

---

## 📖 Estrutura do Código

A lógica principal está concentrada na classe `Estacionamento`, que contém:

*   **Campos Privados:**
    *   `precoInicial`: Taxa cobrada apenas por deixar o veículo estacionado.
    *   `precoPorHora`: Valor cobrado por hora de permanência.
    *   `veiculos`: Uma lista de strings (`List<string>`) utilizada para armazenar as placas.
*   **Métodos:**
    *   `AdicionarVeiculo()`
    *   `RemoverVeiculo()`
    *   `ListarVeiculos()`

---

## 🚀 Como Executar o Projeto Localmente

1. Certifique-se de ter o **SDK do .NET** instalado em sua máquina.
2. Clone este repositório:
```bash
   git clone [https://github.com/ricardocvo/trilha-net-fundamentos-desafio.git](https://github.com/ricardocvo/trilha-net-fundamentos-desafio.git)
