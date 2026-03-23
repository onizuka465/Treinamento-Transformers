Resolução de Atividade Facultativa, Treinamento de um Modelo Transformers

Para rodar este codigo devidamente, precisa-se de utilizar o Google Colab para o treinamento do modelo com um vocabulario de 1000 frases e dividido em 32 batches.
Precisa-se das seguintes bibliotecas: Numpy, PyTorch e Transformers. Além de um tokenizador já pré-treinado (inserido já no codigo)

Recomendo usar o ambiente de execução das GPU's T4 inves da CPU, o treinamento do modelo usando a CPU estava passando de 20 minutos apenas com 10 loops de treino. Enquanto usando as GPU's com 20 loops de treino duraram apenas 1 minuto.

Observação: Execute todos os codigos divididos no Google colab na sequência posta para a execução devida do codigo como um todo. Para melhor tradução do modelo, execute o codigo de treino dele multiplas vezes, o Loss continua salvo depois de sua execução, logo cada vez que o codigo do Training loop for executado, melhor o modelo fica em chegar na tradução esperada, executando o ultimo codigo depois do treino demonstrara isso.

As ferramentes usadas foi apenas a I.A Claude, usada principalmente nas sintaxes do PyTorch e no auxilio da otimização do Training Loop.
