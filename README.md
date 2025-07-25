<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LevelUp Gaming Café</title>
  <link href="style.css" rel="stylesheet">
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <a class="navbar-brand" href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/LevelUp%20Gaming%20Café(Main%20Menu).html">LevelUp</a>

      <div class="nav-links">
        <a href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/LevelUp%20Gaming%20Café(Main%20Menu).html" class="btn-book">Home</a>
        <a href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/Service.html">Services</a>
        <a href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/Contact.html">Contact</a>
        <a href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/Data-Entry.html" >Book Now</a>
      </div>
    </div>
  </nav>

  
  <section class="hero">
    <div>
      <h1>Join the Battle at LevelUp</h1>
      <p>Your best gaming destination – PC, Console & Tournaments</p>
      <a href="file:///C:/Users/harsh/OneDrive/Desktop/HTML/Data-Entry.html" class="btn-book">Book Now</a>
    </div>
  </section>


<div class="slideshow-container">

  <div class="mySlides">
    <img src="C:\Users\harsh\OneDrive\Desktop\HTML\2504_01290 seechurn\PC+Station+2.jpg">
  </div>

  <div class="mySlides">
    <img src="C:\Users\harsh\OneDrive\Desktop\HTML\2504_01290 seechurn\download.jpg" >
  </div>

  <div class="mySlides">
    <img src="C:\Users\harsh\OneDrive\Desktop\HTML\2504_01290 seechurn\professional-gamer-participating-esports-tournament-gaming-club_362389-5740.avif">
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>

<div style="text-align:center; margin-top: 10px;">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
  let slideIndex = 1;
  showSlides(slideIndex);

  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  function currentSlide(n) {
    showSlides(slideIndex = n);
  }

  function showSlides(n) {
    let i;
    let slides = document.getElementsByClassName("mySlides");
    let dots = document.getElementsByClassName("dot");
    if (n > slides.length) { slideIndex = 1 }
    if (n < 1) { slideIndex = slides.length }
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex - 1].style.display = "block";
    dots[slideIndex - 1].className += " active";
  }
</script>

  <footer>
  <p>&copy; 2025 LevelUp Gaming Café. All rights reserved.</p>
  <div class="social-icons">
    <a href="https://www.facebook.com/share/1NvWUfBd5c/" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Facebook_logo_%28square%29.png/960px-Facebook_logo_%28square%29.png" width="20" alt="Facebook" />
    </a>
    <a href="https://www.instagram.com/sarvesh_harsh_seechurn?igsh=bTV6MXlwazcwZWFp" target="_blank">
      <img src="https://img.freepik.com/premium-psd/instagram-logo_971166-164497.jpg?semt=ais_hybrid&w=740" width="20" alt="Instagram" />
    </a>
    <a href="https://x.com/SouGouXTensai?t=9MT2z3GnpR7HWnWusYfkzQ&s=09" target="_blank">
      <img src="https://images.freeimages.com/image/large-previews/f35/x-twitter-logo-on-black-circle-5694247.png" width="20" alt="twitter" />
    </a>
  </div>
</footer>

<script src="https://kit.fontawesome.com/4ad8a9c4f6.js" crossorigin="anonymous"></script>


</body>
</html>
