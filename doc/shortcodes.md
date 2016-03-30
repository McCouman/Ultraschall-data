# Shortcodes
Hier kommen nach und nach, alle shortcodes die so benötigt werden.

<code>us_&lt;Shortcode-name></code> das us steht für ultraschall :D

#### Globale Shortcode
Es wird eine Erweiterungspaket benötigt!
**Beachte:** dieses PlugIn kann nicht unter MIT veröffentlicht
werden und ist daher nicht in diesem Umfang enthalten.


//**Ultraschall Version:  plugin benötigt! (nicht im Umfang enthalten!)**

Liest die in den Einstellungen eingegebene Version aus.

<pre>
[us_version] => 2.0
[us_version name="1"] => 2.0 Gropius
[us_version date="1"] => 2.0 - 9.12.2015
[us_version text="Version"] => Version 2.0

[us_version name="1" date="1" text="Version"] => Version 2.0 Gropius – 9.12.2015
</pre>

//**Ultraschall Name:  plugin benötigt! (nicht im Umfang enthalten!)**

Liest die in den Einstellungen eingegebene Version aus.

<pre>
[v_name] => Gropius
</pre>

//**Ultraschall Datum:  plugin benötigt! (nicht im Umfang enthalten!)**

Liest die in den Einstellungen eingegebene Version aus.

<pre>
[v_date] => 12.09.2015
</pre>


//**Ultraschall Download Button:  plugin benötigt! (nicht im Umfang enthalten!)**
###### automatischer Download -Button oder -Link

Nimmt die Daten aus den globalen Einstellungen und erzeugt einen Downloadlink.
Es wird versucht das Betriebssystem zu ermitteln und gibt automatisch die
Mac/Windows Version frei. Es enthält einen Zusatz (+) um sich umzuentscheiden.

<pre>
[us_download] => (Link/Button) &lt;a href="..." ... >Download (Mac)</a>
[us_download version="1"] => &lt;a href="..." ... >Download 2.0 (Mac)</a>
[us_download button="1"] => &lt;button ... >Download (Win)</button>
[us_download plus="1"] => &lt;button ... >Download (Win) | {+}</button>

Buttonfarbe ändern (ist nun rot)
[us_download color="#f00"] => &lt;a href="..." ... >Download (Win)</a>
</pre>


######  händischer Download -Button oder -Link

Nimmt die daten aus den globalen Einstellungen.

<pre>
[us_download type="mac"] => &lt;a href=".../$/mac.zip" title="Do... 2.0 Gropius for Mac">Download</a>
[us_download type="win"] => &lt;a href=".../$/win.zip" title="Do... 2.0 Gropius for Windows">Download</a>
</pre>

----

//**Ultraschall Referenzen:  plugin benötigt! (nicht im Umfang enthalten!)**
###### Ausgabe der Referenzen

... infos kommen noch! ...
<pre>
[us_referenzen int="10"] //letzten 10 Referenzen

[us_referenzen int="10" slider="1"] //letzten 10 Referenzen als Slider

[us_referenzen int="10" rand="1"] //letzten 10 Referenzen als Random

</pre>


----

//**Ultraschall Changelogs:  plugin benötigt! (nicht im Umfang enthalten!)**
###### Ausgabe der Changelogs

... infos kommen noch! ...
<pre>
[us_changelog int="10"] //letzten 10 Changelog

...
</pre>


----

#### YouTube RSS Button Shortcode

<pre>
//standalone
[us_yt

rss="https://....youtube..." //vielleicht einfach nur Username?
name="(YouTube) RSS Abonnieren" 

]
</pre>

----


#### Team Shortcode

<pre>
//standalone
[us_team

name="Hubert"
image="http://domain.tld/image.jpg" (max.: 400px|400px)
description="laber dings über hubert"

adn="http://domain.tld"
twitter="http://domain.tld"
github="http://domain.tld"
web="http://domain.tld"

]
</pre>

----

#### Div Boxing
Standard Boxen:

1.) DIV (@width: large, middle, standard, optional | @background-color: white, primary, grey, dark, optional)

2.) DIV (@background (url) image)

<pre>
//standalone
[us_box

 ==1==
 width="656"            //large, middle, standard, int(100)px
 background-color="f00" //white, primary, grey, dark, string #(f00)

 ==2==
 background="http://domain.tld/imgae/jpg" //background image url
 margin-top=""        //small, big, large, int(20/-20)px
 margin-bottom=""     //small, big, large, int(20/-20)px
 line-top=""          //center (img), border (css)
 line-bottom=""       //center (img), border (css)

]

... [us_grid rows="center" content-left=" $... "] ...

[/us_box]
</pre>

----

#### Easy Grids
Standard Grids:

3.) DIV grid/container

4.) DIV rows

<pre>
//easy grid - mehr wird vielleicht nicht benötigt :P
[us_grid

 rows="img-left-small"  //img-left-small, img-left-large | img-right-small, img-right-large | center
 content-left=" $... "  //@info: center oder linker content
 content-right=" $... " //@info: rechter content (wenn center = egal)

]
</pre>
