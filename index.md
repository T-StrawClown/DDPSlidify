---
title       : Full Moon and Crime Rates in the City of Chicago
subtitle    : Assignment work of Developing Data Products by JHU on Coursera
author      : T-StrawClown
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Crimes Per Month by Moon Phases 
First lets check how crime rates look overall split by moon phase (drag to zoom, right-click to reset).
<!-- LineChart generated in R 3.2.5 by googleVis 0.5.10 package -->
<!-- Wed Jul 13 17:29:02 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataLineChartID1aa86216611c () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 new Date(2009,0,1,0,0,0),
7520,
9908,
6353,
6422 
],
[
 new Date(2009,1,1,0,0,0),
6695,
5872,
7389,
8272 
],
[
 new Date(2009,2,1,0,0,0),
8673,
9516,
7612,
7886 
],
[
 new Date(2009,3,1,0,0,0),
7842,
8721,
8229,
7739 
],
[
 new Date(2009,4,1,0,0,0),
9000,
10277,
8072,
7901 
],
[
 new Date(2009,5,1,0,0,0),
8138,
9493,
8743,
7796 
],
[
 new Date(2009,6,1,0,0,0),
8111,
10536,
7811,
9219 
],
[
 new Date(2009,7,1,0,0,0),
8118,
10155,
9143,
8446 
],
[
 new Date(2009,8,1,0,0,0),
7899,
8266,
8614,
9115 
],
[
 new Date(2009,9,1,0,0,0),
7732,
8645,
9672,
7337 
],
[
 new Date(2009,10,1,0,0,0),
7463,
6705,
8351,
8908 
],
[
 new Date(2009,11,1,0,0,0),
7706,
5553,
8540,
6436 
],
[
 new Date(2010,0,1,0,0,0),
7030,
6855,
8268,
6998 
],
[
 new Date(2010,1,1,0,0,0),
6871,
6429,
5510,
6116 
],
[
 new Date(2010,2,1,0,0,0),
7430,
8312,
8140,
8364 
],
[
 new Date(2010,3,1,0,0,0),
8711,
7310,
8673,
6990 
],
[
 new Date(2010,4,1,0,0,0),
7525,
8688,
8608,
8611 
],
[
 new Date(2010,5,1,0,0,0),
8651,
7517,
8704,
7708 
],
[
 new Date(2010,6,1,0,0,0),
7555,
8879,
7741,
9388 
],
[
 new Date(2010,7,1,0,0,0),
8741,
7852,
8730,
8783 
],
[
 new Date(2010,8,1,0,0,0),
7324,
8451,
7646,
8499 
],
[
 new Date(2010,9,1,0,0,0),
8614,
7350,
8293,
8068 
],
[
 new Date(2010,10,1,0,0,0),
6998,
7952,
6682,
7295 
],
[
 new Date(2010,11,1,0,0,0),
5869,
5749,
6594,
7001 
],
[
 new Date(2011,0,1,0,0,0),
7200,
7076,
5804,
7077 
],
[
 new Date(2011,1,1,0,0,0),
3795,
5517,
7123,
5721 
],
[
 new Date(2011,2,1,0,0,0),
7710,
6518,
6862,
7599 
],
[
 new Date(2011,3,1,0,0,0),
8092,
7062,
7335,
6553 
],
[
 new Date(2011,4,1,0,0,0),
9250,
7374,
6982,
7978 
],
[
 new Date(2011,5,1,0,0,0),
8834,
7404,
8573,
7494 
],
[
 new Date(2011,6,1,0,0,0),
9621,
7572,
7655,
8364 
],
[
 new Date(2011,7,1,0,0,0),
9579,
8388,
7208,
7363 
],
[
 new Date(2011,8,1,0,0,0),
7884,
6854,
7155,
8032 
],
[
 new Date(2011,9,1,0,0,0),
8277,
8597,
6796,
6512 
],
[
 new Date(2011,10,1,0,0,0),
6072,
7729,
7342,
6536 
],
[
 new Date(2011,11,1,0,0,0),
6337,
8171,
6137,
6359 
],
[
 new Date(2012,0,1,0,0,0),
5699,
8056,
6854,
5509 
],
[
 new Date(2012,1,1,0,0,0),
6401,
6202,
5619,
5708 
],
[
 new Date(2012,2,1,0,0,0),
6786,
8065,
6966,
6707 
],
[
 new Date(2012,3,1,0,0,0),
6287,
7252,
6237,
7432 
],
[
 new Date(2012,4,1,0,0,0),
6721,
8911,
7769,
6651 
],
[
 new Date(2012,5,1,0,0,0),
7345,
7351,
7798,
8459 
],
[
 new Date(2012,6,1,0,0,0),
8128,
7040,
9384,
7409 
],
[
 new Date(2012,7,1,0,0,0),
6738,
6753,
8968,
7533 
],
[
 new Date(2012,8,1,0,0,0),
7352,
6339,
7581,
6515 
],
[
 new Date(2012,9,1,0,0,0),
6356,
7387,
7147,
6979 
],
[
 new Date(2012,10,1,0,0,0),
7085,
5814,
7109,
5931 
],
[
 new Date(2012,11,1,0,0,0),
5991,
6358,
6071,
6856 
],
[
 new Date(2013,0,1,0,0,0),
6438,
5530,
6026,
7359 
],
[
 new Date(2013,1,1,0,0,0),
5528,
6100,
4950,
4776 
],
[
 new Date(2013,2,1,0,0,0),
6598,
5567,
6689,
6100 
],
[
 new Date(2013,3,1,0,0,0),
5937,
6467,
6082,
6961 
],
[
 new Date(2013,4,1,0,0,0),
7052,
6653,
6845,
7354 
],
[
 new Date(2013,5,1,0,0,0),
6234,
7443,
6367,
7322 
],
[
 new Date(2013,6,1,0,0,0),
6297,
6605,
7544,
8150 
],
[
 new Date(2013,7,1,0,0,0),
6485,
7458,
6389,
8250 
],
[
 new Date(2013,8,1,0,0,0),
6240,
6053,
6767,
7254 
],
[
 new Date(2013,9,1,0,0,0),
6693,
6560,
5530,
6577 
],
[
 new Date(2013,10,1,0,0,0),
6585,
5344,
6638,
4962 
],
[
 new Date(2013,11,1,0,0,0),
6831,
4630,
5160,
5254 
],
[
 new Date(2014,0,1,0,0,0),
5940,
3726,
5614,
4481 
],
[
 new Date(2014,1,1,0,0,0),
4039,
4365,
4349,
5255 
],
[
 new Date(2014,2,1,0,0,0),
6249,
5504,
5295,
5072 
],
[
 new Date(2014,3,1,0,0,0),
6061,
5351,
5360,
6029 
],
[
 new Date(2014,4,1,0,0,0),
7269,
6336,
5537,
5595 
],
[
 new Date(2014,5,1,0,0,0),
7041,
5832,
6601,
5915 
],
[
 new Date(2014,6,1,0,0,0),
7031,
7612,
5881,
5865 
],
[
 new Date(2014,7,1,0,0,0),
5578,
7781,
6661,
5764 
],
[
 new Date(2014,8,1,0,0,0),
6579,
6531,
5265,
5453 
],
[
 new Date(2014,9,1,0,0,0),
5450,
7187,
5841,
5383 
],
[
 new Date(2014,10,1,0,0,0),
4644,
5498,
5156,
5334 
],
[
 new Date(2014,11,1,0,0,0),
4693,
5696,
5565,
4952 
],
[
 new Date(2015,0,1,0,0,0),
5217,
5990,
4169,
5216 
],
[
 new Date(2015,1,1,0,0,0),
4530,
3286,
4226,
4274 
],
[
 new Date(2015,2,1,0,0,0),
4795,
5629,
4955,
6102 
],
[
 new Date(2015,3,1,0,0,0),
5798,
5088,
5722,
5009 
],
[
 new Date(2015,4,1,0,0,0),
5450,
5301,
6713,
6054 
],
[
 new Date(2015,5,1,0,0,0),
6203,
5290,
6190,
5301 
],
[
 new Date(2015,6,1,0,0,0),
5285,
6446,
6270,
6052 
],
[
 new Date(2015,7,1,0,0,0),
6303,
5608,
7198,
5556 
],
[
 new Date(2015,8,1,0,0,0),
5148,
6146,
5392,
6270 
],
[
 new Date(2015,9,1,0,0,0),
6007,
5263,
6526,
5057 
],
[
 new Date(2015,10,1,0,0,0),
4724,
5211,
4538,
5861 
],
[
 new Date(2015,11,1,0,0,0),
5626,
4822,
4952,
5419 
],
[
 new Date(2016,0,1,0,0,0),
4310,
4925,
4693,
5993 
],
[
 new Date(2016,1,1,0,0,0),
4808,
4154,
5323,
3987 
],
[
 new Date(2016,2,1,0,0,0),
4944,
5558,
4826,
6079 
],
[
 new Date(2016,3,1,0,0,0),
4614,
4911,
5634,
5402 
],
[
 new Date(2016,4,1,0,0,0),
4999,
5736,
5327,
6724 
],
[
 new Date(2016,5,1,0,0,0),
5351,
5346,
6111,
4635 
] 
];
data.addColumn('datetime','ym');
data.addColumn('number','New');
data.addColumn('number','Waxing');
data.addColumn('number','Full');
data.addColumn('number','Waning');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartLineChartID1aa86216611c() {
var data = gvisDataLineChartID1aa86216611c();
var options = {};
options["allowHtml"] = true;
options["colors"] = ['#e41a1c', '#377eb8', '#4daf4a', '#984ea3'];
options["curveType"] = "function";
options["width"] =   1000;
options["height"] =    400;
options["explorer"] = {actions: ['dragToZoom', 'rightClickToReset']};

    var chart = new google.visualization.LineChart(
    document.getElementById('LineChartID1aa86216611c')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartLineChartID1aa86216611c);
})();
function displayChartLineChartID1aa86216611c() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartLineChartID1aa86216611c"></script>
 
<!-- divChart -->
  
<div id="LineChartID1aa86216611c" 
  style="width: 1000; height: 400;">
</div>
Doesn't seem that there is something special about full moon. BTW more detailed data can be found in my shiny application [here] (https://tstrawclown.shinyapps.io/DDPCourseProject)

--- .class #id


## Top 5 Crime Types
Here is another look. Here are top 5 types of crimes committed during full moon.
<!-- ColumnChart generated in R 3.2.5 by googleVis 0.5.10 package -->
<!-- Wed Jul 13 17:29:03 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID1aa87a0a1a69 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "BATTERY",
107594,
108337,
107454,
107180 
],
[
 "BURGLARY",
38408,
38640,
38826,
38504 
],
[
 "CRIMINAL DAMAGE",
65558,
66433,
66325,
65092 
],
[
 "NARCOTICS",
62773,
64271,
63830,
63329 
],
[
 "THEFT",
130557,
132380,
132055,
130854 
] 
];
data.addColumn('string','type');
data.addColumn('number','New');
data.addColumn('number','Waxing');
data.addColumn('number','Full');
data.addColumn('number','Waning');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID1aa87a0a1a69() {
var data = gvisDataColumnChartID1aa87a0a1a69();
var options = {};
options["allowHtml"] = true;
options["width"] =   1000;
options["height"] =    400;
options["colors"] = ['#e41a1c', '#377eb8', '#4daf4a', '#984ea3'];

    var chart = new google.visualization.ColumnChart(
    document.getElementById('ColumnChartID1aa87a0a1a69')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartColumnChartID1aa87a0a1a69);
})();
function displayChartColumnChartID1aa87a0a1a69() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID1aa87a0a1a69"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID1aa87a0a1a69" 
  style="width: 1000; height: 400;">
</div>
Doesn't look promising too...

--- &twocol w1:50% w2:50%

### Statistical Perspective


*** =left
Distribution from all data (starting from year 2009)

<img src="assets/fig/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto auto auto 0;" />

*** =right
1K x 1K Bootstrap simulations (with replacement)

<img src="assets/fig/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto auto auto 0;" />

--- &radio

### Quiz
# The Ultimate Question

So after looking at these slides what do you think about statement that there are more crimes committed when the moon is full?

1. There is no such myth
2. _There is no statistical evidence of that_
3. It can be clearly seen that it is true
4. 42

*** .hint
No hints, sorry. You'll have to figure it out yourself

*** .explanation
Well from this presentation you can see that it is more likely that the opposite is true. Though the difference is not statistically significant.

But we both know that the true answer to the Ultimate Question is [42] (http://www.urbandictionary.com/define.php?term=42)

