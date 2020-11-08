## Getting Started with Phaser

Phaser is a Javascript Game Framework
<br>
Phaser can use both Canvas or WebGL depending on browser support
<br>
You can compile phaser games to iOS or Android using things such as Apache Cordova
[Example](https://gamedevacademy.org/creating-mobile-games-with-phaser-3-and-cordova/)
<br><br>
This project just covers getting an example working using the framework, the next project, "Making your first phaser game - 2018" (followed by the 2020 version) will explain methods step by step
<br>
<br>
Issue tracker:
<br>
Issue: "Mixed content error"<br>
Fix: this.load.setBaseURL("http://labs.phaser.io");<br>
Change to HTTPS like:<br>
this.load.setBaseURL("https://labs.phaser.io");
