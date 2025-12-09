# a-hacker[index.html](https://github.com/user-attachments/files/24051775/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Fresh Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Fresh Website</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">
    Welcome to My Fresh Website
  </div>

  <section id="about">
    <h2>About</h2>
    <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=900&q=80" alt="About Image">
    <p>This is a fresh start! Your website is clean and ready for content.</p>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="Gallery Image 1">
      <img src="https://images.unsplash.com/photo-1493244040629-496f6d136cc3?auto=format&fit=crop&w=600&q=80" alt="Gallery Image 2">
      <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=600&q=80" alt="Gallery Image 3">
      <img src="https://images.unsplash.com/photo-1504198458649-3128b932f49b?auto=format&fit=crop&w=600&q=80" alt="Gallery Image 4">
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <img src="https://images.unsplash.com/photo-1525186402429-b4ff38bedbec?auto=format&fit=crop&w=900&q=80" alt="Contact Image">
    <p>Reach out here. Fresh start, fresh design! 256=753148046</p>
  </section>

  <footer>
    © 2025 My Fresh Website
  </footer>
</body>
</html>[style.css](https://github.com/user-attachments/files/24051808/style.css)
body {
  margin: 0;
  font-family: "Poppins", sans-serif;
  background: #eef2f7;
  color: #333;
}

header {
  background: linear-gradient(135deg, #4a90e2, #1e3c72);
  padding: 40px 20px;
  color: #fff;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

nav {
  background: #fff;
  padding: 15px;
  display: flex;
  justify-content: center;
  gap: 30px;
  border-bottom: 2px solid #e2e8f0;
  position: sticky;
  top: 0;
  z-index: 10;
}

nav a {
  color: #1e3c72;
  text-decoration: none;
  font-weight: 600;
  transition: 0.3s;
}

nav a:hover {
  color: #4a90e2;
  transform: scale(1.05);
}

.hero {
  height: 350px;
  background: url('https://images.unsplash.com/photo-1503264116251-35a269479413?auto=format&fit=crop&w=1350&q=80') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 2.4rem;
  letter-spacing: 1px;
  font-weight: bold;
  text-shadow: 0 4px 10px rgba(0,0,0,0.4);
  animation: fadeIn 1.5s ease-in-out;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

section {
  padding: 40px;
  max-width: 950px;
  margin: 30px auto;
  background: white;
  border-radius: 14px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.07);
  animation: fadeIn 1.2s ease-in-out;
}

h2 {
  color: #1e3c72;
}

footer {
  text-align: center;
  padding: 20px;
  background: #1e3c72;
  color: white;
  margin-top: 30px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

