
var date = new Date();


document.getElementById("clock").innerHTML = date.toLocaleTimeString();


function startStory() {
 
  document.getElementById("story-text").classList.toggle("show-text");

  var btn = document.getElementById("btn");
  if (btn.innerHTML === "Aizvērt stāstu") {
 
  } else {
    btn.innerHTML = "Aizvērt stāstu";
  }
}
