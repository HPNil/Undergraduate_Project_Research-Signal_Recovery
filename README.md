SOBRE O PROJETO
O projeto visa a aplicação de modelos de otmização para a reconstrução de sinal do calorímetro do Atlas Experiment no contexto do LHC.

SOBRE O ARQUIVO
Introdução
O arquivo do algoritmo implementado está armazenado em um ambiente virtual, assim, o protejendo de possiveis conflitos de versão com as bibliotecas utilizadas.

Algoritmo de Otimização
O coração do dos arquivos é o "Nelder-Mead_Method.ipynb", nele, está implementado todo o algoritmo de otimização seguindo os conceitos do livro [1]. 
Houve uma mudança drástica no algoritmo utilizado, ao invés de utilizar a biblioteca SciPy, optou-se por implementar o método para que se possa atribuir modificações a sua estrutura seguindo o artigo [2], assim, melhorando o desempenho do algoritmo.

Arquivos .csv
Os arquivos do tipo csv são as bases de dados sintéticas geradas a partir do aquivo "synthetic_database.py". Essas base de dados são compostas por diversos registros de sinais, onde a "db_pileup_noise.csv" possui a inclusão de ruídos.

REFERÊNCIAS
[1] Jorge Nocedal, Stephen J. Wright - Numerical Optimization
[2] Fuchang Gao, Lixing Han - Implementing the Nelder-Mead simplex algorithm with adaptive parameters
