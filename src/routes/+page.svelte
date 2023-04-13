<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benim Kişisel Web Sitem</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#anasayfa">Anasayfa</a></li>
        <li><a href="#hakkimda">Hakkımda</a></li>
        <li><a href="#projelerim">Projelerim</a></li>
        <li><a href="#iletisim">İletişim</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="anasayfa">
      <h1>Benim Kişisel Web Sitem</h1>
      <p>Merhaba, benim adım Ozan ve bu benim kişisel web sitem. Sitemdeki içerikler hakkında daha fazla bilgi edinmek için aşağıdaki menüyü kullanabilirsiniz.</p>
    </section>
    <section id="hakkimda">
      <h2>Hakkımda</h2>
      <p>Ben Ozan, bir yazılım geliştiricisiyim. Uzun yıllardır bu alanda çalışıyorum ve birçok projeye imza attım. Sitemdeki projelerim bölümünden daha fazla bilgi edinebilirsiniz.</p>
    </section>
    <section id="projelerim">
      <h2>Projelerim</h2>
      <ul>
        <li>
          <h3>Proje 1</h3>
          <p>Açıklama</p>
          <a href="#">Daha fazla bilgi</a>
        </li>
        <li>
          <h3>Proje 2</h3>
          <p>Açıklama</p>
          <a href="#">Daha fazla bilgi</a>
        </li>
      </ul>
    </section>
    <section id="iletisim">
      <h2>İletişim</h2>
      <form>
        <label for="name">Adınız:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">E-posta adresiniz:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Mesajınız:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Gönder</button>
      </form>
    </section>
  </main>
</body>
</html>

