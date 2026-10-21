[English](README.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [日本語](README.ja.md)

# Hi, ich bin Hu Deyi 👋

## ⚓ Über mich

Ich studiere im Bachelor an der **Dalian Maritime University** im Studiengang
**Englisch (Foreign-related Rule of Law — Recht mit Auslandsbezug)**.

Ich arbeite und experimentiere an der Schnittstelle von **Sozialforschung,
künstlicher Intelligenz, Governance und Informationssystemen**.

Meine aktuellen Interessen lassen sich in fünf Bereichen zusammenfassen:

- ⚖️ **Rechtssoziologie**
- 🤖 **Künstliche Intelligenz**
- 🏛️ **Governance**
- 🔍 **Kritische Soziologie**
- 🌏 **Interkulturelle Studien**

Besonders interessiert mich, wie Institutionen, Regeln, Evidenz, Technologien und
soziale Strukturen zusammenwirken — und wie sich einige dieser Beziehungen in
Systeme übersetzen lassen, die **auffindbar, strukturiert, überprüfbar und
wiederverwendbar** sind.

## Forschungsinteressen

`Rechtssoziologie` · `Künstliche Intelligenz` · `Governance` ·
`Kritische Soziologie` · `Interkulturelle Studien`

## 🌊 Woran ich arbeite

### [SeaFlow](https://github.com/HuDeyi-66/SeaFlow)

**SeaFlow** ist mein langfristiges Projekt für juristische KI und
Evidenzinfrastruktur.

Es untersucht, wie heterogene Quellen in verlässliche, nachvollziehbare und
maschinell nutzbare Evidenz überführt werden können, ohne Herkunft, Zitat und
Evidenzgrenzen aufzugeben.

Aktuelle Prinzipien:

> **Evidence First · Traceable Sources · Small Core · Extensible Skills**

Die Basislaufzeit bleibt privat. Öffentliche Repository-Stände können hinter den lokal abgenommenen Implementierungen zurückliegen; ChenHai und WenHai haben zusätzliche Vertraulichkeitsgrenzen.

**Engineering-Status:** Die sechs Skills haben eine begrenzte, **interne V3.5-Abnahme** der synthetischen Integration unter getesteten Windows-/CPython-Konfigurationen bestanden. **Externes Benchmarking in V3.6 steht noch aus.** Dies ist weder eine unabhängige Begutachtung noch eine Zertifizierung juristischer Korrektheit, realer Korpusleistung oder Produktionsreife.

[SeaFlow-Architektur und die sechs Skills ansehen](https://hudeyi-66.github.io/seaflow-library-project-control/).

### 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — Skill für juristische Textevidenz

**ShanHai** ist ein quelloffener, eigenständig nutzbarer Skill für juristische
Textevidenz.

Schwerpunkte:

- Auffinden der Quelle
- exakte Textextraktion
- Erkennung der Struktur
- native Textzitate
- Umgang mit Mehrdeutigkeit
- ausdrückliche Verweigerung, wenn die Evidenz nicht ausreicht

Das Kernprinzip lautet:

> **Erst die Quelle finden, dann die Frage beantworten.**

ShanHai ist unabhängig von der privaten SeaFlow-Basislaufzeit nutzbar.

### 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — Skill für tabellarische Evidenz

**LuoHai** ist ein quelloffener, eigenständig nutzbarer Skill für strukturierte
und tabellarische Evidenz.

Er ist auf heterogene Tabellen, Berichte, Übersichten und strukturierte
Datensätze ausgelegt und wahrt dabei die Grenzen der Quelle und ihre
Nachvollziehbarkeit.

Das Kernprinzip lautet:

> **Evidenz organisieren ≠ Evidenz erzeugen.**

LuoHai ist unabhängig von der privaten SeaFlow-Basislaufzeit nutzbar.

### 🧩 Vier weitere SeaFlow-Skills — lokal implementiert

Alle sechs SeaFlow-Skills verfügen inzwischen über eigenständige lokale Implementierungen. Es handelt sich um projektspezifische Module; damit wird keine Kompatibilität mit Anthropic Agent Skills behauptet. Öffentliche Sichtbarkeit und technische Abnahme sind zu unterscheiden.

#### 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — Zeitbezogene Evidenz

XianHai verarbeitet zeitliche Evidenzzustände, Pläne zur erneuten Prüfung und Zulassungsentscheidungen. Unbekannte oder widersprüchliche Wirksamkeitszeitpunkte bleiben offen; Veröffentlichungsdaten belegen keine rechtliche Geltung.

#### 🔎 ChenHai（海琛） — Evidenzsuffizienz und Prozessbewertung

ChenHai trennt Evidenzsuffizienz (Φ) von Recherche- und Prozessbewertung (Ψ). Fehlende Abdeckung, ungeklärte Herkunft und gemeinsame Quellen werden nicht stillschweigend zu ausreichender Evidenz.

Die **abgenommene Implementierung ist privat**. Das öffentliche [ChenHai-Explorationsrepository](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) ist ein eigenständiger historischer Prototyp und nicht die aktuelle Implementierung.

#### 🗂️ WenHai（海玟） — Dokumentarische Evidenz

WenHai stellt `RegisterAsset`, `PreserveTranscript`, `SegmentEvidence` und `ExtractAdvice` bereit. Quellenidentität und redaktionelle Bearbeitung bleiben nachvollziehbar; von Menschen geprüfte Empfehlungen sind Vorschläge, keine automatisch genehmigten Anforderungen.

Das Repository bleibt **ausschließlich lokal und privat**; es gibt kein öffentliches GitHub-Repository. Unverfügbare Audioaufnahmen, Sprecheridentitäten und die Richtigkeit von Empfehlungen werden nicht zertifiziert.

#### 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — Evidenz- und Provenienzgraph

JueHai bietet typisierte Provenienzgraphen (Γ) sowie Funktionen für Aussagen und deren Registrierung. Rechnerische Herkunft belegt weder juristische Verweisbeziehungen noch Kausalität oder unabhängige Bestätigung.

## 🧭 Wie ich diese Projekte denke

Eine wiederkehrende Struktur hinter meiner Arbeit ist:

**Soziale Wirklichkeit → Institutionen & Regeln → Evidenz → Informationssysteme → Künstliche Intelligenz**

Mich interessieren beide Richtungen dieser Kette:

- wie soziale und institutionelle Strukturen computational repräsentiert werden können;
- wie computationale Systeme die Produktion, Organisation und Nutzung von Evidenz verändern.

Hier überschneiden sich meine Interessen an **Rechtssoziologie, Künstlicher Intelligenz, Governance, Kritischer Soziologie und interkulturellen Studien**.

## 🛠 Ausgewählte Projekte

- 🌊 [SeaFlow](https://github.com/HuDeyi-66/SeaFlow) — öffentlicher Projekteinstieg und Architektur.
- 🧭 [SeaFlow-Showcase](https://hudeyi-66.github.io/seaflow-library-project-control/) — sechs Skills, Abnahmeumfang und Grenzen.
- 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — juristische Texte, Strukturbeobachtungen und Verweiskandidaten.
- 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — prüfbare tabellarische Evidenz und explizite Verlustangaben.
- 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — begrenzte zeitliche Evidenzentscheidungen.
- 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — Evidenzbeziehungen und rechnerische Provenienz.
- 🔎 **ChenHai（海琛）** — abgenommene Implementierung privat; [öffentlicher Explorationsprototyp](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) ist getrennt.
- 🗂️ **WenHai（海玟）** — lokaler, privater Skill für dokumentarische Evidenz; kein öffentliches Repository.

## 📖 Forschung × Engineering

Ich verstehe Forschung und Engineering als verbundene Teile desselben Prozesses:

> **Beobachten → Verstehen → Formalisieren → Bauen → Überprüfen**

Forschung hilft, Strukturen zu erkennen, auf die es ankommt.

Engineering zwingt diese Strukturen, explizit zu werden.

Ist ein System gebaut, zeigen seine Grenzen oft neue Forschungsfragen auf.

Einige Repositories hier sind stabile Werkzeuge.
Einige sind Forschungsprototypen.
Einige sind Experimente.

Zusammen dokumentieren sie, wie Ideen allmählich zu Systemen werden.

## 🌱 Aktuell erkunde ich

- evidenzorientierte KI-Systeme
- Retrieval und Herkunft
- modulare KI-Skills
- leichte und lokale Modelle
- multimodale Forschungsabläufe
- KI-gestützte Forschungsinfrastruktur
- die gesellschaftlichen Folgen intelligenter Systeme

## 🤖 Modelle, mit denen ich häufig arbeite

`GPT` · `DeepSeek` · `Kimi`

## 🧩 Fünf Schlagworte

**⚖️ Rechtssoziologie**
Institutionen, Regeln, Rechtspraxis und ihr Verhältnis zu sozialen Strukturen.

**🤖 Künstliche Intelligenz**
Retrieval, Agenten, Sprachmodelle, Evidenzsysteme und Mensch-KI-Interaktion.

**🏛️ Governance**
Institutionelles Design, Koordination, Regulierung und die Governance emergenter Technologien.

**🔍 Kritische Soziologie**
Macht, Institutionen, Technik, soziale Struktur und die Annahmen, die in scheinbar neutralen Systemen stecken.

**🌏 Interkulturelle Studien**
Wie Bedeutung, Normen und Institutionen über Sprachen, Rechtskulturen und soziale Kontexte wandern.

## Was ich erkunde

Wie juristische und soziale Forschung mit KI arbeiten kann, ohne die Evidenzkette
hinter der Antwort zu verbergen.
