+++
date = "2023-09-03T18:28:00"
title = "Erinnerungen an die Zukunft "
tags = ""
draft = ""
image = ""
+++
{{<rawhtml>}}
  <img id="slideshow" src="" alt="Bild" />

  <script>
    const bilder = [
      '/tw/2023_05_18-min.png',
      '/tw/2023_05_19-min.png',
      '/tw/2023_05_19_01-min.png',
      '/tw/2023_05_20-min.png',
      '/tw/2023_05_21-min.png',
      '/tw/2023_05_22-min.png',
      '/tw/2023_05_23-min.png',
      '/tw/2023_05_24-min.png',
      '/tw/2023_05_25-min.png',
      '/tw/2023_05_27-min.png',
      '/tw/2023_05_28-min.png',
      '/tw/2023_05_29-min.png',
      '/tw/2023_05_30-min.png',
      '/tw/2023_05_31-min.png',
      '/tw/2023_06_01-min.png',
      '/tw/2023_06_02-min.png',
      '/tw/2023_06_05-min.png',
      '/tw/2023_06_06-min.png',
      '/tw/2023_06_08-min.png',
      '/tw/2023_06_12-min.png',
      '/tw/2023_06_13-min.png',
      '/tw/2023_06_22-min.png',
      '/tw/2023_06_27-min.png'
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
