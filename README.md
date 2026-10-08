# Ponto Q ⚡

Um aplicativo web leve e interativo para calcular e visualizar o **Ponto Quiescente (Ponto Q)** de circuitos com transistores bipolares de junção (TBJ) do tipo NPN.

O projeto foi construído em um único arquivo (HTML, CSS e Vanilla JS), sem dependências externas, garantindo que seja rápido, responsivo e funcione perfeitamente offline ou hospedado em qualquer servidor estático.

## 🚀 Funcionalidades

* **Dois tipos de circuitos suportados:** Polarização por Divisor de Tensão e Polarização com Resistor na Base.
* **Cálculo Passo a Passo:** O aplicativo não apenas dá o resultado final, mas detalha as fórmulas, substituições e o raciocínio utilizado (ideal para estudantes de eletrônica).
* **Análise Flexível:** Escolha entre a análise aproximada (desprezando a corrente da base) ou a análise exata (via equivalente de Thévenin).
* **Gráfico Dinâmico:** Reta de carga desenhada em SVG puro, plotando o Ponto Q em tempo real com base nos valores inseridos.
* **Entrada de Dados Inteligente:** Aceita vírgulas (ex: `2,2`) e notação de engenharia comum (ex: `3k9` para 3900 Ω, `1M` para 1000000 Ω).
* **Identificação de Região:** Identifica automaticamente se o transistor está na Região Ativa, Saturação ou Corte.

## 🌐 Como Acessar

Você pode acessar a calculadora diretamente pelo navegador, sem precisar instalar nada, clicando no link abaixo:

👉 **https://clarameloq.github.io/CalculadoraPontoQ/**

## 💻 Como rodar localmente

Como o projeto não possui dependências complexas ou back-end, rodar localmente é extremamente simples:

1. Faça o clone do repositório:
   ```bash
   git clone [https://github.com/clarameloq/CalculadoraPontoQ.git](https://github.com/clarameloq/CalculadoraPontoQ.git)

    Abra a pasta do projeto.

    Dê um duplo clique no arquivo index.html para abri-lo no seu navegador padrão.
