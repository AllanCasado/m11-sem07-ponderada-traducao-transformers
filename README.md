# Pontos Positivos e Negativos da Abordagem com Transformers

## Pontos Positivos:

* Desempenho superior: Por conta do mecanismo de autoatenção, que permite que o modelo considere relações entre palavras distantes no texto, as traduções são mais coerentes e corretas, superando abordagens mais tradicionais como RNNs e CNNs.

* Paralelização eficiente: Diferentemente dos modelos sequenciais, os Transformers permitem processamento paralelo das sequências, acelerando o treinamento e a inferência.

* Flexibilidade: Uma vantagem geral dos Transformers é que eles possuem uma arquitetura versátil e que pode ser utilizada em diferentes tarefas de NLP além da tradução, como resumo de texto e resposta a perguntas.

## Pontos Negativos:

* Alto custo computacional: Requerem recursos computacionais significativos, como GPUs, principalmente devido ao mecanismo de autoatenção que escala muito conforme o texto aumenta de tamanho. 

* Necessidade de muitos dados: Para atingir um bom desempenho, os Transformers geralmente precisam de grandes volumes de dados de treinamento, o que pode não estar disponível para todos os idiomas ou domínios.

* Complexidade de implementação: São modelos mais complexos de implementar e ajustar corretamente quando comparado com arquiteturas mais simples como RNNs.

* Ineficientes para sequências muito longas: Por causa do mecanismo de autoatenção, o tempo de processamento aumenta significativamente com textos longos.

