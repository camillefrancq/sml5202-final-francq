<h1>Homework 3</h1>
<p>
  <a href="index.html">Home page</a> <br>
  <a href="page3.html">Page 2</a>
</p>

<p>
<img class="imgLeft" style="width:50%; border: 1px solid black;"
src="https://www.discoverlosangeles.com/sites/default/files/styles/hero/public/images/2019-01/Hermosa%20Beach%20Pier%20sunset.jpg?itok=9x82CPJg" alt="DESCRIPTION OF IMAGE" >
Stunning sunsets are synonymous with California. With miles of picturesque coastlines and expansive landscapes, there’s no shortage of places to watch the sun go down in the most breathtaking fashion.
</p>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>



<h2>Here is a list of all names zith a random(ish) verb + adverb</h2>
<button onclick="makeSentence()">Click me</button>

<p id="demo"></p>

<script>
function makeSentence() {

var person = {
    names: ["Brian", "Betty", "Fiona"],
    verbs: ["speaks", "eats","runs", "walks"],
    adverbs: ["slowly", "quickly", "nicely"],

};

var i;
var text = "";
for (i = 0; i < person.names.length; i++) {

  name = person.names[i];
  verb = person.verbs[Math.floor(Math.random() * person.verbs.length)];
  adv = person.adverbs[Math.floor(Math.random() * person.adverbs.length)];

  text += name + " " + verb + " " + adv + "<br>";

  document.getElementById("demo").innerHTML= text;

}
}
  
</script>
