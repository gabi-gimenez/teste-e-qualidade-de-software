# teste-e-qualidade-de-software

# A Documentação foi descrita no código?

O código não fornece uma introdução clara à sua finalidade. 
É importante documentar o propósito do código no início do arquivo
ou em comentários para que outros desenvolvedores possam entender sua função

# As variaveis e constantes possuem boa nomenclatura?
Os nomes de variáveis e classes são genéricos e não descrevem adequadamente 
sua finalidade.A classe User parece representar uma conexão com o banco de dados,
o que pode ser confuso. É aconselhável escolher nomes descritivos e autoexplicativos
para melhorar a manutenção e compreensão do código.

# Existem legibilidade e organização no código?

A formatação do código é inadequada, o que torna a leitura e compreensão mais difíceis.
É fundamental adotar uma convenção de identação consistente para melhorar a legibilidade.
O uso adequado de espaços entre linhas e o posicionamento adequado de colchetes também são 
essenciais para tornar o código mais claro

# Todos os nullpointers foram tratados?

Não há feedback ao usuário sobre o sucesso ou falha ao tentar se conectar ao banco de dados. 
É importante implementar tratamento de erros adequado e fornecer mensagens informativas 
para o usuário, indicando o resultado da operação de conexão.

O código não realiza validação adequada das informações de login e senha. É importante
implementar validações para garantir que os dados fornecidos sejam seguros e válidos 
antes de usá-los na consulta ao banco de dados.

# A Arquitetura utilizada foi devidamente respeitada?

O código não apresenta uma arquitetura clara ou um modelo arquitetônico para orientar o desenvolvimento. Isso pode resultar em falta de estrutura, consistência e direção para a equipe de desenvolvimento. Há ausência de camadas bem definidas no código que dificulta a compreensão das responsabilidades de cada componente. Uma arquitetura em camadas é essencial para separar as preocupações do sistema e manter a coesão e o baixo acoplamento entre os componentes.

# As conexões utilizadas foram fechadas?

O código não fecha a conexão com o banco de dados. Isso pode levar a problemas
de desempenho e segurança, uma vez que muitos sistemas de gerenciamento de banco 
de dados possuem limites de conexão. É fundamental incluir uma instrução de
fechamento da conexão após o uso para liberar recursos e evitar vazamentos de conexão.


# ETAPA 2 - TESTE CAIXA BRANCA

Utilizando a imagem do link https://github.com/gabi-gimenez/teste-e-qualidade-de-software/blob/master/teste_caixa_branca_etapa2.jpeg  como base para o exercício, calculei a complexidade ciclomática, sabendo que:

Calculo complexidade ciclomática

Cal = (Numero de arestas - numero de nós + 2)

Aplicando no fluxo de grafo da imagem:

calculo_complexidade_ciclomatica = 10 - 11 + 2 

calculo_complexidade_ciclomatica = 1

Calculando o caminho independente:

Caminho independente 

1. {1,2,4,5,6,7,8,9,11}

