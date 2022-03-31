# Otimização da Rotina de Confecção de Procurações para Representação de Fundos de Investimentos em Assembleias

#### Aluno: [Juliana Barbosa](https://github.com/julybarbosa/procuracoes)
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

Trabalho idealizado para otimizar a rotina de confecção de procurações para representação de fundos de investimentos em Assembleias. Anualmente confeccionamos dezenas de procurações onde temos dezenas de fundos representados em cada uma delas. Em especial destaco o mês de abril, onde a maior parte delas acontece. A partir deste ano, o projeto será utilizado na prática, garantindo segurança, agilidade e reduzindo o risco operacional. 

### 1. Introdução

O trabalho foi idealizado para resolver uma das minhas atribuições em meu trabalho, que é confeccionar procurações para representar os fundos nas Assembleias das empresas onde eles têm participação. Um exemplo é uma Assembleia da Petrobras, onde o código do ativo é PETR3 por exemplo. Todos os fundos que têm PETR3 na carteira podem participar da Assembleia, com a devida participação, ou seja, um fundo tem 1000 ações da PETR3, outro tem 200000. O somatório das quantidades de PETR3 dos fundos
discriminados na procuração vão determinar a capacidade de votação no assunto a ser deliberado na Assembleia. Ao identificar os fundos e a participação deles, são indicados os advogados que poderão representar os fundos na Assembléia e quem vai assinar a procuração. Imprimimos o documento em PDF para que seja assinado pelos representantes indicados. Considerando a importância deste trabalho e o fato de cada procuração ser feita hoje de maneira manual, onde copiamos e colamos as informações, idealizei o projeto a fim de reduzir o tempo gasto, assim como o risco operacional
pela possibilidade de deixar alguma informação sem constar no documento e também a redução do tempo gasto no processo, pois precisamos sempre fazer horas extras para fazer a rotina diária prevista e ainda confeccionar as Procurações.  

### 2. Modelagem

Primeiro, usei no Python o FPDF, uma vez que as procurações são vinculadas em PDF para assinatura dos representantes. Criei o título, que é sempre Procuração. Os fundos estão em uma coluna e os CNPJs estão em outra, e por este motivo fiz com que entre o nome do fundo e o número constasse a palavra CNPJ. Ao indicar os prepostos, indiquei as colunas como nome, qualificação, CPF e cargo, indicando as pessoas autorizadas a assinar a procuração. Antes da pandemia, todas as Assembleias eram presenciais e no momento a maioria tem sido online, então por este motivo há uma possibilidade de
escolha. Podemos escolher o nome da empresa, data e horário. Considerei a data atual como sendo a data de assinatura da procuração. Criei a base das informações que devem constar na procuração assim como a fonte. Deixei ainda um espaço para assinatura dos indicados. Com a análise exploratória de dados, foi possível analisar e resumir os conjuntos de dados e com isso visualizar os dados dos procuradores com facilidade. Também foi possível visualizar por gráfico que a maioria dos procuradores é casada, do sexo masculino, do Rio de Janeiro e que todos são advogados. Foi possível perceber 
também os dados dos prepostos, onde a maior parte também é do sexo masculino, reside no Rio de Janeiro, casado, todos são bancários e a maioria tem o cargo de gerente executivo.

### 3. Resultados

Através da análise exploratória, foi possível ainda ter as informações dos envolvidos, procuradores e prepostos. Além disso, as procurações foram geradas conforme previsto, com todas as informações necessárias e o principal, sem a possibilidade de haver erro na confecção do documento e de forma rápida e segura. 

### 4. Conclusões

Além de ser o trabalho do curso, tive a oportunidade de colocar em prática os conhecimentos adquiridos e que realmente vai fazer a diferença na minha rotina e da minha equipe. 

---

Matrícula: 183.477.009

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*


![image](https://user-images.githubusercontent.com/96187336/159205377-af8b0023-29e6-4c75-ace6-d236fe9c86f1.png)

![image](https://user-images.githubusercontent.com/96187336/159205428-0611722b-6c8b-46cc-a523-cb7b445aafc1.png)

![image](https://user-images.githubusercontent.com/96187336/159205450-14360b76-eb27-4316-9269-a4f068d34679.png)

![image](https://user-images.githubusercontent.com/96187336/159205474-cdfb372a-82ed-4dc7-87be-989d0f637d5c.png)

![image](https://user-images.githubusercontent.com/96187336/159205501-59342906-89c4-4efc-bb2e-9eb7fdd9a3b8.png)

![image](https://user-images.githubusercontent.com/96187336/159205519-ac07df60-2511-432f-b022-bf322ac51767.png)

![image](https://user-images.githubusercontent.com/96187336/159205530-c6a666a2-5647-4667-ae24-6a11d2c1e0ec.png)

![image](https://user-images.githubusercontent.com/96187336/159205540-06a2d5b2-eb09-4922-83b3-7b917dad3bb1.png)

![image](https://user-images.githubusercontent.com/96187336/159205549-f45da324-5a6f-4264-9da8-16107e95dbbd.png)

![image](https://user-images.githubusercontent.com/96187336/159205556-146761d3-8372-4d04-80ef-ca47d871970e.png)

![image](https://user-images.githubusercontent.com/96187336/159205567-b0052f6e-47fb-4f13-acb2-f53406682457.png)

![image](https://user-images.githubusercontent.com/96187336/159205577-662560b7-c265-4b79-a1d4-3c25f91ad6e5.png)

![image](https://user-images.githubusercontent.com/96187336/159205603-0afb8ab8-3512-4309-b468-47589fa8d35a.png)

![image](https://user-images.githubusercontent.com/96187336/159205610-57fbd962-c021-44b6-88f5-bd72d572f836.png)
