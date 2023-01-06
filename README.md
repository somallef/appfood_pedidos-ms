# appfood [Microsserviço de pedidos]

Projeto criado como acompanhamento do treinamento [Microsserviços na prática: implementando com Java e Spring](https://www.alura.com.br/curso-online-microsservicos-implementando-java-spring)

Para criar um pedido, basta enviar uma requisição POST com o seguinte corpo:

``` json
{
    "itens": [
    	{
        "quantidade": 10,
        "descrição": "Coca-cola"
    	},
    	{
        "quantidade": 5,
        "descrição": "Mc Chicken"
    	}
    ]
}
```