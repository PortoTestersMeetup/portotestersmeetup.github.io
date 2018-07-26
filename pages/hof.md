# Hall of Fame

### A big thanks to the people who were in the organization of this community.

<div style="border: 1px solid transparent; width: 100%;">
  <div class="column" style="padding: 0.5rem 1rem; border: 1px solid #e9ebec; width: 33%;">
    <div class="speakercontainer">
      <img class="speakerimage" src="../images/organization/diogo_junior.jpg" style="min-width:40px;"/>
      <div class="speakermiddle">
        <div class="speakertext" onclick="on('dj')">Diogo Júnior</div>
      </div>
    </div>
  </div>
  <div class="column" style="padding: 0.5rem 1rem; border: 1px solid #e9ebec; width: 33%;">
    <div class="speakercontainer">
      <img class="speakerimage" src="https://avatars1.githubusercontent.com/u/11976836?s=460&v=4" style="min-width:40px;"/>
      <div class="speakermiddle">
         <div class="speakertext" onclick="on('filfreire')">Filipe Freire</div>
      </div>
    </div>
  </div>
</div>

<div id="dj" class="overlay" onclick="off('dj')">
  <div id="text">Diogo Júnior, engineer from FEUP, started working at the Fraunhofer Research Institute in Portugal. After 5 years in research area moved to the "business" world and started working in the mobile e-commerce team at Porto Tech Center. At the moment is working at 7Graus where is currently Lead Android - Full Stack Dev - ASO Expert.</div>
</div>

<div id="filfreire" class="overlay" onclick="off('filfreire')">
  <div id="text">Filipe Freire is currently working with adidas. Check more about him at <a class="overlay-link" href="http://filfreire.com">filfreire.com</a>.</div>
</div>

<script>
function on(panel) {
    document.getElementById(panel).style.display = "block";
}

function off(panel) {
    document.getElementById(panel).style.display = "none";
}
</script>

<br/>
<center><a href="../index.html"><button type="button">Home</button></a></center>
