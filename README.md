## Ist morgen Chaostreff?
<div  style="margin: 0 auto; width:75%">
  <b style="font-size: xxx-large;" id="answer" >Nein! (>85% Genauigkeit)</b>
  <br/>
  <div id="noscript">Bitte aktiviere Javascript, falls du eine genauere Antwort möchtest.</div>
</div>
<br/>

## [Ist heute Chaostreff?](http://www.ist-heute-chaostreff.online)

 <script>
 function updateAnswer(){
  var wednesday = 3;
  
  var treffDay = wednesday;
  var dayBeforeTreff = treffDay -1;
  
  var answers = {
    true:  "JA!",
    false: "Nein!"
  };

  var date = new Date();
  var dayOfWeek = date.getDay();
  
  document.getElementById("answer").innerHTML = answers[dayOfWeek == dayBeforeTreff];
  document.getElementById("noscript").remove();
 }
 updateAnswer();
 </script>