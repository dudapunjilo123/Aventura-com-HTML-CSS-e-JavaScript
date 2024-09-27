# Aventura-com-HTML-CSS-e-JavaScript
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Em busca da cidade perdida</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="img/cenario-passo0.png" alt="">
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre um vestido perdido. Em uma carta perdida em minha casa existia uma historia falando sobre umvestido muito lindo!</p>
            <button class="btn-proximo" data-proximo="1">RENNER</button(![e8faeaee-df5c-42be-a051-740c47df0279](https://github.com/user-attachments/assets/c517313e-1c06-43ee-9e1f-b3810a46be27)
        )
            <button class="btn-proximo" data-proximo="2">SHEIN</button>(![f5d9f722-2a7a-4985-b3f0-21b76c474354](https://github.com/user-attachments/assets/782da7bd-44d6-4a5d-b3fb-0f49570bd817)
       )
        </div>
        <div class="passo" id="passo-1">
            <p>Você começa sua jornada na RENNER, subindo a lojas no shopin ao amanhecer para encontrar a primeira pista.</p>
            <button class="btn-proximo" data-proximo="3">Procurar a pista no shopin</button>
            <button class="btn-proximo" data-proximo="4">Desistir e voltar para casa</button>
        </div>
        <div class="passo" id="passo-2">
            <p>Em SHEN, você visita os perços espetaculares. Na carta, uma das pistas indica que para localizar a entrada dos peços baixos no istagram ou no feicbuk. Por qual você começa?</p>
            <button class="btn-proximo" data-proximo="5">Investigar o intagrans</button>(![049ee602-24d9-40d9-9aac-380f927a33b9](https://github.com/user-attachments/assets/16380065-9519-4310-90c0-4de38bfc34ff)
     )
            <button class="btn-proximo" data-proximo="6">Explorar o feicbok</button>(![8b25a891-f2df-43fd-aa99-507dd0a504db](https://github.com/user-attachments/assets/63065f50-c5c8-499e-b2a4-0e3920277ddc)
        )
        </div>
        <div class="passo" id="passo-3">
            <p>No topo do isntragran, você encontra uma antiga inscrição apontando que a próxima pista está
                localizada no instragra.</p> (![1e3da160-89f8-4177-91ba-5fc653be0735](https://github.com/user-attachments/assets/b250cabb-3c52-4cac-8f48-290edd38ea1c)
    )
            <button class="btn-proximo" data-proximo="7">Seguir para o istagram</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/cenario-passo4-voltar-casa.png" alt="imagem voltando para casa e desitindo da aventura">
            <p>Você decide que a aventura é grande demais e volta para casa, mas sempre se pergunta o que teria
                encontrado.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>No instagram, você descobre um mapa antigo escondido atrás de um altar, apontando que a próxima
                pista está na casa de sua mãe.</p>
            <button class="btn-proximo" data-proximo="7">Viajar para a casa de sua mãe</button>
        </div>

        <div class="passo" id="passo-6">
            <p>Explorando o fecbok, você encontra uma um cupom, mas ela leva a um beco sem saída.</p>
            <button class="btn-proximo" data-proximo="8">Voltar e explorar o istagram</button>
        </div>(![bb421413-24f7-4bac-b9c4-d2807d56d1c5](https://github.com/user-attachments/assets/bee0db4d-fc4d-48a9-9fdc-e604e63728f6  vs ![1e3da160-89f8-4177-91ba-5fc653be0735](https://github.com/user-attachments/assets/39a34c46-2cd3-4ac8-af2e-43f7c4a6ebc2)
  )
       )

        <div class="passo" id="passo-7">
            <p>EM para a casa de sua mãe, a busca pela cidade perdida se intensifica. Você se depara com um vestindo lindo.</p>(![7233a997-ef25-4715-8892-22d4358b5fb0](https://github.com/user-attachments/assets/e8e59b56-0a02-4b32-a72c-736fff7c9096)
         )
            <button class="btn-proximo" data-proximo="9">Seguir pelo guarda rupa da mamãe</button> (![c7234ba2-6d35-4e4f-a3e0-03f0bca31bc4](https://github.com/user-attachments/assets/b20892ef-ee77-4e06-b197-95329042a46b)
   )
            <button class="btn-proximo" data-proximo="10">Seguir pelas roupas velhas da vovó</button> (![eaf4519f-a537-4778-83f0-23e30661811c](https://github.com/user-attachments/assets/695e5f01-877f-4db3-94ca-03d0f3ee6aab)
  )
        </div>

        <div class="passo" id="passo-8">
            <p>De volta ao intagram, você finalmente encontra o mapa antigo. Agora, para o casa da mãe!</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o casa da mãe</button>
        </div>

        <div class="passo" id="passo-9">
            <p>O pelo guarda rupa da mamãe leva você a uma gaveta escondida com muita poeira revelamdo o vestido mais belo do mundo.</p>
            <button class="btn-proximo" data-proximo="11">Explorar é procurar o vestido perdida</button>
        </div>

        <div class="passo" id="passo-10">
            <p>O pelas roupas velhas da vovó achamos só o vestido de casamento. Apesar de ser belo não se enquada nos meus padroes, não há sinais de outro vestido 
                aqui.</p>(![7cca35c8-1a3b-466f-a1f1-c64ea3ee3ad3](https://github.com/user-attachments/assets/bd8f0a5c-60b4-4f7a-8562-6ab11b893e77)
   )
            <button class="btn-proximo" data-proximo="12">Retornar e tentar  para a casa de sua mãe </button>
        </div>

        <div class="passo" id="passo-11">
            <img src="img/cenario-passo11-(![60607cae-96f2-4174-b111-d0462712dcb8](https://github.com/user-attachments/assets/e23e6d01-8ef6-46f1-8ee7-d56a09c94666)
    )vestido bonito.png" alt="encontrando um vestido lindo perdida  para o casa da mãe">
            <p>Dentro da casa da mãe, você descobre vestido maravilhosos, que nunca tinha visto antes nesse
                lugar</p>
        </div>

        <div class="passo" id="passo-12">
            <p>Retornando e escolhendo opelo guarda rupa da mamãe, você finalmente encontrao vestido mais belo do mundo
                que levam ao vestido maravilhoso p.</p>
            <button class="btn-proximo" data-proximo="11">Explorar o guarda roupa de mãe</button> (![c7234ba2-6d35-4e4f-a3e0-03f0bca31bc4](https://github.com/user-attachments/assets/0a9f4b04-b4f2-46a7-9b5f-c4b0ed5783dd)
 )
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
const avanca = document.querySelectorAll('.btn-proximo');

avanca.forEach(button => {
    button.addEventListener('click', function(){
        const atual = document.querySelector('.ativo');
        const proximoPasso = 'passo-' + this.getAttribute('data-proximo');

        atual.classList.remove('ativo');
        document.getElementById(proximoPasso).classList.add('ativo');
    })
})
body {
    background-color: #1D4221;
    color: white;
    font-family: "Bai Jamjuree", sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 700px;
    margin: 0;
}

button {
    background-color: #64A712;
    color: white;
    font-family: "Bai Jamjuree", sans-serif;
}

.passo {
    display: none;
}

.passo.ativo {
    display:block;
}

main {
    text-align: center;
    max-width: 90%;
}

img {
    max-width: 90%;
}
imagens ultilizads na historia
![7cca35c8-1a3b-466f-a1f1-c64ea3ee3ad3](https://github.com/user-attachments/assets/d5ae1e61-1c73-46c2-99e6-cc57ff201e74)
![60607cae-96f2-4174-b111-d0462712dcb8](https://github.com/user-attachments/assets/f43b6c28-3ae3-4d97-a6c2-976eef59e3a9)
![eaf4519f-a537-4778-83f0-23e30661811c](https://github.com/user-attachments/assets/22b29df5-c69c-4cdb-a1da-79a4b13ce140)
![c7234ba2-6d35-4e4f-a3e0-03f0bca31bc4](https://github.com/user-attachments/assets/27a62e69-aed5-4cd8-92b9-350f202548a6)
![7233a997-ef25-4715-8892-22d4358b5fb0](https://github.com/user-attachments/assets/637fce67-26ba-49b6-b3f3-0ddfcb219a0c)
![bb421413-24f7-4bac-b9c4-d2807d56d1c5](https://github.com/user-attachments/assets/79275acc-3ed9-4f81-ab74-0737264f993b)
![1e3da160-89f8-4177-91ba-5fc653be0735](https://github.com/user-attachments/assets/37b57c5a-ac48-4aeb-aef9-8e04ff079c26)
![f5d9f722-2a7a-4985-b3f0-21b76c474354](https://github.com/user-attachments/assets/ca341f7f-e5f3-49fd-9534-0541e11bb623)
![e8faeaee-df5c-42be-a051-740c47df0279](https://github.com/user-attachments/assets/3555f2ff-edf2-4455-8ffe-ca8f2d58bbaa)

obrigado por ver s minhs historia
![2d528806-1492-4a0d-b763-ce3e611dc189](https://github.com/user-attachments/assets/7ba9f802-4e40-464f-93d9-84d16e0a6318)
