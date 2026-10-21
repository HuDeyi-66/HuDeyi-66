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

Die vier öffentlichen Skill-Repositories sind innerhalb ihrer genehmigten Veröffentlichungsumfänge synchronisiert. Die Basislaufzeit und die abgenommene ChenHai-Implementierung bleiben privat; WenHai bleibt ausschließlich lokal.

**Engineering-Status:** Die sechs Skills haben eine begrenzte, **interne V3.5-Abnahme** der synthetischen Integration unter getesteten Windows-/CPython-Konfigurationen bestanden. **Externes Benchmarking in V3.6 steht noch aus.** Dies ist weder eine unabhängige Begutachtung noch eine Zertifizierung juristischer Korrektheit, realer Korpusleistung oder Produktionsreife.

[SeaFlow-Architektur und die sechs Skills ansehen](https://hudeyi-66.github.io/seaflow-library-project-control/).

## 🧩 Die sechs SeaFlow-Skills

Alle sechs Skills sind gleichrangige SeaFlow-Module mit lokal implementierten, begrenzten Funktionen. Sie sind projektspezifisch; eine Kompatibilität mit Anthropic Agent Skills wird nicht behauptet. Code-Verfügbarkeit und interne Abnahme sind getrennt zu betrachten.

### 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — Juristische Textevidenz

**Kernfunktionen:** Structure, ResolveRefs, quelltreue Textsegmentierung und Rekonstruktion von Zitaten.

**Evidenzgrenze:** Quellstellen sind an die registrierte Textrepräsentation gebunden. Ein eindeutiger Quellbezeichner beweist weder juristische Verweisidentität noch juristische Richtigkeit.

**Quellcode-Status:** Öffentliches Quellrepository.

### 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — Tabellarische Evidenz

**Kernfunktionen:** ReconstructVerify, AccountLoss, Zellprovenienz und explizite Verlustangaben.

**Evidenzgrenze:** Die Prüfung gilt nur für unterstützte Eingaben und ausgewählte Belege; sie bestätigt nicht die Vollständigkeit einer gesamten Arbeitsmappe.

**Quellcode-Status:** Öffentliches Quellrepository.

### 🗂️ WenHai（海玟） — Dokumentarische Evidenz

**Kernfunktionen:** RegisterAsset · PreserveTranscript · SegmentEvidence · ExtractAdvice.

**Evidenzgrenze:** Textsegmente bewahren deklarierte Positionen und redaktionelle Ableitungen. Nicht vorgelegte Audioquellen, Sprecheridentität und Richtigkeit der Empfehlungen werden nicht zertifiziert.

**Quellcode-Status:** Ausschließlich lokales privates Repository; kein öffentlicher Quelllink.

### 🔎 ChenHai（海琛） — Evidenzsuffizienz und Prozessbewertung

**Kernfunktionen:** Φ Evidenzsuffizienz und Ψ Bewertung von Recherche und Prozess.

**Evidenzgrenze:** Fehlende Abdeckung und ungeklärte Herkunft bleiben sichtbar; eine Prozessbewertung ist keine juristische Korrektheitsprüfung.

**Quellcode-Status:** Abgenommene Implementierung privat; das öffentliche ChenHai-Erkundungsrepository ist ein gesonderter historischer Prototyp ([öffentlicher Explorationsprototyp](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill)).

### 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — Evidenz- und Provenienzgraph

**Kernfunktionen:** Γ Provenienzgraphen, typisierte Ereignisse, Aussagen und Registerprüfung.

**Evidenzgrenze:** Rechnerische Ableitung belegt weder juristische Verweisbeziehungen noch Kausalität oder unabhängige Bestätigung.

**Quellcode-Status:** Öffentliches Quellrepository.

### 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — Zeitliche Evidenz

**Kernfunktionen:** Zeitliche Zustandsbewertung, Planung erneuter Prüfungen und Zulassungsentscheidungen.

**Evidenzgrenze:** Unbekannte rechtliche Wirksamkeitszeitpunkte bleiben offen; Veröffentlichungs- oder Plandaten belegen keine Rechtswirksamkeit.

**Quellcode-Status:** Öffentliches Quellrepository.

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
