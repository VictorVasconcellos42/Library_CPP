# SYNTAX

Como já sou acostumado com a linguagem C (o que eu recomendo fortemente você estudar para caso queira entender melhor muitos conceitos), não existem muitas novidades em relação a essa parte, porem existem alguns pontos que gostaria de comentar.

## USING NAMESPACE

Isso aqui é a novidade! Ele permite que a gente possa dar nomes para objetos e variaveis para qualquer biblioteca, deixando o teu código mais subjetivo em relação a algumas coisas, como por exemplo. Porem, o problema é que você traz todas as funções para o escopo do teu projeto, o que é visto como uma má pratica na comunidade.

**Sem Namespace:**

* std::cout << "Hello World"

**Com Namespace:**

* cout << "Hello World"

## COUT

Metodo da biblioteca padrão para jogar na saida padrão do sitema textos.
(obs: não adiciona uma newline no final)

## Formas de Adicionar newlines

* std::cout << "Victor de Vasconcellos" << endl;

or

* std::cout << "Victor de Vasconcellos\n";
