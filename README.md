# moatlens.app

Die Website zur Android-App **MoatLens** — Aktienanalyse und Fundamentalanalyse in
klarer Sprache, in vier Sprachen.

**Live:** <https://moatlens.app> · **App:** [Google Play](https://play.google.com/store/apps/details?id=com.nexihl.moatlens)

## Was hier liegt

Das **gebaute** Ergebnis, nicht der Generator. 196 Seiten, ausgeliefert über GitHub Pages:

| Bereich | Adresse |
|---|---|
| Startseite | <https://moatlens.app> |
| Lexikon — jede Kennzahl in Alltagssprache | <https://moatlens.app/lexikon.html> |
| Anleitung in acht Schritten | <https://moatlens.app/anleitung.html> |
| Magazin | <https://moatlens.app/magazin.html> |
| Presse & Creator | <https://moatlens.app/presse.html> |

Englisch, Französisch und Spanisch liegen unter `/en/`, `/fr/` und `/es/`; jede Seite
verweist per `hreflang` auf ihre Übersetzungen.

## Technik

Statische Seiten, kein Framework, kein Build-Schritt in diesem Repo. Ein Generator in
Python erzeugt alle Seiten aus einer Textquelle und den Sprachdateien der App — er liegt
bewusst außerhalb dieses Repos, hier steht ausschließlich das Ergebnis.

Hosting: GitHub Pages mit eigener Domain (`CNAME`), HTTPS erzwungen.

## Rechtliches

MoatLens ist **keine Anlageberatung**, sondern ein Analyse- und Lernwerkzeug. Es gibt
keine Kauf- oder Verkaufssignale und keine Kursziele.

Impressum, Datenschutz und Nutzungsbedingungen:
[nexihl-devOp/moatlens-legal](https://github.com/nexihl-devOp/moatlens-legal)
