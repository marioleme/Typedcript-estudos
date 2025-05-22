![Typescript: orientação a objetos](https://imgur.com/9399vxd.png)

# Typescript: orientação a objetos

Este projeto faz parte da escola Front-end e tem como objetivo ensinar a transformar trechos de código originalmente cosntruídos em programação funcional para programação orientada a objetos, destacando as diferenças entre os dois paradigmas.

## Funcionalidades do projeto

O projeto contará com o desenvolvimento de:

- Classe conta e armazenador;
- Atributos e construtor de conta;
- Modificadores de acesso;
- Métodos estáticos;
- Herança de classes;
- Decorators de validação.


## curso Typescript Alura

##  Tipos Primitivos
let valor: number = 3000;
let nome: string = "";
let isPago: boolean = false;
let qualquer: any = "";
qualquer = 22;

## Arrays
const lista: number[] = [];
lista.push(13, 22.5, 22, 89, 1.58);

## Tipos Personalizados (Type Alias)
type Transacao = {
    tipoTransacao: TipoTransacao;
    data: Date;
    valor: number;
}

## Enum
enum TipoTransacao {
    DEPOSITO = "Depósito",
    TRANSFERENCIA = "Transferência",
    PAGAMENTO_BOLETO = "Pagamento de Boleto"
}

const novaTransacao: Transacao = {
    tipoTransacao: TipoTransacao.PAGAMENTO_BOLETO,
    data: new Date(),
    valor: 0
}
