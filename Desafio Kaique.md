Kotlin

- Apesar do código permitir o cadastro e a exclusão dos empreendimentos, bem como consultar quem cadastrou, 
não há garantias de autenticação, que por sua vez ferem a isonômia do processo e acarretará prejuízos à empresa. 
O problema pode ser resolvido utilizando a Java Bean Validation, utilizando validações pré-definidas ou criando 
validações próprias.

React

- O Front está inserindo dados diretamente no código sem sanitização. Tal problema pode ser resolvido
utilizando dompurify

NodeJS

- O desenvolvedor não filtrou aquilo que o usuário pode digitar, possibilitando ataques de injeção de código.
Isso poderia ter sido evitado criando wordlists, ou seja, listas de filtragem daquilo que o usuário pode digitar 
e deve ser considerado como String. EX: [', /, \, |, &, ;] e outros parametros que podem ser usados como argumentos

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	em uma injeção de código.