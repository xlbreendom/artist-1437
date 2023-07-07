<!DOCTYPE html>
<html>
<head>
  <title>My arts website</title>
  <style>
    /* Estilos CSS */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #FFFFFF;
    }
    header {
      background-color: #add8e6;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #b0cddf;
      color: #fff;
      padding: 10px;
    }
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
    }
    nav ul li {
      display: inline;
    }
    nav ul li a {
      color: #fff;
      text-decoration: none;
      padding: 10px;
    }
    main {
      padding: 20px;
      color: #000;
    }
    .gallery {
      display: flex;
      justify-content: space-between;
    }
    .gallery img {
      width: 300px;
      height: auto;
    }
    footer {
      background-color: #e66b00;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h1>My arts website</h1>
  </header>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Galery</a></li>
      <li><a href="#">about</a></li>
      <li><a href="#">Contacts</a></li>
    </ul>
  </nav>
  <main>
    <h2 style="color: blue;">Art Gallery</h2>
    <p>Here you will find amazing artwork created by me.</p>
    <h3 style="color: black;">artist1437</h3>
    <div class="gallery">
      <img src="artist.jpeg" alt="my art">
    </div>
  </main>
  <footer>
    <p>&copy; 2023 BRENDOM. Todos os direitos reservados.</p>
  </footer>
</body>
</html>

