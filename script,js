function Livro(titulo, autor, anoDePublicacao) {
    this.titulo = titulo;
    this.autor = autor;
    this.anoDePublicacao = anoDePublicacao;

    this.getInfo = function() {
        return this.titulo + " foi escrito por " + this.autor + " e publicado em " + this.anoDePublicacao + ".";
    }
}

// Criando um novo livro
var livro1 = new Livro("O Senhor dos Anéis", "J.R.R. Tolkien", 1954);

// Invocando o método getInfo
console.log(livro1.getInfo());

// Verificando se uma propriedade existe
console.log("titulo" in livro1);  // retorna true

// Iterando sobre todas as propriedades
for (var prop in livro1) {
    console.log(prop + ": " + livro1[prop]);
}
