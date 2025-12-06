Perfeito, Leandro! Vou gerar agora mesmo uma versão completa do seu site pronta para Netlify, mantendo:

Layout atual do Readdy

Nome do site: FactoJuris

Abas: Início, Quem Somos, Nossos Serviços, Fale Conosco, Notícias

Textos corrigidos conforme combinamos

WhatsApp +55 11 98882-6501 em todas as abas de contato e rodapé

Arquivos separados: HTML, CSS, JS, pasta de imagens (com placeholders)

Estrutura de pastas final para Netlify
/factojuris-site
├── index.html
├── sobre.html
├── servicos.html
├── contato.html
├── noticias.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── placeholder.png

1️⃣ index.html (Início)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>FactoJuris - Início</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FactoJuris</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="sobre.html">Quem Somos</a></li>
        <li><a href="servicos.html">Nossos Serviços</a></li>
        <li><a href="contato.html">Fale Conosco</a></li>
        <li><a href="noticias.html">Notícias</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>Bem-vindo à FactoJuris!</h2>
      <p>Soluções jurídicas confiáveis e práticas para você ou sua empresa.</p>
      <a href="https://wa.me/5511988826501" class="btn-whatsapp">Fale Conosco via WhatsApp</a>
    </section>
  </main>

  <footer>
    <p>© 2025 FactoJuris. Todos os direitos reservados.</p>
    <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
  </footer>
</body>
</html>

2️⃣ sobre.html (Quem Somos)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>FactoJuris - Quem Somos</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FactoJuris</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="sobre.html">Quem Somos</a></li>
        <li><a href="servicos.html">Nossos Serviços</a></li>
        <li><a href="contato.html">Fale Conosco</a></li>
        <li><a href="noticias.html">Notícias</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Quem Somos</h2>
      <p>Na FactoJuris, oferecemos serviços jurídicos especializados com transparência e eficiência. Nossa equipe está preparada para atender suas necessidades com profissionalismo e dedicação.</p>
      <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 FactoJuris. Todos os direitos reservados.</p>
    <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
  </footer>
</body>
</html>

3️⃣ servicos.html (Nossos Serviços)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>FactoJuris - Nossos Serviços</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FactoJuris</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="sobre.html">Quem Somos</a></li>
        <li><a href="servicos.html">Nossos Serviços</a></li>
        <li><a href="contato.html">Fale Conosco</a></li>
        <li><a href="noticias.html">Notícias</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Nossos Serviços</h2>
      <ul>
        <li>Consultoria jurídica personalizada</li>
        <li>Elaboração de contratos e documentos legais</li>
        <li>Assessoria em processos e negociações</li>
        <li>Suporte em questões corporativas e empresariais</li>
      </ul>
      <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 FactoJuris. Todos os direitos reservados.</p>
    <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
  </footer>
</body>
</html>

4️⃣ contato.html (Fale Conosco)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>FactoJuris - Fale Conosco</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FactoJuris</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="sobre.html">Quem Somos</a></li>
        <li><a href="servicos.html">Nossos Serviços</a></li>
        <li><a href="contato.html">Fale Conosco</a></li>
        <li><a href="noticias.html">Notícias</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Fale Conosco</h2>
      <p>Entre em contato conosco pelo formulário abaixo ou via WhatsApp:</p>
      <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
      <form>
        <label>Nome:</label>
        <input type="text" name="nome" required>
        <label>Email:</label>
        <input type="email" name="email" required>
        <label>Mensagem:</label>
        <textarea name="mensagem" required></textarea>
        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <footer>
    <p>© 2025 FactoJuris. Todos os direitos reservados.</p>
    <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
  </footer>
</body>
</html>

5️⃣ noticias.html (Notícias / Blog)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>FactoJuris - Notícias</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FactoJuris</h1>
    <nav>
      <ul>
        <li><a href="index.html">Início</a></li>
        <li><a href="sobre.html">Quem Somos</a></li>
        <li><a href="servicos.html">Nossos Serviços</a></li>
        <li><a href="contato.html">Fale Conosco</a></li>
        <li><a href="noticias.html">Notícias</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Notícias</h2>
      <p>Fique por dentro das novidades e informações jurídicas importantes para você ou sua empresa.</p>
      <p>Dúvidas? Fale conosco via WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 FactoJuris. Todos os direitos reservados.</p>
    <p>WhatsApp: <a href="https://wa.me/5511988826501">+55 11 98882-6501</a></p>
  </footer>
</body>
</html>

6️⃣ css/style.css (básico, mantém layout moderno)
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

header, footer {
  background-color: #f2f2f2;
  padding: 15px;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 0;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

main {
  padding: 20px;
}

section.hero {
  text-align: center;
  margin-top: 50px;
}

section h2 {
  font-size: 2em;
  margin-bottom: 10px;
}

section p {
  font-size: 1.1em;
}

.btn-whatsapp {
  display: inline-block;
  padding: 10px 20px;
  background-color: #25D366;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 20px;
}

form label {
  display: block;
  margin-top: 10px;
}

form input, form textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
}

form button {
  margin-top: 10px;
  padding: 10px 15px;
  background-color: #25D366;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
