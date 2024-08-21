interface Produto {
    nome: string;
    preco: number;
    categoria: string;
}

type FormaPagamento = 'dinheiro' | 'cartão' | 'pix';
function processarCompra(produto: Produto, formaPagamento: FormaPagamento): string {
    return `Você comprou o produto "${produto.nome}" da categoria "${produto.categoria}" por R$${produto.preco.toFixed(2)}. Forma de pagamento: ${formaPagamento}.`;
}

const produtoExemplo: Produto = {
    nome: 'Camiseta',
    preco: 49.90,
    categoria: 'Vestuário'
};

const formaPagamentoExemplo: FormaPagamento = 'cartão';

console.log(processarCompra(produtoExemplo, formaPagamentoExemplo));
