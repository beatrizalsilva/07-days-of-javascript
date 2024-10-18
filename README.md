# 7 Days of Code - Lógica de Programação com Javascript

## Dia 1
#### Exercício
Hoje iremos começar de uma forma tranquila, porém com um aprendizado bastante importante para seguirmos pros próximos dias de desafios!

Caso você ainda não tenha passado por isso, é muito comum ao utilizarmos Javascript termos problemas com os tipos de variáveis na hora de atribuirmos novos valores e os comparar

Sendo assim, você irá **reescrever o código abaixo de maneira que ele esteja imprimindo as informações de maneira correta, que faça sentido e sem erros**:

```javascript
let numeroUm = 1
let stringUm = '1'
let numeroTrinta = 30
let stringTrinta = '30'
let numeroDez = 10
let stringDez = '10'

if (numeroUm = stringUm) {
  console.log('As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroUm e stringUm não tem o mesmo valor')
}

if (numeroTrinta == stringTrinta) {
  console.log('As variáveis numeroTrinta e stringTrinta tem o mesmo valor e mesmo tipo')
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo')
}

if (numeroDez === stringDez) {
  console.log('As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroDez e stringDez não tem o mesmo valor')
}
```

#### Dica
**Você pode utilizar o próprio navegador para executar o seu programa** caso ainda não tenha familiaridade com editores de código, como o Visual Studio Code
Para isso, basta você clicar com o botão direito do mouse em qualquer página, ir em `console` e digitar o seu código, bem simples

Caso queira **mudar os nomes das variáveis e valores**, sinta-se a vontade, porém jamais imprima algo que não seja verdadeiro, hein!

## Dia 2
#### Exercício
Sabe quando você se cadastra em um site e logo em seguida, quando você faz o seu login, ele já te chama pelo seu próprio nome? No desafio de hoje iremos fazer isso!

Você precisará desenvolver um programinha que simulará um desses sites e **ele pedirá para a pessoa que for utilizá-lo responder 3 perguntas**:
`Qual o seu nome?`
`Quantos anos você tem?`
`Qual linguagem de programação você está estudando?`

E, claramente, a pessoa que estiver usando o programa deverá **responder cada uma delas a medida que forem sendo feitas**

No final, o programa irá **imprimir a mensagem:**

`"Olá X, você tem X anos e já está aprendendo X!"`

Em que cada `X` é uma das respostas dadas pela pessoa

#### Dica
Você poderá **adicionar quantas perguntas quiser**, inclusive adicionando as respostas da pessoa na mensagem que será impressa.

Para **imprimir e receber valores**, você pode tanto usar `console.log`, `prompt` e `alert`, quanto usar HTML e CSS caso já tenha conhecimento dessas duas tecnologias.

## Dia 3
#### Exercício
Você alguma vez já jogou algum jogo onde ele te desse mais de uma escolha e, dependendo da que você escolhesse, o destino da personagem seria totalmente diferente?

Vamos fazer um um exemplo com Javascript!

Seu desafio de hoje é **criar os destinos possíveis de um jogo**, em que a pessoa jogador consiga escolher:

1. No **início** de seus estudos, onde poderá escolher entre **seguir para área de front-end** ou **seguir para a área de back-end**

2. No **meio**, onde caso esteja na área de **front-end**, ela poderá **seguir aprendendo React** ou **seguir aprendendo Vue** e, caso esteja na área de **back-end**, poderá **seguir aprendendo C#** ou **seguir aprendendo Java**

3. No **fim**, onde, independente de suas escolhas anteriores, ela poderá escolher entre **seguir se especializando na área escolhida** ou **seguir se desenvolvendo para se tornar fullstack**

O importante é que a pessoa que jogar possa sempre **escolher qual decisão tomar** para conseguir aprender e se desenvolver na área de programação

#### Dica
Já da pra ter uma ideia de como fazer toda essa historinha acontecer né? Principalmente lembrando como utilizamos as **estruturas condicionais em Javascript**!

Caso você ainda não saiba como **imprimir e receber valores** nas páginas web com HTML e CSS, você poderá usar `console.log`, `prompt` e `alert` para desenvolver o seu jogo

Lembre-se que você pode sempre **personalizar** o jogo da forma que quiser!