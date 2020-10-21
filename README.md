# chamadasassincronas
1. Qual o problema que percebeu ao realizar tais alterações?

    A ordem em que é exibido as tags e o resultado da pesquisa, não condiz com a forma como foi implementada no script. Já que a função é chamada antes de mostrar a tag h2 criada, e ainda assim ela é exibida antes.

2. Explique porque o problema ocorreu e qual a relação com chamadas assíncronas?

    Este problema ocorre porque a chamada assíncrona não espera ser finalizada para executar a próxima linha de código (que no caso é a exibição da tag h2) ela vai carregando o que estiver pronto, para depois exibir o resultado da request.
    
3. Altere o código para resolver o problema.