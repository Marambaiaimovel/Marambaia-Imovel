<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marambaia Imóvel</title>
  <!-- Importando fontes do Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link 
    href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Open+Sans:wght@400;600&display=swap" 
    rel="stylesheet">
  <!-- Link para o arquivo de estilos -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <div class="container-header">
      <!-- Substitua "logo.png" pelo nome correto do seu arquivo de logotipo -->
      <img src="logo.png" alt="Logotipo Marambaia Imóvel" class="logo">
      <nav>
        <ul>
          <li><a href="#home">Início</a></li>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#imoveis">Imóveis</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Seção de Boas-Vindas -->
  <section id="home" class="hero">
    <div class="hero-overlay">
      <h2>Bem-vindo à Marambaia Imóvel</h2>
      <p>Uma imobiliária que preza pelo bom atendimento e entende a necessidade do cliente comprador.</p>
      <a href="#imoveis" class="btn-cta">Ver Imóveis</a>
    </div>
  </section>

  <!-- Sobre Nós -->
  <section id="sobre">
    <div class="container">
      <h2>Sobre Nós</h2>
      <p>
        Na <strong>Marambaia Imóvel</strong>, nosso objetivo é oferecer um atendimento 
        <em>personalizado</em> e encontrar o imóvel ideal que atenda às suas necessidades e preferências. 
        Nossa equipe está pronta para auxiliá-lo em cada etapa da sua jornada.
      </p>
    </div>
  </section>

  <!-- Imóveis Disponíveis -->
  <section id="imoveis">
    <div class="container">
      <h2>Imóveis Disponíveis</h2>
      <div class="imovel">
        <img src="imovel1.jpg" alt="Imagem do imóvel">
        <h3>Casa na Praia</h3>
        <p>Descrição do imóvel, localização e outras informações relevantes.</p>
      </div>
      <!-- Adicione outros imóveis conforme necessário -->
    </div>
  </section>

  <!-- Contato -->
  <section id="contato">
    <div class="container">
      <h2>Contato</h2>
      <form action="envia_contato.php" method="post">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem" required></textarea>
        
        <button type="submit">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Marambaia Imóvel. Todos os direitos reservados.</p>
    </div>
  </footer>
</body>
</html>
    
