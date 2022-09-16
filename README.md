# SelfCheckout

Developed in Visual Studio 2022, .NET 6.
The project implements Swagger API, and should be used on it's default page, where the GET and POST requests can be found.

Main features:
STOCK GET - Returns a list of every stored item with a unique id. (because for some reason you cant make keyless entities).

STOCK POST - Accepts a Json body input from POST request. The app stores the input in memory with 'UseInMemoryDatabase'. Returns with the currently stored items.

CHECKOUT - Not implemented (tried, but couldn't finish)
