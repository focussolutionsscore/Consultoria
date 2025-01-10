<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Focus Solutions - Aumento de Score e Limpeza de Nome</title>
    <!-- Link para a biblioteca Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f7fa; /* Azul claro para o fundo */
        }
        header {
            background-color: #0056b3; /* Azul escuro */
            color: white;
            padding: 40px;
            text-align: center;
            border-bottom: 5px solid #007bff; /* Azul mais claro para a borda */
        }
        header h1 {
            font-size: 36px;
            margin: 0;
        }
        header p {
            font-size: 18px;
            margin-top: 10px;
        }
        section {
            padding: 40px 20px;
        }
        .card {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            padding: 20px;
            max-width: 900px;
            text-align: center;
        }
        .card h2 {
            color: #0056b3; /* Azul escuro para os títulos */
            font-size: 28px;
        }
        .btn, .whatsapp-btn {
            display: inline-block;
            background-color: #0056b3; /* Azul escuro */
            color: white;
            padding: 15px 25px;
            text-align: center;
            border-radius: 8px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            margin: 15px 0;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .btn:hover, .whatsapp-btn:hover {
            background-color: #007bff; /* Azul mais claro ao passar o mouse */
        }
        .whatsapp-btn {
            background-color: #25D366; /* Cor do WhatsApp */
        }
        .whatsapp-btn:hover {
            background-color: #20b557; /* Cor do WhatsApp mais escura */
        }
        footer {
            background-color: #0056b3; /* Azul escuro */
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
            font-size: 16px;
        }
        footer p {
            margin: 0;
        }
        #precos {
            background-color: #f1f5f9;
            padding: 20px;
            border-radius: 12px;
        }
        #precos p {
            font-size: 20px;
            font-weight: bold;
            color: #0056b3; /* Azul escuro */
        }
        #imagem-score, #imagem-limpa-nome {
            max-width: 70%; /* Reduzindo a imagem para 70% do tamanho original */
            height: auto;
            margin: 20px auto;
            display: block; /* Centralizando a imagem */
        }

        /* Responsividade */
        @media (max-width: 768px) {
            /* Para dispositivos menores que 768px (como tablets) */
            header h1 {
                font-size: 28px;
            }
            header p {
                font-size: 16px;
            }
            .card {
                padding: 15px;
            }
            .card h2 {
                font-size: 24px;
            }
            .btn, .whatsapp-btn {
                font-size: 16px;
                padding: 12px 20px;
            }
            #imagem-score, #imagem-limpa-nome {
                max-width: 90%; /* Para telas menores, aumentar a largura da imagem */
            }
        }

        @media (max-width: 480px) {
            /* Para dispositivos menores que 480px (como smartphones) */
            header h1 {
                font-size: 24px;
            }
            header p {
                font-size: 14px;
            }
            .card h2 {
                font-size: 20px;
            }
            .btn, .whatsapp-btn {
                font-size: 14px;
                padding: 10px 15px;
            }
            #imagem-score, #imagem-limpa-nome {
                max-width: 100%; /* A imagem ocupa 100% da largura da tela */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Focus Solutions</h1>
        <p>Soluções Inteligentes para Melhorar sua Vida Financeira</p>
    </header>

    <section>
        <div class="card">
            <h2>Aumento de Score</h2>
            <p>Melhore seu score de crédito com a ajuda de especialistas. Oferecemos análise personalizada e estratégias comprovadas para aumentar sua pontuação e abrir novas portas para o seu futuro financeiro.</p>
            <img src="imagem%20score.jpg" alt="Imagem de aumento de score" id="imagem-score">
            <a href="https://wa.me/5511977859676?text=Olá,%20tenho%20interesse%20em%20aumentar%20meu%20score!" class="btn">Quero Aumentar Meu Score</a>
        </div>

        <div class="card">
            <h2>Limpeza de Nome</h2>
            <p>Está com o nome negativado? A Focus Solutions ajuda você a negociar dívidas e limpar seu nome de forma prática e rápida. Volte a ter credibilidade no mercado!</p>
            <img src="limpa nome.jpg" alt="Imagem de limpeza de nome" id="imagem-limpa-nome">
            <a href="https://wa.me/5511977859676?text=Olá,%20tenho%20interesse%20em%20limpar%20meu%20nome!" class="btn">Quero Limpar Meu Nome</a>
        </div>
    </section>

    <section id="contato">
        <div class="card">
            <h2>Entre em Contato</h2>
            <p>Fale diretamente com nossa equipe pelo WhatsApp para tirar dúvidas ou contratar nossos serviços.</p>
            <a 
                href="https://wa.me/5511977859676?text=Olá,%20tenho%20interesse%20nos%20serviços%20da%20Focus%20Solutions!" 
                target="_blank" 
                class="whatsapp-btn"
            >
                <i class="fab fa-whatsapp"></i> Entre em Contato pelo WhatsApp
            </a>
        </div>
    </section>

</body>
</html>
