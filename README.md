# python-busca-precos-web

Projeto realizado utilizando Jupyter Notebook 
https://jupyter.org/

Projeto do curso Python Impressionador da Hashtag Treinamentos
https://www.hashtagtreinamentos.com/curso-python

Projeto Automação Web - Busca de Preços

Objetivo: projeto que utiliza automações web com Selenium para buscar as informações que precisamos

Descrição:
Imagine que você trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos.

Nessa hora, você vai constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

Seu objetivo: descobrir o produto mais barato e atualizar isso em uma planilha.

Caso o valor seja 20% (ou mais) abaixo do preço original, queremos também ser avisados por e-mail para poder agir rápido e aproveitar essa promoção.

No nosso caso, vamos fazer com produtos comuns em sites como Amazon, Magazine Luiza e Lojas Americanas, mas a ideia é a mesma.

O que temos disponível?
Planilha de Produtos, com os nomes dos produtos e o link em cada loja, além do preço original cadastrado.

O que devemos fazer:
Cadastrar na coluna Preço Atual o menor preço encontrado e na Coluna Local o nome do Local onde foi encontrado esse preço
Enviar um e-mail para compras com a notificação do menor preço encontrado e o link de compra, caso o preço encontrado esteja com 20% ou mais de desconto em relação ao preço original. (Vou usar o e-mail pythonimpressionador+compras@gmail.com. Use um e-mail seu para fazer os testes para ver se a mensagem está chegando)

Adicional:
Podemos colocar esse programa para rodar de 4 em 4 horas ou então todo dia as 10hrs da manhã. Podemos fazer isso via agendador de tarefas do Windows ou então deixar o código rodando em background com um time.sleep(tempo)
Caso queira, você pode deixar o navegador sem aparecer ao término do seu código, para ficar mais sutil o seu programa