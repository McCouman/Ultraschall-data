# Neue Post_Types (PlugIn!):

### Global Settings: [ admin_cpt: ultraschall_settings | MB: Einstellungen ]

Hier können die Grundfunktionen des Themes eingestellt werden.
Dies enthält auch die Daten für die global nutzbaren Shortcodes.

###### Vorschau
<img src="https://raw.githubusercontent.com/McCouman/Ultraschall/master/doc/img/post_type-1.png">

----


### Versionen: [ cpt: ultraschall_versions | MB: Home, Installationsanleitung ]

Hier werden die Versionen beschreiben und werden am Ende Übersetzt.
Sie werden automatisch in über ein Template eingebunden. Damit spart man sich die
Arbeit und weis immer wo man ein neues Release freigibt. Mehr Infos kommen dann im Blog,
falls es Änderungen gibt.

<pre>
Aufbau einer Versionsseite mit allen Informationen (de/eng)
- MB: Home => [de|eng] (Hier werden die Neusten Features kurz vorgestellt und mit Bild/text erklärt.)
- MB: Installation => mac [de][eng] | windows [de][eng]
 _MB: !Changelogs => [de][eng] (noch Fragwürdig ob nicht einfacher geht um global weiter zu nutzen?
vielleicht als Kategorien?)_
</pre>

- <a href="https://github.com/McCouman/Ultraschall/blob/master/doc/cpt_mbs/mb_version.md">MB: US_Versions</a>


----


### Changelogs: [ cpt: ultraschall_changelogs | MB: Changelog ]

Hier werden die Changlogs verfast... (in Arbeit!)

<pre>
Aufbau einer Versionsseite mit allen Informationen (de/eng)
- MB: !Changelogs => [de][eng] (noch Fragwürdig ob nicht einfacher geht um global weiter zu nutzen? vielleicht als Kategorien?)
</pre>

- <a href="https://github.com/McCouman/Ultraschall/blob/master/doc/cpt_mbs/mb_changelogs.md">MB: US_Changelogs</a>


----


### Referenzen: [ cpt: ultraschall_references | MB: Referenzen ]

Hier werden die Podcasts mit ihren Referenzen/Clients erfast ... (in Arbeit!)

<pre>
MB: Referenzen Podcasts => [de][eng]

- Field: Name (string) | *podcast_name* {{ ultraschall_referenzen@podcast_name }}
- Field: Link (string) | *podcast_url* {{ ultraschall_referenzen@podcast_url }}
- Field: Cover (string) | *podcast_poster* {{ ultraschall_referenzen@podcast_poster }}
</pre>

- <a href="https://github.com/McCouman/Ultraschall/blob/master/doc/cpt_mbs/mb_references.md">MB: US_References</a>


----


### Team: [ cpt: ultraschall_team | MB: Team ]

<pre>
MB: Team (Personenangaben): (Aufbau einer Teamseite zur Nutzung als Shortcode)

- Field: Name (string) | *user_name* {{ ultraschall_team@user_name }}
- Field: Description (string) | *user_infos* {{ ultraschall_team@user_infos }} (ist fragwürdig ob nötig, macht aber viel Sinn!)
- Field: Social-Networks (dropdown = key : value) | *user_socials[]* {{ ultraschall_team@user_socials[] }}
 * adn : ADN
 * twitter : Twitter
 * github : Github
 * web : Website
 * xing : Xing (last uns auch auch mal wo anderes reden... /*hust*/)
 * ... was weis ich denn noch ...
</pre>

- <a href="https://github.com/McCouman/Ultraschall/blob/master/doc/cpt_mbs/mb_team.md">MB: US_Team</a>


----


###### IDEE: später vielleicht nach den Tests - wenn wirklich nötig!
<pre>
- Screencasts: (Wenn nicht möglich über den Feed / sollte jedoch erst später überlegt werden)
</pre>
