# MarktWissen Deutschland – Conversion Blueprint

## Ziel

Die deutsche Website soll nach der Freigabe durch das Affiliate-Programm möglichst viele **qualifizierte** Nutzer bis zum Registrierungsstart führen – ohne aggressive oder irreführende CFD-Werbung.

Dieses Dokument beschreibt die Conversion-Architektur vor Aktivierung des offiziellen Affiliate-Links. Es ist keine regulatorische Freigabe und ersetzt keine Prüfung durch Affiliate-Programm/Compliance.

## Wichtige Regel: offizieller Link fehlt noch

Der konkrete Affiliate-Link wird **erst vom Affiliate-Programm bereitgestellt bzw. freigegeben**.

Bis dahin:

- keine erfundenen oder geratenen URLs;
- keine Tracking-Parameter erfinden;
- keine Provider-Landingpage als aktiv bewerben;
- keine konkrete Anbieter-Risikowarnung mit geratenem Verlustprozentsatz einsetzen;
- keine nicht freigegebenen Banner, Logos oder Werbemittel veröffentlichen.

Nach Erhalt des offiziellen Materials wird nur dieses geprüft und an den vorgesehenen CTA-Stellen eingesetzt.

## Funnel

### 1. Suchintention

Primäre Einstiege:

- CFD Kosten Deutschland
- CFD Gebühren Deutschland
- CFD Spread Deutschland
- CFD Finanzierung / Overnight-Kosten
- CFD Hebel und Margin
- CFD Broker Kriterien
- CFD Vergleich Deutschland
- Erfahrungen mit CFD-Anbietern

Ziel ist nicht maximaler Traffic, sondern Besucher mit konkretem Entscheidungsinteresse.

### 2. Vertrauensphase

Jede kommerziell relevante Seite soll dem Nutzer vor einer externen Weiterleitung mindestens drei Dinge geben:

1. verständliche Erklärung des Problems;
2. konkrete Kriterien bzw. Checkliste;
3. klare Aussage, welche Information noch providerbezogen geprüft werden muss.

Vertrauensseiten:

- Methodik
- Affiliate-Transparenz
- Über MarktWissen
- Datenschutz
- Impressum
- Risiken

### 3. Vergleichsphase

Der zentrale Knotenpunkt ist `/de/cfd-vergleich-deutschland.html`.

Von dort soll der Nutzer nachvollziehbar zu:

- Kosten
- Gebühren
- Finanzierung
- Broker-Kriterien
- Anbieter-Kosten
- Anbieter-Erfahrungen

geführt werden.

Kein pauschales „bester Broker“. Stattdessen Entscheidung anhand von Kosten, Instrumenten, Finanzierung, Hebel/Margin, Ausführung und Schutz/Rechtsrahmen.

### 4. CTA-Phase

Vor Aktivierung des offiziellen Links:

- CTA bleibt informativ;
- kein falscher „Jetzt anmelden“-Link;
- keine vorgetäuschte Verfügbarkeit eines Partnerangebots.

Nach Freigabe:

- CTA wird mit dem **offiziell gelieferten Affiliate-Link** verbunden;
- Affiliate-Link wird als solcher transparent gekennzeichnet;
- technisches Link-Attribut `rel="sponsored"` verwenden;
- providerbezogene, aktuelle Risikowarnung wird exakt nach freigegebenem Material umgesetzt;
- Position und Darstellung der Warnung werden vor Veröffentlichung geprüft.

## Conversion-Prioritäten

### Priorität A – bestehende Seiten stärker machen

Keine Massenproduktion neuer Seiten. Zuerst die vorhandenen DE-Seiten so verbinden, dass ein Nutzer nicht in einer Sackgasse endet.

Besonders wichtig:

- Kosten → Vergleich
- Gebühren → Kosten / Vergleich
- Spread → Kosten / Vergleich
- Finanzierung → Vergleich
- Broker → Vergleich
- Anbieter-Kosten → Vergleich
- Anbieter-Erfahrungen → Vergleich
- Vergleich → Anbieter-Kosten / Anbieter-Erfahrungen / später offizieller CTA

### Priorität B – konkrete Entscheidungshilfe

Jede kommerziell relevante Seite sollte mindestens eine eigene Entscheidungshilfe enthalten, z. B.:

- Kosten-Checkliste
- 5-Minuten-Vergleich
- Fragen vor Kontoeröffnung
- Kriterien zur Bewertung von Erfahrungen
- Check der laufenden Finanzierungskosten

Das erhöht den Nutzwert ohne in aggressives Verkaufsmarketing umzuschlagen.

### Priorität C – CTA erst nach ausreichendem Kontext

Der erste CTA soll nicht direkt nach dem Hero stehen, wenn der Nutzer noch keine Orientierung hat.

Besser:

Problem → Erklärung → Beispiel/Kriterien → Checkliste → Vergleich → CTA.

Ein CTA darf zusätzlich am Ende einer Seite erscheinen, wenn der Nutzer die Entscheidungskriterien bereits gesehen hat.

## Messkonzept nach Aktivierung

Vorgesehene Ereignisse:

- `affiliate_cta_view`
- `affiliate_cta_click`
- `affiliate_outbound`
- `affiliate_registration`
- `qualified_trader`

Dimensionen:

- Quellseite
- Suchintention
- CTA-Position
- Gerät
- Zielseite
- freigegebene Creative-/Link-Version

Optimierungsziel:

**Qualified Outcome > Registration > Outbound Click > CTA Click > Pageview**

Nicht nur Klickrate optimieren. Ein hoher Klickanteil ohne qualifizierte Registrierungen ist kein gutes Conversion-Ergebnis.

## Compliance-Gate vor dem ersten aktiven Affiliate-CTA

Alle folgenden Punkte müssen erfüllt sein:

- [ ] deutsche Website/Source durch Affiliate-Programm freigegeben
- [ ] konkretes Marketingmaterial freigegeben
- [ ] konkreter Affiliate-Link/Tracking-Link geliefert
- [ ] Ziel-URL geprüft
- [ ] zuständige deutsche rechtliche Einheit / Produktbedingungen geprüft
- [ ] aktuelle providerbezogene Risikowarnung geliefert
- [ ] aktueller providerbezogener Verlustprozentsatz geliefert
- [ ] Warnung optisch und sprachlich korrekt umgesetzt
- [ ] keine verbotenen Boni/Rabatte/Referral-Incentives
- [ ] keine Gewinn-, Sicherheits- oder Erfolgsgarantien
- [ ] Affiliate-Beziehung klar erkennbar
- [ ] Link mit `rel="sponsored"` umgesetzt

BaFin weist ausdrücklich darauf hin, dass die Anforderungen an Risikowarnungen auch für Affiliate-/Partner-Marketing gelten. citeturn0search0turn0search12

## Was wir bewusst NICHT machen

- 500+ künstliche SEO-Seiten
- generische „Top Broker“-Listen ohne belastbare Methodik
- erfundene Preise/Spreads/Verlustquoten
- alte providerbezogene Risikowarnungen
- aggressive FOMO-Texte
- „schnell Geld verdienen“-Botschaften
- Bonus-/Cashback-/Freunde-werben-Mechaniken
- nicht freigegebene Plus500-Links oder Logos
- Vermischung von Deutschland und Österreich

## Nächste technische Schritte

1. DE-interne Links auf einen klaren Informations → Vergleich → CTA-Pfad prüfen.
2. CTA-Platzierung auf den wichtigsten kommerziellen Seiten vereinheitlichen.
3. Nach Erhalt des offiziellen Links nur diesen Link integrieren.
4. Providerwarnung exakt aus den freigegebenen Unterlagen übernehmen.
5. Nach Aktivierung CTA-Klicks und qualifizierte Ergebnisse messen.
6. Erst auf Basis realer Daten einzelne Seiten/CTAs optimieren.
