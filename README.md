<h3 dir="ltr" >Features Version 1.1</h3>

<ul>
<li><p>Python 2</p>

</li>
<li><p>Linux only</p>

</li>
</ul>

<p>Instructions</p>

<p>1. Download the repository, you can use the command below if you have git installed:</p>

<p>git clone <a href="https://github.com/sameryahya56/mac_changer" >https://github.com/sameryahya56/mac_changer</a></p>

<p>2. Make sure that you have python installed, just type python in your terminal and you will see an interpreter if it is installed.</p>

<p>3. Go to the folder where you have the repository cloned, make sure you are in the folder which the repository is and use (of course it must be unziped, if you used git clone it should be already unziped)</p>

<p>cd mac_changer/</p>

<p>4. Now you have to run the program like python mac_changer.py and the arguments (check the section below)</p>

<h3 dir="ltr" >Arguments</h3>

<h6 dir="ltr" >You can use the short one with one "-" or you can use the long one with two "--"</h6>

<table ><colgroup><col ><col ></colgroup>
<tbody>
<tr>
<td><p>Argument</p></td>
<td><p>Help</p></td>
</tr>

<tr>
<td><p>--help</p></td>
<td><p>To see more info and options.</p></td>
</tr>

<tr>
<td><p>-m / --mac</p></td>
<td><p>To put the new MAC Address (must be 6 pairs of alphanumerics characters) separated with ":" example 00:11:22:33:44:55</p></td>
</tr>

<tr>
<td><p>-i / --interface</p></td>
<td><p>Put the interface which you wanna change the MAC, to know your interface use ifconfig.</p>

<br />
</td>
</tr>

</tbody>
</table>

<h4 dir="ltr" >Combination of arguments</h4>

<p>(examples only with short version but you can use long too)</p>

<ul>
<li><p>--help:<br />
python mac_changer --help</p>

</li>
<li><p>-i:<br />
python3 mac_changer -i (your interface “eth0”)</p>

</li>
<li><p>-m:<br />
python mac_changer -m 00:14:22:91:56:37 </p>

</li>
<li><p>Your line should be like this:<br />
python mac_changer -i (your interface “eth0”) -m (the new mac address “ 00:14:22:91:56:37”)</p>

</li>
</ul>

<br />
