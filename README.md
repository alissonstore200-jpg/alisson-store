index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Alisson Store</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f5f5f5; }
    header { background: #111; color: #fff; padding: 20px; text-align: center; }
    .container { padding: 20px; max-width: 1100px; margin: auto; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: #fff; border-radius: 10px; padding: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
    .card img { width: 100%; border-radius: 10px; }
    .card h3 { margin: 10px 0 5px; }
    .price { color: #2ecc71; font-size: 18px; font-weight: bold; }
    .btn { display: inline-block; margin-top: 10px; padding: 10px 15px; background: #25d366; color: #fff; text-decoration: none; border-radius: 5px; }
    footer { background: #111; color: #fff; text-align: center; padding: 15px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <h1>Alisson Store</h1>
    <p>Sua loja online simples e direta</p>
  </header>

  <div class="container">
    <h2>Produtos em destaque</h2>
    <div class="products">
      <div class="card">
        <img src="https://via.placeholder.com/300" alt="Painel FiveM" />
        <h3>Painel FiveM</h3>
        <p>Painel administrativo completo para servidores FiveM. Interface simples, funções essenciais e acesso rápido para gerenciar seu servidor com eficiência.</p>
        <p class="price">R$ 15,00</p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Painel%20FiveM%20da%20Alisson%20Store." target="_blank">Comprar no WhatsApp</a>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/300" alt="Eloi Menu" />
        <h3>Eloi Menu</h3>
        <p>Menu avançado para FiveM com diversas funções exclusivas. Ideal para quem busca mais controle, praticidade e desempenho dentro do servidor.</p>
        <p class="price">R$ 30,00</p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Eloi%20Menu%20da%20Alisson%20Store." target="_blank">Comprar no WhatsApp</a>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/300" alt="Mod Menu" />
        <h3>Mod Menu</h3>
        <p>Mod Menu completo e poderoso para FiveM. Inclui recursos premium, estabilidade e suporte, indicado para usuários que querem o máximo de funcionalidades.</p>
        <p class="price">R$ 50,00</p>
        <a class="btn" href="https://wa.me/5577999174877?text=Olá!%20Tenho%20interesse%20no%20produto%20Mod%20Menu%20da%20Alisson%20Store." target="_blank">Comprar no WhatsApp</a>
      </div>
    </div>
  </div>

  <footer>
    <p>© 2026 Alisson Store - Todos os direitos reservados</p>
  </footer>
</body>
</html>
