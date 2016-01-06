<h3>Vienna City Districts Javascript Plugin</h3>

This is a light weight Vienna Districts Plugin. You can easily add it to your app or web site. The Plugin requries a jQuery Library.<br/>

<h4>How to add the map:</h4>

<pre><code>$('#map').viennaDistrictsMap();</code></pre>

<h4>How to add a link to a district:</h4>

<pre><code>//Adds an on click link to the 1st distrinct on the map
$('#map').linkDistricts(1, "http://www.google.com");</code></pre>

<h4>Change the Map Colours:</h4>
<pre><code>$('#map').changeDistrictColors('blue', 'pink', 'yellow', 'black');
//blue - static map colour
//pink - map on hover color
//yellow - static text colour
//black - text on hover colour</code></pre>

<h4>Licence</h4>

The Plugin is under an MIT Licence. Please read the LICENCE.txt file for further details and instructions.
