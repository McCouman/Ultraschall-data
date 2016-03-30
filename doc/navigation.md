# Navigation:
**Vorschau**

<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/navigation.png">

###### download buttons
<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/mac.png">
<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/win.png">
<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/mac-c.png">
<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/win-c.png">


**Grundgerüst:**
- *Allgemeines:*
 - collapsed Navigation: Es sollte auf "Aufklappmechanismen" in der Hauptnavigation verzeichtet werden! Da weiterführende Informatioen als collap. Navigation, zu einer Informationsüberflutung führen würde. Dies nimmt den Fokus auf das Projekt. Es ist daher nicht dienlich.
 - Untermenüs: Es sollte ein eigenes Untermenü als "Zusatznavigations" eingesetzt werden. Damit nimmt man die komplexität hinter den Seiten (zeigt Offenheit ünd versucht nichts zu verstecken - fördert Communitygedanke, macht Aussage glaubhafter für den Leser der Seite).

- *Navigation*
 - *Hauptnavigation: (Ausrichtung)*
   - Links: Ultraschall Logo
    - Rechts: Navigationen

 - *Hauptnavigation: (Farbe)*
   - eher ein dunkles grau/midnight black um nicht von den Bildern und Infos abzulenken

 - *Subnavigation: (Ausrichtung)*
   - Links: Name der Seite
    - Rechts: Subnavigationen
    - Rechts Ende: YouTube / Github Buttons um auf Externe Resourcen hinzuweisen.

 - *Subnavigation: (Farbe)*
   - eher ein helleres grau - hat offener Wirkung, lengt jedoch nicht durch Farbe von den Bildern ab.

- *Content*
 - Aufbau in Blockbereiche

- *Footer*
 - Übersicht der Seiten (vielleicht ohne Seitenunterbrechung nutzen, um Bruch mit der Seite zu vermeiden und Übersichtlichkeit weiter zu erhöhen)
 - dark footer mit Impressum & Co (+ Berlin Logo?)

#### Naviagtion (construction):

**Jetzt**
<pre>
|- Home
|- Blog
|- Download
|- Github
|- Referenzen
|- Tutorials
|- Community
|- Kompatibilität
</pre>

**Neu**
<pre>
|- Home
  1. Header Navigation (ohne Subnavigation!)
  --
  2. Big Ultraschall Image ( vielleicht in dunkel? :D )
  3. Infos: zur aktuellen Version => gemacht für (Mac | Windows)
  4. Referenzen: Podcaster Sliedes
  5. Team: (überlegen ob wirklich so gut?!)
  --
  6. Footer: sitelists
  7. Footer end

|- Blog

|- Anleitungen
     |- Features (Beschreibt kurz die Funktionen => klickbares Ultraschall mit Infos & WebPlayer)
     |- Vorbereitung
     |- Aufnahmen
     |- Produktion

|- Screencast (YouTube Page / automationsseite über den Feed)
  1. Header Navigation (ohne Subnavigation!)
  --
  2. Big Ultraschall YouTube (klicken auf letzte Folge zeigt YT-Video über Modal)
  3. Letzten Folgen (vielleicht als Kategorie Gallery möglich?) + Feed Abonnieren Button
  --
  4. Footer: sitelists
  5. Footer end

|- Referenzen
  1. Header Navigation (ohne Subnavigation!)
  --
  2. Ralf sein Twitter Dings (über iframe einbinden)
  3. Podcasts die Ultraschall schon einsetzen...
  --
  4. Footer: sitelists
  5. Footer end

|- Community
  1. Header Navigation (ohne Subnavigation!)
  --
  2. Big Ultraschall Image von Sendegate Forum (Merke: was gar kein Form ist!)
  3. Infos und so + direkter Link zum SendegatForm
  --
  4. Footer: sitelists
  5. Footer end

|- [ Download | 2.0 ] //als Button anzeigen mit Versions-Nr.
       |- Installation (als >>switscher<< menu [fade in effect] in der Mitte => Appel|Windows)
       |- Changelog
       |- Kompatibilität { Subnavi }
       |- (4 th-large Icon) title: Versionen (de) / History (eng)
             |- Version 2.0 - Übersichtsseiten mit Infos der letzten Releases aus der V2.0
             |- Version 1.0 - Übersichtsseiten mit Infos der letzten Releases aus der V1.0

------------
Subnavi

left:
|- Name:...

right:
|- Submenu: [ Link | Name ]
|- ...
...
|- YouTube (Link zu YouTube)
|- Github (link to Github)
</pre>
