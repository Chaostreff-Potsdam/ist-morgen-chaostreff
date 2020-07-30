## Ist morgen Chaostreff?
<div  style="margin: 0 auto;">
  <b style="font-size: xxx-large;" id="answer" >Bitte aktiviere Javascript, falls du eine korrekte Antwort möchtest. Ansonsten lautet die Antwort: Nein! (>85% Genauigkeit)</b>
</div>

## [Ist heute Chaostreff?](http://www.ist-heute-chaostreff.online)

 <script>
  var wednesday = 3;
  
  var treffDay = wednesday;
  
  var answers = {
    true:  "JA!",
    false: "Nein!"
  };

  var date = new Date();
  var dayOfWeek = date.getDay();
  
  document.getElementById("answer").innerHTML = answers[dayOfWeek == treffDay];
 </script>