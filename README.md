---
extensions:
  preset: gfm

---

<h1 id="calculation-of-overturn-moment-due-to-horizontal-wind-force">Calculation of overturn moment due to horizontal wind force</h1>

<table>
<thead>
<tr>
<th align="center">This tool calculates the load at each guy to resist overturn due to horizontal wind force.</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"></td>
</tr>
<tr>
<td align="center"><img src="https://ballast.web.app/tent.png" alt="enter image description here"></td>
</tr>
</tbody>
</table><h2 id="assumptions">Assumptions</h2>

<table>
<thead>
<tr>
<th align="center"></th>
<th align="center"></th>
<th align="center"></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><img src="https://ballast.web.app/p1.png" alt=""></td>
<td align="center"><img src="https://ballast.web.app/p2.png" alt=""></td>
<td align="center"><img src="https://ballast.web.app/p3.png" alt=""></td>
</tr>
</tbody>
</table><ol>
<li>Wind pressure is applied on the windward wall (if side is present) and on the roof profile vertical projection.</li>
<li>Wind pressure is calculated from the wind speed using p = 0.00256 V2, where V is the wind speed in miles per hour (mph) and p is the pressure in pound per square foot (psf). For instance, if V = 70 mph, p = 12.5 psf.</li>
<li>Vertical wind load (uplift) is not considered as it is a different mode of failure.</li>
<li>The ground friction at the footings of all leeward posts is sufficiently large to prevent sliding of the whole tent.</li>
<li>The frame is sufficiently rigid to overturn as a whole without collapsing at the onset  of overturn.</li>
<li>The number of ballasts per post along the width and the length are the same.</li>
<li>The number of ballasts per corner post is the same for the four corners.</li>
</ol>
<h2 id="user-input">User Input</h2>
<p><img src="https://ballast.web.app/labeled.png" alt="enter image description here"></p>

<table>
<thead>
<tr>
<th align="center">Gable Roof</th>
<th align="center">Hip Roof</th>
<th align="center">Pyramid Roof</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><img src="https://ballast.web.app/gable.png" alt="Gable Roof"></td>
<td align="center"><img src="https://ballast.web.app/gable.png" alt="Gable Roof"></td>
<td align="center"><img src="https://ballast.web.app/hip.png" alt="Hip Roof"></td>
</tr>
</tbody>
</table><blockquote>
<p>Clear wind flow denotes unobstructed wind flow with no blockage (e.g., plain, grass land, large parking lot). Partially obstructed wind flow denotes relatively unobstructed wind flow with blockage less than or equal to 50%.</p>
</blockquote>
<blockquote>
<p>Obstructed wind flow denotes objects below roof inhibiting wind flow with 50% blockage (e.g., urban environment, dense vegetation all the way around)</p>
</blockquote>

