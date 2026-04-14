---
title: "Қазақша мағлұмат"
permalink: /Kazakh/
---

Бұл парақша менің ана тілім – қазақ тілінде жүргізіледі.

### БАҚ-та біздің зерттеуіміз туралы жарияланған материалдар

<div class="carousel">

  <div class="slide active">
    <img src="/images/el_kz.jpg" alt="El.kz мақаласы" class="slide-img">
    <p><strong>El.kz</strong><br>
     журналист Ажар Лаубаева.<br>
    <a href="https://el.kz/keptelisti-basqaruga-bolady-otandyq-inzhener-galym-zhana-zhuye-usyndy_400045726/" target="_blank">
    «Кептелісті басқаруға болады: отандық инженер-ғалым жаңа жүйе ұсынды»
    </a><br>
    06.04.2026.
    </p>
  </div>

  <div class="slide">
    <img src="/images/ulysmedia.jpg" alt="Ulysmedia мақаласы" class="slide-img">
    <p><strong>Ulysmedia</strong><br>
     журналист Ақлима Джақсыбекова.<br>
    <a href="https://qaz.ulysmedia.kz/news/38413-kazakstandyk-galym-britaniia-parlamentinde-gylymi-zhobasyn-tanystyrdy/" target="_blank">
    «Қазақстандық ғалым Британия парламентінде ғылыми жобасын таныстырды»
    </a><br>
    29.03.2026.
    </p>
  </div>

  <div class="slide">
    <img src="/images/khabar.jpg" alt="Khabar TV бейнесі" class="slide-img">
    <p><strong>Khabar TV</strong><br>
    <a href="https://www.youtube.com/watch?v=8fr18N5udA8" target="_blank">
    «Ұлыбританиядағы қазақ ғалымының жетістігі | Оян»
    </a><br>
    30.03.2026.
    </p>
  </div>

  <div class="slide">
    <img src="/images/shalqar.jpg" alt="Shalqar радиосы бағдарламасы" class="slide-img">
    <p><strong>Shalqar радиосы</strong><br>
     журналист Нұржамал Янгибаева.<br>
    <a href="https://qazradio.fm/shalqarfm/kz/audios/63937" target="_blank">
    «Құтты білік» бағдарламасы
    </a><br>
    Қазақ тіліндегі материал
    </p>
  </div>

  <div class="slide">
    <img src="/images/hw_news.jpg" alt="HW News мақаласы" class="slide-img">
    <p><strong>HW News / NewsBeat</strong><br>
    <a href="https://heriotwatt.sharepoint.com/sites/Newsletter/SitePages/Postdoctoral%20researcher%20shares%20urban%20traffic%20insights%20at%20UK%20Parliament.aspx?startedResponseCatch=true" target="_blank">
     «Ұлыбритания парламентінде қалалық көлік қозғалысы туралы зерттеу нәтижелері ұсынылды»
    </a><br>
    25.03.2026.
    </p>
  </div>

  <div class="slide">
    <img src="/images/times_india.jpg" alt="The Times of India мақаласы" class="slide-img">
    <p><strong>The Times of India</strong><br>
    Пол Джон.<br>
    <a href="https://timesofindia.indiatimes.com/city/ahmedabad/study-rates-efficiency-of-city-road-network/articleshow/119086477.cms" target="_blank">
    «Қала жол желісінің тиімділігі зерттелді | Ахмедабад»
    </a><br>
    17.03.2025.
    </p>
  </div>

  <div class="slide">
    <img src="/images/aqshamnews.jpg" alt="aqshamnews.kz мақаласы" class="slide-img">
    <p><strong>aqshamnews.kz</strong><br>
     журналист Саягүл Әлімбекова.<br>
    <a href="https://aqshamnews.kz/kz/article/qazaq-qyzy-ulybritaniiada-kolik-qozgalysyn-retteuge-ules-qosyp-jur.html" target="_blank">
    «Қазақ қызы Ұлыбританияда көлік қозғалысын реттеуге үлес қосып жүр»
    </a><br>
    12.09.2021.
    </p>
  </div>

  <div class="slide">
    <img src="/images/qazaq_adebieti.jpg" alt="Qazaq Adebieti мақаласы" class="slide-img">
    <p><strong>Qazaq Adebieti</strong><br>
     журналист Нұрлайым Батыр.<br>
    <a href="https://qazaqadebieti.kz/11795/ala-oz-alysyn-retteu-ylymi-zertteudi-azhet-etedi" target="_blank">
    «Қала қозғалысын реттеу – ғылыми зерттеуді қажет етеді»
    </a><br>
    01.09.2017.
    </p>
  </div>

  <button class="prev" onclick="moveSlide(-1)">❮</button>
  <button class="next" onclick="moveSlide(1)">❯</button>

</div>

<style>
.carousel {
  position: relative;
  max-width: 700px;
  margin: 30px auto;
  background: #f7f7f7;
  padding: 20px;
  border-radius: 12px;
  text-align: center;
}

.slide {
  display: none;
}

.slide.active {
  display: block;
}

.slide-img {
  width: 100%;
  max-height: 250px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 15px;
}

.slide p {
  font-size: 1.1rem;
  line-height: 1.6;
}

button {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0,0,0,0.5);
  color: white;
  border: none;
  padding: 10px 14px;
  cursor: pointer;
  border-radius: 8px;
}

.prev { left: 10px; }
.next { right: 10px; }
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  let current = 0;
  const slides = document.querySelectorAll(".slide");

  function showSlide(i) {
    slides.forEach((s, index) => {
      s.classList.toggle("active", index === i);
    });
  }

  window.moveSlide = function(step) {
    current = (current + step + slides.length) % slides.length;
    showSlide(current);
  };

  showSlide(current);
});
</script>
