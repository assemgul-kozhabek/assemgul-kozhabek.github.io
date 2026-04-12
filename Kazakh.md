---
title: "Қазақша мағлұмат"
permalink: /Kazakh/
---

Бұл парақша менің ана тілім – қазақ тілінде жүргізіледі.

## БАҚ-та біздің зерттеуіміз туралы жарияланған материалдар

<div class="news-carousel">
  <div class="slides">
    <div class="slide active">
      <img src="/assets/elkz.jpeg" alt="El.kz мақаласы">
      <p><strong>El.kz</strong><br>
      Ажар Лаубаева.
      <a href="https://el.kz/keptelisti-basqaruga-bolady-otandyq-inzhener-galym-zhana-zhuye-usyndy_400045726/" target="_blank">
      «Кептелісті басқаруға болады: отандық инженер-ғалым жаңа жүйе ұсынды»
      </a>. 06.04.2026.</p>
    </div>

    <div class="slide">
      <img src="/assets/ulysmedia.jpeg" alt="Ulysmedia мақаласы">
      <p><strong>Ulysmedia</strong><br>
      Ақлима Джақсыбекова.
      <a href="https://qaz.ulysmedia.kz/news/38413-kazakstandyk-galym-britaniia-parlamentinde-gylymi-zhobasyn-tanystyrdy/" target="_blank">
      «Қазақстандық ғалым Британия парламентінде ғылыми жобасын таныстырды»
      </a>. 29.03.2026.</p>
    </div>

    <div class="slide">
      <img src="/assets/khabar.jpeg" alt="Khabar TV сюжеті">
      <p><strong>Khabar TV</strong><br>
      <a href="https://www.youtube.com/watch?v=8fr18N5udA8" target="_blank">
      «Ұлыбританиядағы қазақ ғалымының жетістігі | Оян»
      </a>. 30.03.2026.</p>
    </div>

    <div class="slide">
      <img src="/assets/hwnews.jpeg" alt="HW News article">
      <p><strong>HW News / NewsBeat</strong><br>
      <a href="https://heriotwatt.sharepoint.com/sites/Newsletter/SitePages/Postdoctoral%20researcher%20shares%20urban%20traffic%20insights%20at%20UK%20Parliament.aspx?startedResponseCatch=true" target="_blank">
      Postdoctoral researcher shares urban traffic insights at UK Parliament
      </a>. Published 25.03.2026.</p>
    </div>
  </div>

  <button class="carousel-btn prev" onclick="moveSlide(-1)">❮</button>
  <button class="carousel-btn next" onclick="moveSlide(1)">❯</button>
</div>

<style>
.news-carousel {
  position: relative;
  max-width: 850px;
  margin: 30px auto;
  overflow: hidden;
  border-radius: 12px;
  background: #f7f7f7;
  padding: 14px;
}

.slide {
  display: none;
  text-align: center;
}

.slide.active {
  display: block;
}

.slide img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  margin-bottom: 15px;
}

.slide p {
  font-size: 1rem;
  line-height: 1.6;
  padding: 0 10px 10px;
}

.carousel-btn {
  position: absolute;
  top: 40%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.5);
  color: white;
  border: none;
  padding: 12px 16px;
  cursor: pointer;
  font-size: 20px;
  border-radius: 8px;
}

.prev {
  left: 10px;
}

.next {
  right: 10px;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  let currentSlide = 0;
  const slides = document.querySelectorAll(".slide");

  function showSlide(index) {
    slides.forEach((slide, i) => {
      slide.classList.toggle("active", i === index);
    });
  }

  window.moveSlide = function(step) {
    currentSlide = (currentSlide + step + slides.length) % slides.length;
    showSlide(currentSlide);
  };

  showSlide(currentSlide);
});
</script>
