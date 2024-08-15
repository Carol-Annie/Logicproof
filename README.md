# Logicproof
A biblioteca logicproof foi desenvolvida para auxiliar na criação de provas lógicas, com o foco maior em lógica de predicados e lógica de primeira ordem. Permitindo a organização das provas em estruturas de blocos que destacam as subprovas ou lemas; e declaração é acompanhada de uma justificativa, ou seja, qual a regra aplicada e as linhas/caixas envolvidas.

* Como utilizar?
Para utilzar a biblioteca basta utilizar o comando \usepackage{logicproof}. Para começar a desenvolver a estrutura da prova os comandos \begin{logicproof}{n} \end{logicproof} são empregados. De modo similar as caixas são criadas utilizando \begin{subproof} \end{subcproof}. Os conectivos lógicos são representados por: \lnot para a negação, \lor  para a disjunção, \land para conjunção, \to para o 'então' e \bot para representar a contradição/absurdo.
