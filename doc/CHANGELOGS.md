##Changelogs

**Changelog 0.0.4**

- erweiterte Functionen für letzte Version
- version install: cmb: mac updates, mac install, win updates, win install
- view version install: liest nun neue mbs aus
- fixed views: version template
- fixed functions: versions-functions, page-functions, features-functions

**Changelog 0.0.3**

- Auslagerungen der Funktionen als PlugIn
- functions:
  - page-functions,
  - versions-functions,
  - features-functions,
  - changelog-functions
- post_type: changelogs => clogs (Wordpress spert cpts mit "change" im namen!)
- cmb: mb fields für changelogs (<a href="https://github.com/McCouman/Ultraschall/blob/master/doc/cpt_mbs/mb_changelogs.md">siehe Änderungen </a>)
- Translation: DE|ENG über link
  - Übersetzungen über cookie-translation: (cookie_is(), get_translation()) ermöglicht die Ansichten der Seiten zu ändern (in deutsch oder englisch) über den link query: ...?translation=de. Vergibt einen Cookie und aktualisiert die Seite über redirect: action=1. Damit wird vermieden das der cookie erst nach erneuten aufruf der Seite aktiviert und ausgelesen werden kann.

**Changelog 0.0.2**

- wp functions: navigation,
- global functions: ultraschall-walker, ultraschall-bulks
- page container: box templates (page), page content(page), box templates(features)
- flex-fields: full (grid), half-half(grid), features(option: page)
- page-functions [standards]: get_page_content(), get_version_content(), get_feature(), get_cpt_features()
- post_types: team, features, versions, changelogs

**Changelog 0.0.1**

- Shortcodes: us_version, v_name, v_date
- Functions: Ultraschall NavWalker für collapsed Navigation
- Design: Navigation und Subnavigation
- Design: Header
- Header, Footer erstellt

**Changelog 0.0.0**

- started wp-ultraschall theme
- Ultraschall Namespace: us_ ....
