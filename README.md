<h3>Vienna Districts Map Javascript Plugin</h3>

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

The MIT License (MIT)

Copyright (c) 2015 Milos Kuveljic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
