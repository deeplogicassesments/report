<!DOCTYPE html>
<html>
<body>
<p><u><h3>Time website five recent updates</h3></u></p>
<p id="demo"></p>
<script>
var myObj, i, j, x = "";
myObj = {
  "name":"https://time.com",
  "link": [
    {"name":"2 million people have died from COVID-19 worldwide", "models":["https://time.com/5930111/2-million-covid-19-deaths/"]},
    {"name":"A fireable Offense", "models":["https://time.com/5929398/police-officers-involved-capitol-riots-charges/"]},
    {"name":"After georgia flips blue GOP push voting restriction", "models":["https://time.com/5928991/georgia-republicans-voting-restrictions/"] },{"name":"Israel leads in COVID-19 vaccinations palestinians are'nt on the list", "models":["https://time.com/5930060/israel-covid-vaccine-palestinians/"] },{"name":"The GOP's last chance to quit trumph", "models":["https://time.com/5929618/donald-trump-impeachment-republicans/"] }
  ]
}
for (i in myObj.link) {
  x += "<h2>" + myObj.link[i].name + "</h2>";
  for (j in myObj.link[i].models) {
    x += myObj.link[i].models[j] + "<br>";
  }
}
document.getElementById("demo").innerHTML = x;
</script>

</body>
</html>

