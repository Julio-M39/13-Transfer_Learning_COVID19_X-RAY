## Transfer Learning Para Categorização de Patologias

OBS: Caso o Github não renderize o arquivo .ipynb use os links abaixo:

- <a href="https://nbviewer.org/github/Julio-M39/13-Transfer_Learning_COVID19_X-RAY/blob/main/Detec%C3%A7%C3%A3o%20de%20Anomalias%20em%20Radiografias%20do%20T%C3%B3rax%20de%20Pacientes%20com%20Covid%20%281%29.ipynb">Clique Aqui!</a> 

### Definição do Projeto

A ideia geral da aprendizagem por transferência é usar o conhecimento aprendido em tarefas para as quais muitos dados rotulados estão disponíveis em ambientes onde apenas poucos dados rotulados estão disponíveis. Criar dados rotulados é caro, portanto, aproveitar os conjuntos de dados existentes de maneira ideal é fundamental.

Em um modelo de aprendizado de máquina tradicional, o objetivo principal é generalizar para dados invisíveis com base em padrões aprendidos com os dados de 
treinamento. Com a aprendizagem por transferência, você tenta iniciar esse processo de generalização começando a partir de padrões que foram aprendidos para uma tarefa diferente. Essencialmente, em vez de iniciar o processo de aprendizagem a partir de uma folha em branco (geralmente inicializada aleatoriamente), você começa a partir de padrões que foram aprendidos para resolver uma tarefa diferente. A transferência de conhecimento e padrões é possível em uma ampla variedade de domínios.

Neste projeto vamos construir um modelo de IA que ao receber uma imagem e será capaz de detectar se há alguma anomalia que indique a presença de COVID. Daremos ênfase ao Transfer Learning e ainda apresentaremos uma nova técnica de tratamento de dados desbalanceados.

**Referências:**

- <a href="https://deepai.org/machine-learning-glossary-and-terms/transfer-learning">Transfer Learning</a>
- <a href="https://openreview.net/pdf?id=ryebG04YvB">ADVERSARIALLY ROBUST TRANSFER LEARNING</a>
- <a href="https://openreview.net/pdf?id=ryeYpJSKwr">META-LEARNING ACQUISITION FUNCTIONS FOR TRANSFER LEARNING IN BAYESIAN OPTIMIZATION</a>

Fonte de Dados:

https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/#1590858128006-9e640421-6711

### Etapas do Projeto

- Preparação dos Dados
- Dataset Augmentation
- Modelagem - Transfer Learning
- Avaliação do Modelo
- Confusion Matrix
- Previsão com o Modelo Treinado

### Resultados

A imagem abaixo mostra a matriz de confusão:

<div>
<img src="https://user-images.githubusercontent.com/54995990/193692932-a7efd44f-a291-4489-b841-a2c8f59c06ea.png" width="350px" />
</div>

A imagem abaixo mostra um relatório de classificação:

<div>
<img src="https://user-images.githubusercontent.com/54995990/193693313-c5757d9b-a947-406e-ae00-9c8204133890.png" width="550px" />
</div>
