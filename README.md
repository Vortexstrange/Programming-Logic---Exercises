function exibirTextoNaTela(tag, texto) {
    let campo = document.querySelector(tag)
    campo.innerHTML = texto;
}

exibirTextoNaTela('h1', 'Secret Game');
exibirTextoNaTela('p', 'Welcome to the secret Game! Guess the secred number between 1 and 340.');

function verificarChute() {
    console.log('o botão foi clicado')
}
