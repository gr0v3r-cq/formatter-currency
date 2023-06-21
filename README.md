# formatter-currency

formatter.format(2342)
'$2,342.00'

const formatter = new Intl.NumberFormat('es-MX', {style:"currency", currency:"MXN"})

const formatter = new Intl.NumberFormat('es-BO', {style: "currency", currency: "BOB"});

const amount = 1000;
const formattedAmount = formatter.format(amount);
console.log(formattedAmount);

formatter.format(12)
'$12.00'
