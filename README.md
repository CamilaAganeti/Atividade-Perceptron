# Atividade Perceptron

##  Objetivo
Compreender, de forma aplicada, o funcionamento do Perceptron, um dos modelos mais simples e fundamentais de redes neurais artificiais.

---

## 1. Conceito
O Perceptron é um modelo matemático inspirado no funcionamento dos neurônios biológicos.  
Ele recebe valores de entrada, multiplica cada um por um peso, soma todos e adiciona um **bias** (ajuste).  
Se o resultado for maior ou igual a zero, a saída é **1**, caso contrário, **0**.  
Historicamente, o Perceptron foi um dos primeiros passos para a construção de redes neurais e abriu caminho para os modelos mais complexos usados atualmente em Inteligência Artificial.

---

## 2. Funcionamento
O Perceptron é chamado de **classificador linear** porque ele só consegue separar os dados em duas classes usando uma linha (ou um hiperplano em dimensões maiores).  
Isso significa que ele funciona bem em problemas simples de separação linear, mas **não consegue resolver problemas mais complexos**, como o clássico exemplo do XOR.

---

## 3. Código
No código fornecido, as principais etapas foram:
- **Definição da função `perceptron_input`**: calcula a soma ponderada das entradas com os pesos, adicionando o bias.  
- **Definição da função `perceptron_output`**: aplica a regra de ativação, retornando 1 ou 0 dependendo do valor da soma.  
- **Função `main`**: executa o programa e mostra o resultado da entrada do perceptron.  

Esse código não tem um "treinamento completo" com ajuste de pesos, mas sim a **base de cálculo** que o perceptron utiliza.

---

## 4. Aplicação prática
Um exemplo simples de aplicação do Perceptron seria em um **sistema de filtro de spam**:  
- Entradas: presença de certas palavras no e-mail (ex: "promoção", "grátis", "oferta").  
- Saída: se o e-mail é spam (1) ou não (0).  

Nesse caso, mesmo um modelo simples como o Perceptron pode ser útil, pois é rápido, fácil de implementar e funciona bem quando os dados podem ser separados de forma linear.

---

