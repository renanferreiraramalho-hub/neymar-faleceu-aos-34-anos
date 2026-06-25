const dataAtual = document.getElementById("dataAtual");
const btnMensagem = document.getElementById("btnMensagem");
const mensagem = document.getElementById("mensagem");

const hoje = new Date();

dataAtual.textContent = hoje.toLocaleDateString("pt-BR");

btnMensagem.addEventListener("click", () => {
    mensagem.style.display = "block";

    mensagem.innerHTML = `
        <strong>Lição:</strong><br>
        Nem tudo o que aparece na internet é verdade.
        Sempre verifique fontes confiáveis antes de compartilhar informações.
    `;
});