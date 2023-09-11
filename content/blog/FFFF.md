+++
date = "2023-09-11T01:19:00"
title = "x"
tags = ""
draft = ""
image = ""
+++
# {{<rawhtml>}}<span class="title">Ähnlichkeiten</span>{{</rawhtml>}}
{{<rawhtml>}}<span class="hide1">Stark und doch sanft,</span>{{</rawhtml>}}\
{{<rawhtml>}}<span class="hide2">Hart und doch zärtlich</span>{{</rawhtml>}}\
{{<rawhtml>}}<span class="hide3">Zart und doch so zerbrechlich</span>{{</rawhtml>}}\
{{<rawhtml>}}<span class="eins">SIE</span>{{</rawhtml>}} {{<rawhtml>}}<span class="hide4">hat ein Loch im Herz</span>{{</rawhtml>}}\
{{<rawhtml>}}<span class="hide5">Grausam tief sitzt der Schmerz</span>{{</rawhtml>}}\
{{<rawhtml>}}<span class="zwei">SIE</span>{{</rawhtml>}} kniet am Boden, {{<rawhtml>}}<span class="drei">SIE</span>{{</rawhtml>}} betet, fleht,\
Hofft, das der Alptraum vergeht.\
{{<rawhtml>}}<span class="vier">SIE</span>{{</rawhtml>}} ringt nach Luft.\
Panik. Angst.\
Schweiß tropft von den Wänden.\
{{<rawhtml>}}<span class="funf">IHR</span>{{</rawhtml>}} eigenes Blut an den Händen.\
In {{<rawhtml>}}<span class="sechs">IHREM</span>{{</rawhtml>}} Schoß liegen Scherben.\
{{<rawhtml>}}<span class="sieben">SIE</span>{{</rawhtml>}} würde gern.
\
\
\
{{<rawhtml>}}<span class="nachricht">?</span>{{</rawhtml>}}




{{<rawhtml>}}
  



  
<script id="eins">
// ——————————————————————————————————————————————————
// TextScramble
// ——————————————————————————————————————————————————

class eins {
  constructor(eleins) {
    this.eleins = eleins;
    this.charseins = 'tabitha';
    this.updateeins = this.updateeins.bind(this);
  }
  setText(newTexteins) {
    const oldTexteins = this.eleins.innerText;
    const length = Math.max(oldTexteins.length, newTexteins.length);
    const promise = new Promise(resolve => this.resolve = resolve);
    this.queueeins = [];
    for (let i = 0; i < length; i++) {
      const from = oldTexteins[i] || '';
      const to = newTexteins[i] || '';
      const start = Math.floor(Math.random() * 40);
      const end = start + Math.floor(Math.random() * 40);
      this.queueeins.push({ from, to, start, end });
    }
    cancelAnimationFrame(this.frameRequest);
    this.frame = 0;
    this.updateeins();
    return promise;
  }
  updateeins() {
    let output = '';
    let complete = 0;
    for (let i = 0, n = this.queueeins.length; i < n; i++) {
      let { from, to, start, end, char } = this.queueeins[i];
      if (this.frame >= end) {
        complete++;
        output += to;
      } else if (this.frame >= start) {
        if (!char || Math.random() < 0.28) {
          char = this.randomChar();
          this.queueeins[i].char = char;
        }
        output += `<span class="dud">${char}</span>`;
      } else {
        output += from;
      }
    }
    this.eleins.innerHTML = output;
    if (complete === this.queueeins.length) {
      this.resolve();
    } else {
      this.frameRequest = requestAnimationFrame(this.updateeins);
      this.frame++;
    }
  }
  randomChar() {
    return this.charseins[Math.floor(Math.random() * this.charseins.length)];
  }}


// ——————————————————————————————————————————————————
// Example
// ——————————————————————————————————————————————————




  // TEIL 1
  const el1 = document.querySelector('.eins');
  const el2 = document.querySelector('.zwei');
  const el3 = document.querySelector('.drei');
  const el4 = document.querySelector('.vier');
  const el5 = document.querySelector('.funf');
  const el6 = document.querySelector('.sechs');
  const el7 = document.querySelector('.sieben');
  const eltitle = document.querySelector('.title');
  const elnachricht = document.querySelector('.nachricht');
  const elhide1 = document.querySelector('.hide1');
  const elhide2 = document.querySelector('.hide2');
  const elhide3 = document.querySelector('.hide3');
  const elhide4 = document.querySelector('.hide4');
  const elhide5 = document.querySelector('.hide5');

  
  // TEIL 2
  const fx1 = new eins(el1);
  const fx2 = new eins(el2);
  const fx3 = new eins(el3);
  const fx4 = new eins(el4);
  const fx5 = new eins(el5);
  const fx6 = new eins(el6);
  const fx7 = new eins(el7);
  const fxtitle = new eins(eltitle);
  const fxnachricht = new eins(elnachricht);
  const fxhide1 = new eins(elhide1);
  const fxhide2 = new eins(elhide2);
  const fxhide3 = new eins(elhide3);
  const fxhide4 = new eins(elhide4);
  const fxhide5 = new eins(elhide5);


  // TEIL 3
  const phrases1 = ['Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases2 = ['Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases3 = ['sie', 'er', 'sie', 'er', 'sie', 'er', 'sie', 'er', 'sie', 'er', 'sie','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases4 = ['Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases5 = ['Ihr', 'Sein', 'Ihr', 'Sein', 'Ihr', 'Sein', 'Ihr', 'Sein', 'Ihr', 'Sein', 'Ihr','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases6 = ['ihrem', 'seinem', 'ihrem', 'seinem', 'ihrem', 'seinem', 'ihrem', 'seinem', 'ihrem', 'seinem', 'ihrem','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrases7 = ['Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie', 'Er', 'Sie','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrasestitle = ['Sie          ','Er          ','Sie          ','Er          ','Sie          ','Er          ','Sie          ','Er          ','Sie          ','Er          ','Sie          ','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  const phrasesnachricht = ['Bitte warten...','Zum Neustarten Seite neuladen...','60','59','58','57','56','55','54','53','52','51','50','49','48','47','46','45','44','43','42','41','40','39','38','37','36','35','34','33','32','31','Nachricht wird entschlüsselt...','29','28','27','26','25','24','23','22','21','20','19','18','17','16','15','14','13','12','11','10','9','8','7','6','5','4','3','2','1','0','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];


  const phrasehide1 = ['Stark und doch sanft,','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  
  const phrasehide2 = ['Hart und doch zärtlich','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  
  const phrasehide3 = ['Zart und doch so zerbrechlich','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  
  const phrasehide4 = ['hat ein Loch im Herz','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];
  
  const phrasehide5 = ['Grausam tief sitzt der Schmerz','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','','',''];

  
  // TEIL 4
  let counter1 = 0;
  let counter2 = 0;
  let counter3 = 0;
  let counter4 = 0;
  let counter5 = 0;
  let counter6 = 0;
  let counter7 = 0;
  let countertitle = 0;
  let counternachricht = 0;
  let counterhide1 = 0;
  let counterhide2 = 0;
  let counterhide3 = 0;
  let counterhide4 = 0;
  let counterhide5 = 0;

  
  // TEIL 5
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next1 = () => {
    fx1.setText(phrases1[counter1]).then(() => {
      setTimeout(next1, 9000);
    });
    counter1 = (counter1 + 1) % phrases1.length;
  };
  // ENDE

  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next2 = () => {
    fx2.setText(phrases2[counter2]).then(() => {
      setTimeout(next2, 9000);
    });
    counter2 = (counter2 + 1) % phrases2.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next3 = () => {
    fx3.setText(phrases3[counter3]).then(() => {
      setTimeout(next3, 9000);
    });
    counter3 = (counter3 + 1) % phrases3.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next4 = () => {
    fx4.setText(phrases4[counter4]).then(() => {
      setTimeout(next4, 9000);
    });
    counter4 = (counter4 + 1) % phrases4.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next5 = () => {
    fx5.setText(phrases5[counter5]).then(() => {
      setTimeout(next5, 9000);
    });
    counter5 = (counter5 + 1) % phrases5.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next6 = () => {
    fx6.setText(phrases6[counter6]).then(() => {
      setTimeout(next6, 9000);
    });
    counter6 = (counter6 + 1) % phrases6.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const next7 = () => {
    fx7.setText(phrases7[counter7]).then(() => {
      setTimeout(next7, 9000);
    });
    counter7 = (counter7 + 1) % phrases7.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexttitle = () => {
    fxtitle.setText(phrasestitle[countertitle]).then(() => {
      setTimeout(nexttitle, 9000);
    });
    countertitle = (countertitle + 1) % phrasestitle.length;
  };
  // ENDE
  
  // Funktionen zum Aktualisieren der Texte für jedes Element
  const nextnachricht = () => {
    fxnachricht.setText(phrasesnachricht[counternachricht]).then(() => {
      setTimeout(nextnachricht, 1000);
    });
    counternachricht = (counternachricht + 1) % phrasesnachricht.length;
  };
  // ENDE
  
    // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexthide1 = () => {
    fxhide1.setText(phrasehide1[counterhide1]).then(() => {
      setTimeout(nexthide1, 110000);
    });
    counterhide1 = (counterhide1 + 1) % phrasehide1.length;
  };
  // ENDE
  
    // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexthide2 = () => {
    fxhide2.setText(phrasehide2[counterhide2]).then(() => {
      setTimeout(nexthide2, 110000);
    });
    counterhide2 = (counterhide2 + 1) % phrasehide2.length;
  };
  // ENDE
  
    // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexthide3 = () => {
    fxhide3.setText(phrasehide3[counterhide3]).then(() => {
      setTimeout(nexthide3, 110000);
    });
    counterhide3 = (counterhide3 + 1) % phrasehide3.length;
  };
  // ENDE
  
    // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexthide4 = () => {
    fxhide4.setText(phrasehide4[counterhide4]).then(() => {
      setTimeout(nexthide4, 110000);
    });
    counterhide4 = (counterhide4 + 1) % phrasehide4.length;
  };
  // ENDE
  
    // Funktionen zum Aktualisieren der Texte für jedes Element
  const nexthide5 = () => {
    fxhide5.setText(phrasehide5[counterhide5]).then(() => {
      setTimeout(nexthide5, 110000);
    });
    counterhide5 = (counterhide5 + 1) % phrasehide5.length;
  };
  // ENDE

  // TEIL 6
  next1();
  next2();
  next3();
  next4();
  next5();
  next6();
  next7();
  nexttitle();
  nextnachricht();
  nexthide1();
  nexthide2();
  nexthide3();
  nexthide4();
  nexthide5();

    </script>
	
	
	

	
	
	

  {{</rawhtml>}}
