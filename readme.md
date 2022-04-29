# Recriando a Interface do Netflix

Como parte do bootcamp Carrefour Web Developer, montamos uma versão front-end da página do Netflix e fomos encorajados a fazer customizações e compartilhar o resultado.

[Página hospedada](https://iandealmeida.github.io/my-netflix-clone/)

Decidi incluir uma simulação de uma funcionalidade que eu sempre quis que o Netflix implementasse. Deixar o usuário escolher o filme/série por país.
![Página Filmes](https://iandealmeida.github.io/my-netflix-clone/img/index.gif)

Minha versão começa na página "Filmes" e inclui um botão para o usuário escolher dois tipos de filtro:
- Gênero
- País
![enter image description here](https://iandealmeida.github.io/my-netflix-clone/img/genero_pais.gif)


Cada uma dessas opções leva a uma página diferente, com filmes do gênero ou país selecionado.

Não foi mostrado no curso como inserir botões, mas consegui fazer isso usando a mesma lógica que o instrutor Felipe Aguiar usou para incluir o carrossel.

Busquei um botão feito com Bootstrap + JaaScript no site [W3Schools](https://www.w3schools.com/bootstrap5/bootstrap_dropdowns.php).

Adicionei o link para o *stylesheet* em css e o *script* em JS, mas logo vi que precisaria baixar esses códigos e salvá-los nas pastas *style* e *js* para poder customizar o botão, que era bem diferente.

Também usando a lógica aplicada no curso, localizei as propriedades e valores a serem modificados e consegui deixar o botão bem parecido com o da Netflix.

Precisei modificar o nome de algumas classes para não gerar conflito com o *stylesheet* e *script* JS que importei.

O desafio foi orientado por [Felipe Aguiar](https://github.com/felipeAguiarCode).
