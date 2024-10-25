<section class="contato"></section>
<section class="contato">
  <h2>Fique por dentro das novidades!</h2>
  <p>Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" />
</section>
<section class="contato">
  <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
  <p class="contato__texto"> Atualizações de e-books, novos livros, promoções e outros.</p>
  <input type="email" placeholder="Cadastre seu e-mail" class="contato__email"/>
</section>
@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");
.contato {
  background-color: var(--branco);
  padding: 1em;
}
.contato__titulo,
.contato__texto {
  background: var(--azul-degrade);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.contato__titulo {
  font-size: 18px;
  font-weight: 500;
}
.contato__texto {
  font-weight: 300;
  margin: 1em 0;
}
.contato__email {
  padding: 1em;
  border: 1px solid var(--azul);
  border-radius: 24px;
  width: 90%;
  color: var(--azul);
}
.contato__email::placeholder {
  font-family: var(--fonte-principal);
  color: var(--azul);
  background: url("../img/Email.svg") no-repeat;
  padding-left: 2em;
}
<hr />
<hr />

<footer class="rodapé">

</footer>
<hr />

<footer class="rodapé">
  <h2 class="rodapé__titulo">Grupo Alura</h2>
</footer>
@import url("styles/header.css");
@import url("styles/banner.css");
@import url("styles/carrossel.css");
@import url("styles/topicos.css");
@import url("styles/contato.css");
@import url("styles/rodapé.css");
hr {
  margin: 0;
}
.rodapé {
  background-color: var(--branco);
  padding: 1em;
}
