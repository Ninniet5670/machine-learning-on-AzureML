## Detalhes da solução do problema

Seguiu-se o passo-a-passo da aula **Trabalhando com Machine Learning na Prática no Azure ML** do curso **Microsoft Azure AI Fundamentals** da plataforma **DIO**, no entanto, notou-se um vácuo da 5° aula (Configurando Modelos e Conjuntos De Dados) para a 6° (Análise e teste de modelo), onde depois do Job ter sido concluído, as abas Models e Endpoints já estavam disponíveis, não demonstrando o processo de sua configuração

Após isso, tentei eu mesmo criar um modelo a partir do um job output e a partir dele, seu endpoint. Em consequência disso, tive um problema que não consegui testar os endpoints do modelo dando o seguinte erro: `Failed to test model: A value is not provided for the 'input_data' parameter.`

Fui então atrás da documentação que a instrutora falava e no final do módulo estava o link com o passo-a-passo oferecido pela própria Microsoft e, com ele, resolvi o problema dando o deploy do modelo direto da página de detalhes do mesmo



## Referências:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html (passo-a-passo da Microsoft)

https://www.dio.me/bootcamp/microsoft-azure-ai-fundamentals (curso da DIO)
