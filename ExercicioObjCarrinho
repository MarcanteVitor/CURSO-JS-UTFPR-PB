const carrinho = {
  totalItens: 0,
  produtos: []
};

function adicionarProduto(nome, preco) {
  const produto = {
    nome: nome,
    preco: preco
  };

  carrinho.produtos.push(produto);
  carrinho.totalItens++;
}


adicionarProduto("Camiseta", 29.90);
adicionarProduto("Calça Jeans", 99.90);
adicionarProduto("Tênis", 149.90);

console.log('Total itenhs carrinho ' + carrinho.totalItens); 




for (let i = 0; i < carrinho.produtos.length; i ++) {
	console.log("Nome: " + carrinho.produtos[i].nome + "  Valor: " +  carrinho.produtos[i].preco)
}
