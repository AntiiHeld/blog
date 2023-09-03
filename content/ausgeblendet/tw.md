+++
title = "Erinnerungen an die Zukunft "
tags = ""
draft = ""
image = ""
url= "/eadz/"
+++
{{<rawhtml>}}
  <img id="slideshow" src="" alt="Bild" />

  <script>
    const bilder = [
      '/tw/2023_05_18.png',
      '/tw/2023_05_19.png',
      '/tw/2023_05_19_01.png',
      '/tw/2023_05_20.png',
      '/tw/2023_05_21.png',
      '/tw/2023_05_22.png',
      '/tw/2023_05_23.png',
      '/tw/2023_05_24.png',
      '/tw/2023_05_25.png',
      '/tw/2023_05_27.png',
      '/tw/2023_05_28.png',
      '/tw/2023_05_29.png',
      '/tw/2023_05_30.png',
      '/tw/2023_05_31.png',
      '/tw/2023_06_01.png',
      '/tw/2023_06_02.png',
      '/tw/2023_06_05.png',
      '/tw/2023_06_06.png',
      '/tw/2023_06_08.png',
      '/tw/2023_06_12.png',
      '/tw/2023_06_13.png',
      '/tw/2023_06_22.png',
      '/tw/2023_06_27.png'
      // Fügen Sie hier weitere Bild-URLs hinzu
    ];

    let index = 0;

    function startDiashow() {
      setInterval(function() {
        document.getElementById('slideshow').src = bilder[index];
        index = (index + 1) % bilder.length;
      }, 1000); // Ändern Sie diese Zahl, um die Anzeigedauer anzupassen (hier 1 Sekunde)
    }

    startDiashow();
  </script>
  {{</rawhtml>}}
