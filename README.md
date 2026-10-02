desafio-colaborativo-git.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SobreFilmes</title>
    <a href="#" class="logo">SobreFilmes</a>
        <link rel="stylesheet" href="css/style.css">
</header>

<body>

    <header>

        <nav class="navbar">
            <ul>
                <li><a href="#map">Mapa</a></li>
                <li><a href="#gallery">Galeria</a></li>
                <li><a href="#contact">Contato</a></li>
                <li><a href="#indicacao">Avaliação</a></li>
                <li><a href="#about">Sobre</a></li>
            </ul>
        </nav>
    </header>

    <main>

        <section id="hero">
            <h1 style="color: white; text-shadow: 2px 2px 4px black;">Tudo sobre filmes Brasileiros!</h1> 
            <br>
            <p style="text-align: center; color: white; text-shadow: 1px 1px 3px black;">
                Melhores indicações de filmes atualizada. 
            </p>
        </section>

        <section id="about">
            <h1>Sobre o o blog</h1>

            <p>
                As melhores indicações de filmes brasileiros. 🐾
            </p>

            <p>
                O cinema brasileiro é repleto de histórias marcantes, personagens cativantes e diferentes formas de retratar a nossa cultura e realidade. Para quem quer conhecer ou revisitar grandes produções nacionais, vale conferir filmes como Central do Brasil, Cidade de Deus, O Auto da Compadecida, Que Horas Ela Volta? e Bacurau
            </p>

            <p>
                Cada um, à sua maneira, apresenta diferentes aspectos da sociedade brasileira, explorando temas como família, desigualdade, identidade, amizade e resistência. São ótimas opções para quem busca filmes nacionais capazes de emocionar, provocar reflexões e, ao mesmo tempo, valorizar o talento do cinema brasileiro.
            </p>

           
        </section>

        <section id="galery" style="background-color: lightgray;">
    <h2>Galeria</h2>

    <div class="filme">
        <img src="img/film1.jpg" alt="Tropa de Elite">
        <p>Tropa de Elite - 2007</p>
    </div>

    <div class="filme">
        <img src="img/film2.jpg" alt="O Auto da Compadecida">
        <p>O Auto da Compadecida - 2000</p>
    </div>

    <div class="filme">
        <img src="img/film3.jpg" alt="Última Parada 174">
        <p>Última Parada 174 - 2008</p>
    </div>

    <div class="filme">
        <img src="img/film4.jpg" alt="Central do Brasil">
        <p>Central do Brasil - 1998</p>
    </div>

    <div class="filme">
        <img src="img/film5.jpg" alt="Cidade de Deus">
        <p>Cidade de Deus - 2002</p>
    </div>
</section>

        <section id="map">
            <h2>Mapa</h2>
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3838.8066233458267!2d-47.902056024152635!3d-15.81414732344331!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x935a3ac9011178f5%3A0x26b9b78c743de987!2sCine%20Bras%C3%ADlia!5e0!3m2!1spt-BR!2sbr!4v1789513324123!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin">
                style="border:0;"
            </iframe>
        </section>

        <section id="contact">
            <h2>Contato</h2>
            <p> Para contato enviar e-mail para nossa gerência; </p>
             <a href="mailto:isaquealuno@gmail.com">
                isaquealuno@gmail.com
            </a>
            
        </section>
        <section id="indicacao">
            <h2>Avaliação</h2>

    <p>Para dicas e sugestões favor preencher o formulário:</p>

    <form action="" method="get">

        <label>
            Nome
            <input type="text" name="nome">
        </label>
        <br>

        <label>
            E-mail
            <input type="email" name="email">
        </label>
        <br>

        <label>
            Idade
            <input type="number" name="idade" min="1" max="120">
        </label>
        <br>

        <button type="submit">Enviar</button>
        <label>mensagem
            <textarea name="mensagem" rows="s"
             cols="30"></textarea>
        </label>

    </form>
</section>

    </main>

    <footer>
        <p>
            &copy; 2026 Todos os direitos reservados.
            Desenvolvido por:
            <a href="mailto:arthurpereira47al@gmail.com">
                Arthur Pereira
                RGM: 4889557-1
            </a> <br>
            <a href="mailto:caiomendesteam@gmail.com">
                Caio Mendes Dias Carneiro 
                RGM: 4988460-3
            </a>
        </p>
    </footer>

</body>
</html>
