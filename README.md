<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Room - Entretenimento Premium</title>
    <style>
        /* Estilização: Preto, Vermelho e Branco */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #000;
            color: #fff;
        }
        
        header {
            background-color: #000;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #ff0000;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            color: #ff0000;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin-top: 15px;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        
        nav ul li a:hover {
            color: #ff0000;
        }
        
        .hero {
            background: url('https://via.placeholder.com/1200x500/000000/ff0000') no-repeat center center;
            background-size: cover;
            height: 500px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: #fff;
            text-shadow: 2px 2px 4px #000;
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin-bottom: 20px;
        }
        
        .btn-contact {
            background-color: #ff0000;
            color: #fff;
            padding: 10px 30px;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            text-decoration: none;
        }
        
        .plans {
            padding: 50px 20px;
            text-align: center;
        }
        
        .plans h2 {
            font-size: 2.5rem;
            margin-bottom: 30px;
            color: #ff0000;
        }
        
        .plan-cards {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        
        .plan {
            background-color: #1a1a1a;
            border: 1px solid #ff0000;
            border-radius: 10px;
            padding: 30px;
            width: 300px;
            text-align: center;
        }
        
        .plan h3 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #fff;
        }
        
        .price {
            font-size: 2rem;
            color: #ff0000;
            margin-bottom: 20px;
        }
        
        .plan ul {
            list-style: none;
            margin-bottom: 20px;
        }
        
        .plan ul li {
            margin: 10px 0;
            color: #ccc;
        }
        
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            border-top: 2px solid #ff0000;
        }
        
        .whatsapp-btn {
            background-color: #25D366;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            margin-top: 10px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">THE ROOM</div>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#plans">Planos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="hero" id="home">
        <h1>THE ROOM</h1>
        <p>Entretenimento de alta qualidade para você.</p>
        <a href="https://wa.me/5547992909565" class="btn-contact">Fale Conosco</a>
    </section>
    
    <section class="plans" id="plans">
        <h2>NOSSOS PLANOS</h2>
        <div class="plan-cards">
            <div class="plan">
                <h3>1 MÊS</h3>
                <div class="price">R$ 25</div>
                <ul>
                    <li>Acesso imediato</li>
                    <li>Suporte 24/7</li>
                    <li>Atualizações constantes</li>
                </ul>
                <a href="https://wa.me/5547992909565" class="whatsapp-btn">ASSINAR</a>
            </div>
            
            <div class="plan">
                <h3>2 MESES</h3>
                <div class="price">R$ 40</div>
                <ul>
                    <li>Economize 20%</li>
                    <li>Suporte prioritário</li>
                    <li>Garantia de qualidade</li>
                </ul>
                <a href="https://wa.me/5547992909565" class="whatsapp-btn">ASSINAR</a>
            </div>
            
            <div class="plan">
                <h3>3 MESES</h3>
                <div class="price">R$ 60</div>
                <ul>
                    <li>Melhor custo-benefício</li>
                    <li>Ativação instantânea</li>
                    <li>+ Conteúdo exclusivo</li>
                </ul>
                <a href="https://wa.me/5547992909565" class="whatsapp-btn">ASSINAR</a>
            </div>
        </div>
    </section>
    
    <footer id="contact">
        <p>Entre em contato via WhatsApp:</p>
        <a href="https://wa.me/5547992909565" class="whatsapp-btn">CHAMAR NO WHATSAPP</a>
        <p>© 2024 THE ROOM. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
