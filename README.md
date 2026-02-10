index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alisson Store</title>
  <style>
    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: radial-gradient(circle at top, #1a1a1a, #0d0d0d);
      color: #eaeaea;
    }
    header {
      background: linear-gradient(135deg, #000, #1f1f1f);
      color: #fff;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 { font-size: 36px; margin: 0; letter-spacing: 1px; }
    header p { opacity: 0.8; margin-top: 10px; }

    .container { padding: 40px 20px; max-width: 1200px; margin: auto; }
    h2 { text-align: center; margin-bottom: 30px; }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .card {
      background: #141414;
      border-radius: 16px;
      padding: 18px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.6);
      transition: transform 0.2s ease-out, box-shadow 0.2s ease-out;
      will-change: transform;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.8);
    }
    
    .card h3 { margin: 10px 0 8px; font-size: 20px; }
    .card p { font-size: 14px; opacity: 0.85; }

    .price {
      color: #2ecc71;
      font-size: 22px;
      font-weight: bold;
      margin-top: 10px;
    }

    .btn {
      display: block;
      margin-top: 15px;
      padding: 12px;
      background: linear-gradient(135deg, #25d366, #1ebe5d);
      color: #fff;
      text-decoration: none;
      border-radius: 10px;
      font-weight: bold;
      text-align: center;
      transition: filter 0.2s;
    }
    .btn:hover { filter: brightness(1.1); }

    footer {
      background: #000;
      color: #aaa;
      text-align: center;
      padding: 25px 15px;
      margin-top: 60px;
      font-size: 14px;
    }
  
    @media (max-width: 768px) {
      header { padding: 30px 15px; }
      header h1 { font-size: 28px; }
      header p { font-size: 14px; }

      .container { padding: 30px 15px; }

      h2 { font-size: 22px; }

      .products {
        grid-template-columns: 1fr;
        gap: 20px;
      }

      .card {
        padding: 16px;
      }

      .card h3 { font-size: 18px; }
      .card p { font-size: 13px; }

      .price { font-size: 20px; }

      .btn {
        padding: 14px;
        font-size: 16px;
      }

      footer {
        font-size: 13px;
        padding: 20px 10px;
      }
    }
  
    .payment-bar {
      position: sticky;
      top: 0;
      z-index: 999;
      background: linear-gradient(135deg, #2ecc71, #27ae60);
      color: #000;
      text-align: center;
      padding: 10px 15px;
      font-weight: bold;
      font-size: 14px;
    }

    @media (max-width: 768px) {
      .payment-bar { font-size: 13px; }
    }
  
    
      
      .hero-text p { font-size: 14px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Alisson Store</h1>
    <p>Venda segura de painéis e menus FiveM • Entrega imediata via Pix</p>
  </header>

  

  <div class="payment-bar">
    💳 Pagamento via <strong>Pix</strong> • Liberação rápida • Suporte via WhatsApp
  </div>

  <div class="container">
    <h2>Escolha seu produto e receba na hora</h2>
    <div class="products">
      <div class="card">
        
        <h3>Painel FiveM</h3>
        <p>Controle total do seu servidor FiveM em poucos cliques. Ideal para quem quer praticidade, organização e agilidade desde o primeiro dia.</p>
        <p class="price">R$ 15,00 <span style="font-size:13px; opacity:0.8;">(acesso imediato)</span></p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Painel%20FiveM%20da%20Alisson%20Store." target="_blank">Comprar agora no WhatsApp</a>
      </div>

      <div class="card">
        
        <h3>Eloi Menu</h3>
        <p>Menu avançado com funções extras para elevar seu nível no FiveM. Mais recursos, mais controle e melhor experiência dentro do servidor.</p>
        <p class="price">R$ 30,00 <span style="font-size:13px; opacity:0.8;">(mais vendido)</span></p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Eloi%20Menu%20da%20Alisson%20Store." target="_blank">Comprar agora no WhatsApp</a>
      </div>

      <div class="card">
        
        <h3>Mod Menu</h3>
        <p>A opção mais completa da loja. Recursos premium, estabilidade e suporte para quem quer o máximo desempenho no FiveM.</p>
        <p class="price">R$ 50,00 <span style="font-size:13px; opacity:0.8;">(premium)</span></p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Mod%20Menu%20da%20Alisson%20Store." target="_blank">Comprar agora no WhatsApp</a>
      </div>
    </div>

  <div class="container" id="termos">
    <h2>Termos de Uso e Aviso Legal</h2>
    <div class="card">
      <p><strong>1. Natureza dos produtos</strong><br>
      Os produtos vendidos na Alisson Store são digitais e entregues conforme descrito no momento da compra.</p>

      <p><strong>2. Entrega</strong><br>
      A entrega é realizada via WhatsApp após a confirmação do pagamento.</p>

      <p><strong>3. Reembolsos</strong><br>
      Por se tratarem de produtos digitais, não realizamos reembolso após a entrega.</p>

      <p><strong>4. Responsabilidade</strong><br>
      O uso dos produtos é de total responsabilidade do comprador. A Alisson Store não se responsabiliza por mau uso ou penalidades aplicadas por terceiros.</p>

      <p><strong>5. Suporte</strong><br>
      O suporte é oferecido conforme descrito em cada produto.</p>

      <p>Ao comprar em nossa loja, você concorda com todos os termos acima.</p>
    </div>
  </div>

  <footer>
    <p>© 2026 Alisson Store - Todos os direitos reservados</p>
    <p style="margin-top:10px;">
      <a href="#termos" style="color:#2ecc71; text-decoration:none; font-weight:bold;">Termos de Uso</a>
    </p>
    <p style="margin-top:12px;">
      <a href="https://discord.gg/ENZPddPKgK" target="_blank" style="color:#7289da; text-decoration:none; font-weight:bold;">💬 Entrar no Discord</a>
    </p>
  </footer>
</body>
</html>
