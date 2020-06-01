<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Darmowy Kurs CSS</title>

    <style>
      #caly_blok {
        font-size:24px;
        min-width:480px;
        max-width:1600px;
        border-left:1px solid gold;
        border-right:1px solid gold;
      }

      #naglowek {
        background-color:gold;
        text-align:center;
        font-size:1.6em;
        line-height:1.5em;
      }

      #lewy {
        float:left;
        width:25%;
        font-size:1em;
        line-height:1.5em;
      }

      #lewy p {
        border:1px solid gold;
        border-left:none;
        margin:15px 0;
        padding:15px;
      }

      #srodek {
        float:left;
        width:50%;
        font-size:1.2em;
        line-height:1.5em;
      }

      #srodek p {
        margin:15px 0;
        padding:15px;
      }

      #prawy {
        float:left;
        width:25%;
        font-size:1em;
        line-height:1.5em;
      }

      #prawy p {
        border:1px solid gold;
        border-right:none;
        margin:15px 0;
        padding:15px;
      }

      #stopka {
        clear:both;
        background-color:gold;
        text-align:center;
        font-size:1.4em;
        line-height:1.5em;
      }
    </style>
  </head>

  <body>

    <div id="caly_blok">
      <div id="naglowek">nagłówek strony</div>

      <div id="lewy">
        <p>to jest lewa kolumna układu elementów HTML, który składa się z trzech kolumn</p>
      </div>

      <div id="srodek">
        <p>to jest środkowa kolumna układu elementów HTML</p>
      </div>

      <div id="prawy">
        <p>prawa kolumna układu elementów HTML</p>
      </div>

      <div id="stopka">stopka strony</div>
    </div>

  </body>
</html>
