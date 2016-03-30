#Anforderungen und Ideen zum Design

### Frontend
 - möglichst flaches Design
 - in graustufen haltend
 - JS/CSS Effekte sollen Ultraschall auch auf der Website wiederspiegeln (mögliche Infofunktionen der Website)
 - vielleicht einen WebPlayer zum Absielen der Schnittmarken?
 - große Bilder / große Schrift (grauer Untertitel) / dosserierte Schriftverläufe (siehe Ultraschall Schrift - fine/bold)
 - Ultraschall Buttons als Fonts: zum einfachen wiederverwenden, erklären und um Ladezeiten zu veringern
 - möglichst flex und grid verwenden
 - vielleicht ultra-timer als feature einbauen :)

### Backend
 - Global TAB: Allgemein zur Version: (für globale Nutzung Shortcodes)
   - Field: input (string) version number [2.0.1234] | *version* {{ global@version }}
    - Field: input (string) Release Name [Gropius] | *version* {{ global@version_name }}
    - Field: datepicker (string) last version- / release date [01.12.2015] | *version_date* {{ global@version_date }}
    - Field: url (string) Link zum Download / Mac | *version_downloadUrl_mac* {{ global@version_downloadUrl_mac }}
    - Field: url (string) Link zum Download / Windows | *version_downloadUrl_win* {{ global@version_downloadUrl_win }}
    - ...

 - Global TAB: Page Settings:
   - Field: colorpicker (String) global color [#ff0000] | *color* {{ global@color }}
    - ...

## Boxen

Standard Boxen:

1.) DIV (@width: large, middle, standard | @background-color: white, primary, grey, dark)
2.) DIV (@background (url) image)
3.) DIV grid/container
4.) DIV rows
