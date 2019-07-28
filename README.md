<p><a href="https://user-images.githubusercontent.com/53395087/62005404-6eb42f80-b13b-11e9-80c4-d72c42fb443a.png" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/53395087/62005404-6eb42f80-b13b-11e9-80c4-d72c42fb443a.png" alt="oie_ogeuzWuhkp0R" /></a><br /><strong>Features Version 1.1</strong></p>
<ul>
<li>
<p>Python 2</p>
</li>
<li>
<p>Linux only</p>
<p><strong>Instructions</strong>:</p>
</li>
</ul>
<ol>
<li>Download the repository, you can use the command below if you have git installed:<br /><code>git clone</code>&nbsp;<a href="https://github.com/sameryahya56/mac_changer">https://github.com/sameryahya56/mac_changer</a></li>
<li>Make sure that you have python installed, just type python in your terminal and you will see an interpreter if it is installed.</li>
<li>Go to the folder where you have the repository cloned, make sure you are in the folder which the repository is and use (of course, it must be unzipped, if you used git clone it should be already unzipped)<br /><code>cd mac_changer/</code></li>
<li>Now you have to run the program like&nbsp;<code>python mac_changer.py</code>&nbsp;and the arguments (check the section below)</li>
</ol>
<p><strong>Arguments</strong>:</p>
<table>
<thead>
<tr>
<th>Argument</th>
<th>Help</th>
</tr>
</thead>
<tbody>
<tr>
<td>--help</td>
<td>To see more info and options.</td>
</tr>
<tr>
<td>-m / --mac</td>
<td>To put the new MAC Address (must be 6 pairs of alphanumerics characters) separated with ":" example 00:11:22:33:44:55</td>
</tr>
<tr>
<td>-i / --interface</td>
<td>Put the interface which you wanna change the MAC, to know your interface use ifconfig.</td>
</tr>
</tbody>
</table>
<p><strong>Combination of arguments</strong>:<br />(examples only with short version but you can use long too)</p>
<ul>
<li>--help:<br /><span style="font-weight: 400;">python mac_changer --help</span></li>
<li>-i:<code>python3 mac_changer -i (your interface &ldquo;eth0&rdquo;)</code>
<li>-m:<code>python mac_changer -m 00:14:22:91:56:37</code>
<li>Your line should be like this:
  <code>python mac_changer -i (your interface &ldquo;eth0&rdquo;) -m (the new mac address &ldquo; 00:14:22:91:56:37&rdquo;)</code>
</ul>
