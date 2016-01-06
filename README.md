<h3>Vienna Districts Map Plugin</h3>

This is a light weight Vienna Districts Plugin. You can easily add it to your app or web site. The Plugin requries a jQuery Library.<br/>

<h4>How to add the map:</h4>

<pre><code>$('#map').viennaDistrictsMap();</code></pre>

<h4>How to add a link to a district:</h4>

<pre><code>//Adds an on click link to the 1st distrinct on the map
$('#map').linkDistricts(1, "http://www.google.com");</code></pre>

<h4>Change the Map Colours:</h4>
<pre><code>//blue - static map colour
//pink - map on hover color
//yellow - static text colour
//black - text on hover colour
$('#map').changeDistrictColors('blue', 'pink', 'yellow', 'black');</code></pre>

<h4>Licence</h4>
The plugins is under the MIT Licence
