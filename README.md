README.md
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metro Medições - Topografia e Agrimensura</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { background-color: #f5f5f5; color: #333; line-height: 1.6; }
        header { background-color: #2c3e50; color: white; padding: 2rem; text-align: center; }
        h1 { font-size: 2.5rem; margin-bottom: 0.5rem; letter-spacing: 2px; }
        .slogan { font-size: 1.2rem; opacity: 0.9; }
        .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; }
        .card { background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); margin-bottom: 2rem; }
        h2 { color: #2c3e50; margin-bottom: 1rem; border-bottom: 2px solid #3498db; padding-bottom: 0.5rem; }
        
        /* Botões */
        .botoes { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; margin-top: 2rem; }
        .botao { display: block; background: linear-gradient(135deg, #2c3e50, #3498db); color: white !important; padding: 2rem 1.5rem; border-radius: 12px; text-align: center; text-decoration: none; font-weight: bold; font-size: 1.1rem; transition: all 0.3s ease; box-shadow: 0 4px 12px rgba(44,62,80,0.2); }
        .botao:hover { transform: translateY(-5px); box-shadow: 0 8px 20px rgba(44,62,80,0.3); text-decoration: none; }
        .botao span { display: block; font-size: 0.9rem; margin-top: 0.5rem; opacity: 0.9; font-weight: normal; }
        
        .servicos { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; margin-top: 1rem; }
        .servico { background: #f8f9fa; padding: 1.5rem; border-radius: 8px; border-left: 4px solid #3498db; }
        
        .contato { background: #2c3e50; color: white; text-align: center; padding: 2rem; border-radius: 10px; }
        .contato p { margin: 0.5rem 0; font-size: 1.1rem; }
        .whatsapp-btn { display: inline-block; background: #25d366; color: white !important; padding: 1rem 2rem; border-radius: 50px; font-weight: bold; font-size: 1.1rem; margin: 1rem 0; text-decoration: none; box-shadow: 0 3px 10px rgba(0,0,0,0.2); }
        .whatsapp-btn:hover { background: #1ebe5d; text-decoration: none; }
        .qrcode-area { text-align: center; margin-top: 2rem; padding: 1.5rem; background: #f0f0f0; border-radius: 10px; }
        .qrcode-img { max-width: 200px; border-radius: 8px; margin-top: 1rem; }
        footer { text-align: center; padding: 2rem; color: #777; font-size: 0.9rem; margin-top: 2rem; }
    </style>
</head>
<body>
    <header>
        <h1>METRO MEDIÇÕES</h1>
        <p class="slogan">Topografia • Agrimensura • Projetos</p>
    </header>

    <div class="container">
        <div class="card">
            <h2>Sobre Nós</h2>
            <p>Somos a Metro Medições, uma empresa especializada em serviços de topografia e agrimensura, com precisão e compromisso com a qualidade em cada projeto. Atendemos Mandaguari e região com profissionalismo e experiência.</p>
        </div>

        <div class="card">
            <h2>Conheça Nosso Trabalho</h2>
            <p>Clique e veja mais detalhes sobre cada etapa do nosso trabalho:</p>
            
            <div class="botoes">
                <a href="campo.html" class="botao">
                    🌲 TRABALHO EM CAMPO
                    <span>Coleta precisa de dados no terreno</span>
                </a>
                <a href="profissionais.html" class="botao">
                    👷 PROFISSIONAIS PREPARADOS
                    <span>Equipe treinada e experiente</span>
                </a>
                <a href="equipamentos.html" class="botao">
                    📡 EQUIPAMENTOS
                    <span>Tecnologia de ponta e precisão</span>
                </a>
            </div>
        </div>

        <div class="card">
            <h2>Nossos Serviços</h2>
            <div class="servicos">
                <div class="servico">
                    <strong>Topografia</strong>
                    <p>Levantamentos planialtimétricos, locação de obras, medições e demarcações.</p>
                </div>
                <div class="servico">
                    <strong>Agrimensura</strong>
                    <p>Demarcação de áreas, divisão de terras, regularização de imóveis e matrículas.</p>
                </div>
                <div class="servico">
                    <strong>Projetos Técnicos</strong>
                    <p>Elaboração, acompanhamento e aprovação de projetos técnicos e topográficos.</p>
                </div>
            </div>
        </div>

        <div class="contato">
            <h2>Entre em Contato</h2>
            <p>📍 Mandaguari - Paraná</p>
            <p>📞 WhatsApp: (44) 99108-9268</p>
            <p>✉️ E-mail: metromedicoes@gmail.com</p>
            
            <a href="https://wa.me/5544991089268" target="_blank" class="whatsapp-btn">
                💬 Falar no WhatsApp
            </a>

            <div class="qrcode-area">
                <p><strong>Escaneie com a câmera do celular:</strong></p>
                <img src="qrcode.png" alt="QR Code WhatsApp" class="qrcode-img">
                <p style="margin-top: 0.5rem; font-size: 0.9rem; color: #555;">Aponte a câmera e fale conosco diretamente</p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2026 Metro Medições — Mandaguari-PR | Todos os direitos reservados</p>
    </footer>
</body>
</html>
