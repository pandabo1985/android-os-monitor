# Notice #
**This site is no longer to maintain, please go to the GitHub https://github.com/eolwral/OSMonitor**




---


**AndroidPIT Android Market** - Silver Award<br>
<a href='http://www.androidpit.com/en/android/tests/test/391874/OS-Monitor-Looking-Under-Your-Android-s-Hood'><img src='http://st01.androidpit.info/img/common/report_silver.png' /></a>

<h2>Introduction</h2>
<h4>OSMonitor is a small tool let you monitor your android phone.</h4>
<table><thead><th> <b>Process</b> </th><th> monitor all processes and display detail information about each. </th></thead><tbody>
<tr><td> <b>Network</b> </td><td> show every physical or logical network interface with statistics. </td></tr>
<tr><td> <b>Connection</b> </td><td> display every tcp or udp network connection, and query it via WHOIS ( require Google Map ) </td></tr>
<tr><td> <b>Misc</b> </td><td> monitor processor, battery and file system. </td></tr>
<tr><td> <b>Log</b> </td><td> check dmesg or logcat in real-time. </td></tr></tbody></table>

<b>Thanks to following translation contributors:</b>
<br>Brazilian Portuguese - Thanks to Alex Fiorani<br>
<br>Danish - Thanks to Kasper Kristensen<br>
<br>
<b>source code already upload via git, please check repository like below</b>
<table><thead><th> OSMonitor </th><th> <a href='http://code.google.com/p/android-os-monitor/source/browse/?repo=osmonitor'>http://code.google.com/p/android-os-monitor/source/browse/?repo=osmonitor</a> </th></thead><tbody>
<tr><td> OSMonitor-Tablet </td><td> <a href='http://code.google.com/p/android-os-monitor/source/browse/?repo=osmonitor-tablet'>http://code.google.com/p/android-os-monitor/source/browse/?repo=osmonitor-tablet</a> </td></tr></tbody></table>

<br>
<a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=eolwral%40gmail.com&lc=US&item_name=Support%20OSMonitor&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted'><img src='https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif' /></a>

Android 2.3.4 (HTC Magic)<br>
<br>
<img src='https://lh3.googleusercontent.com/-wpb5m7-ZsMk/TlA4RbG9JyI/AAAAAAAAAn4/QNNKnFD8VWc/s800/device-2011-08-21-061530.png'>

Android 3.1 (Motorola Xoom) <b>Tablet</b>
<br>
<img src='https://lh3.googleusercontent.com/-mlD9FP6fY8s/Tk7LQCJ4IOI/AAAAAAAAAmA/lE7udDxAJ0M/s800/Connection_Table.png'>


<br>
Whois API: <a href='http://en.utrace.de/'>locate IP addresses-utrace</a>
<br>

<h3>Changelog</h3>
<b>Table Version 1.0.2 (4-Sep-2011)</b>
<ul><li>add "Freeze" button on process. (Thanks to Jack Deslippe)<br>
</li><li>better preferences (Thanks to djdilicious)<br>
</li><li>add PSS Memory and start time for each process</li></ul>

<b>Version 2.0.5  (4-Sep-2011)</b>
<ul><li>fix nice function<br>
</li><li>display PSS memory (only support 2.0.1 above)<br>
</li><li>display start time for each process (thanks to Mike M'Cartney)<br>
</li><li>fix fc when press misc (thanks to Lucio Ferro)<br>
</li><li>fix minor fc (thanks to everyone who give me feedback!)<br>
</li><li>Translation<br>
<br>    Brazilian Portuguese - Thanks to Alex Fiorani<br>
<br>    Danish - Thanks to Kasper Kristensen</li></ul>

<b>Version 2.0.3  (28-Aug-2011)</b>
<ul><li>fix sorted column (thanks to Mike)</li></ul>

<b>Version 2.0.2  (28-Aug-2011)</b>
<ul><li>add uptime to misc tab (thanks to Florian)<br>
</li><li>fix wrong name with process ( thanks to Pascal and Christophe)<br>
</li><li>fix typo (status bar) (thanks to クロ)<br>
</li><li>fix fc when press misc (I hope) (thanks to BMay4 and andysweb)<br>
</li><li>restore freeze button from messages<br>
</li><li>fix minor fc (thanks to everyone who give me feedback!)</li></ul>

<b>Table Version 1.0.1 (21-Aug-2011)</b>
<ul><li>add "Kill" button (Thanks to Jack Deslippe)</li></ul>

<b>Table Version 1.0.0 (21-Aug-2011)</b>
<ul><li>beta version release!</li></ul>

<b>Version 2.0.1  (21-Aug-2011)</b>
<ul><li>back to old layout<br>
</li><li>add nice function (process)<br>
</li><li>remove some useless options (algorithm)<br>
</li><li>remove freeze button from messages (it won't refresh whole list after updating data.)<br>
</li><li>change default settings (sort, order and hide system process)<br>
</li><li>fix detect rooted function (from %s -> %s%s)<br>
</li><li>fix minor fc (thanks to everyone who give me feedback!)</li></ul>

<b>Version 2.0.0  (20-Aug-2011)</b>
<ul><li>change layout (for table and phone)<br>
</li><li>fix detect rooted function<br>
</li><li>fix minor fc (thanks to everyone who give me feedback!)</li></ul>

<b>Version 1.1.8  (28-Nov-2010)</b>
<ul><li>fix whois function <i>100 queries per day</i> (thanks to ferretty10 and John Johnson)<br>
</li><li>add freeze function to message tab (thanks to Kostya Maslyuk)<br>
</li><li>add slow adapter feature to process tab (optional) (thanks to jerry.asher)<br>
</li><li>add quick sort as default sort algorithm for process tab (thanks to jerry.asher)<br>
</li><li>fix minor fc</li></ul>

<b>Version 1.1.7  (15-Nov-2010)</b>
<ul><li>fix fc when press "Option" (use reflection to avoid crash on Cupcake Android 1.5)<br>
</li><li>force refresh after kill processes. (thanks to David B Harris)<br>
</li><li>Spanish language support. (thanks to Borja Berastegui)<br>
</li><li>dark-blue notification icon. (thanks to Florence Delville)<br>
</li><li>display own process for each connection.<br>
</li><li>support set cpu on boot (require rooted phone and enable auto-start, thanks to Milan Jaroš)<br>
</li><li>change way to check rooted. (thanks to Adwin Putteeraj)<br>
</li><li>fix layout with portrait</li></ul>

<br>