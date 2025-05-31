# Implementação Manual de Backpropagation para Problema XOR

## Introdução

Este mini projeto tem como objetivo reforçar o aprendizado dos conceitos de backpropagation implementados manualmente, funções de ativação não lineares e redes neurais com múltiplas camadas.

Utilizei a função de custo de erro quadrático médio (MSE) e a função de ativação sigmoid para os neurônios da camada oculta e da camada de saída.

### Arquitetura da rede

entrada -> A11 
               \
		\
	            A2 -> saída
                /	
entrada -> A12 /


- A11 e A12 são neurônios da camada oculta;
- A2 é o neurônio da camada de saída.

---

## Como rodar

Para rodar o código, basta ter o Python instalado. É possível alterar o conjunto de entradas para representar qualquer porta lógica, seja linearmente (AND, OR) ou não linearmente separável (XOR, XNOR).

---

## Resultados e Conclusões

A implementação demonstra que a rede neural com backpropagation, função de ativação não linear e múltiplas camadas é capaz de aprender todas as portas lógicas.

No entanto, observei que ao rodar o código várias vezes, para o problema XOR a rede converge para a saída desejada em cerca de 75% das execuções. Nas demais, a rede não converge, independentemente do número de gerações.

Acredito que isso está relacionado à inicialização aleatória dos pesos, que pode afetar a convergência. Além disso, o uso da função de custo MSE pode não ser o mais adequado para esse tipo de problema, e a Cross-Entropy Loss poderia melhorar o desempenho.

---

## Tecnologias utilizadas

- Python (versão 3)
- Biblioteca(s) padrão (sem frameworks externos)
