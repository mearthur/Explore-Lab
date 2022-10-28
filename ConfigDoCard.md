// visa ^4/d{0,15}
// inicia com4 seguido de mais 15 dígitos
4234234234234234234

// mastercard
// inicia com 5, seguido de um dígito entre 1 e 5, seguido de mais 2 dígitos
// ou
// inicia com 22, seguido de dígito entre 2 e 9, seguido de mais 1 digito
// ou
// inicia com 2, seguindo de um digito entre 3 e 7, seguido de mias 2 digitios
// seguido de mais 12 digitos
5353535353535353
2323232323232323
2234344655455664

(^5[1-5]\d{0,2}|^22[2-9]\d|^2[3-7]\d{0,2})\d{0,12}
