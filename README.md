<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Graphiluxe - Free PNGs, Fonts, Vectors & More</title>
  <meta name="description" content="Graphiluxe is your one-stop destination for all things premium in design – PNGs, Fonts, Vectors, Wallpapers & More. Experience luxury in design.">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #ffffff, #800000);
    }.header {
  text-align: center;
  padding: 50px 20px;
  color: white;
  background: #2d2d2d;
}

.header h1 {
  font-size: 48px;
  margin-bottom: 5px;
  letter-spacing: 2px;
}

.header small {
  font-size: 16px;
  color: #ccc;
}

.about {
  background-color: #fff0f0;
  padding: 30px;
  font-size: 18px;
  text-align: center;
  line-height: 1.6;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 30px;
}

.item {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.2s ease;
}

.item:hover {
  transform: scale(1.03);
}

.item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.item .desc {
  padding: 15px;
  font-size: 16px;
  font-weight: 500;
}

.download-btn {
  display: block;
  margin: 10px auto 20px auto;
  padding: 10px 20px;
  background-color: #800000;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

footer {
  background-color: #2d2d2d;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 14px;
}

.search-bar {
  text-align: center;
  margin-top: 20px;
}

#searchInput {
  padding: 10px;
  width: 300px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

  </style>
</head>
<body>  <div class="header">
    <h1><span style="color:#ffd6d6;">Graphi</span><span style="color:#fff;">luxe</span></h1>
    <small>Design with Class</small>
  </div>  <div class="search-bar">
    <input type="text" id="searchInput" onkeyup="filterGallery()" placeholder="Search resources...">
  </div>  <div class="about">
    <strong>Graphiluxe</strong> is your one-stop destination for all things premium in design.<br>
    ✨ Transparent PNGs, ✨ Modern Fonts, ✨ 4K Wallpapers, ✨ Vectors, Illustrations – All free and high-quality.<br>
    It's not just a website – it's a <strong>luxury experience for every creative mind.</strong>
  </div>  <div class="gallery" id="gallery">
    <div class="item">
      <img src="https://i.imgur.com/klbN8dd.png" alt="PNG Sample">
      <div class="desc">Stylish PNG #1</div>
      <a href="#" class="download-btn">Download</a>
    </div><div class="item">
  <img src="https://i.imgur.com/GI0iTIf.jpg" alt="Vector Sample">
  <div class="desc">Vector Art #1</div>
  <a href="#" class="download-btn">Download</a>
</div>

<div class="item">
  <img src="https://i.imgur.com/l6GS8Ff.jpg" alt="Font Preview">
  <div class="desc">Stylish Font Pack</div>
  <a href="#" class="download-btn">Download</a>
</div>

  </div>  <footer>
    Contact: meshiv9359@gmail.com | Instagram: @kunal_raut_149
  </footer>  <script>
    function filterGallery() {
      const input = document.getElementById('searchInput');
      const filter = input.value.toLowerCase();
      const gallery = document.getElementById('gallery');
      const items = gallery.getElementsByClassName('item');

      for (let i = 0; i < items.length; i++) {
        let desc = items[i].getElementsByClassName("desc")[0];
        if (desc.innerHTML.toLowerCase().indexOf(filter) > -1) {
          items[i].style.display = "block";
        } else {
          items[i].style.display = "none";
        }
      }
    }
  </script></body>
</html>
