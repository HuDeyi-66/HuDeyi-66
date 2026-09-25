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

Die SeaFlow-Basislaufzeit wird privat gepflegt. Die öffentlichen Skills sind so
gestaltet, dass sie unabhängig davon nutzbar bleiben.

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

### 🔭 Geplante Skills (Reserved / Planned)

Die folgenden vier Skills sind **reserviert und geplant**. Ihre Repositories sind
die kanonischen künftigen Implementierungsorte und derzeit bewusst
dokumentationsorientiert: Die ersten Commits legen den Skill-Vertrag, die
architektonische Grenze und die geplante öffentliche Schnittstelle fest, bevor die
Implementierung beginnt. Funktionierende Funktionalität wird für sie noch nicht
beansprucht.

Zusammen beschreiben sie, wie Evidenz organisiert wird, nachdem sie gewonnen
wurde: **WenHai** registriert dauerhafte Dokumentenbestände, **XianHai** stellt
Evidenz und Ereignisse in die Zeit, **JueHai** verbindet beides über typisierte
Beziehungen und Herkunftspfade, und **ChenHai** beurteilt, ob die daraus
entstehende Evidenz ausreicht, und fordert Nachlieferung, wenn sie es nicht tut.

#### 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — Skill für zeitliche Evidenzorchestrierung

**XianHai** ordnet Evidenz in der Zeit.

- zeitliche Ordnung von Evidenz und Ereignissen; Ereignis-Zeitachsen
- Übergänge von Evidenzzuständen; Bewusstsein für zeitliche Gültigkeit und Veralterung
- Erkennung fehlender Zeiträume und zeitlicher Lücken; lückengetriebene Überprüfungs- und Nachlieferungsanfragen

Er erzeugt keine Evidenz, entscheidet keine juristischen Schlussfolgerungen und
ersetzt nicht das Auffinden von Quellen. Zeitachse und zeitliche Orchestrierung
gehören zu XianHai; allgemeine Evidenzbeziehungen und Herkunftspfade gehören zu
JueHai.

#### 🔎 [ChenHai（海琛）](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) — Skill für Evidenzerkundung und -bewertung

**ChenHai** fragt, ob die Evidenz ausreicht.

- Bewertung der Evidenzabdeckung; Erkennung von Unzulänglichkeit
- Signale für Recherche- und Trefferrisiko
- Bewertung von Precision und Recall anhand von Benchmarks, wenn qrels vorliegen; sonst Laufzeit-Proxywerte für die Abdeckung
- Identifikation ungelöster Evidenzlücken mit Empfehlungen für Wiederholung und Nachlieferung

Er recherchiert nicht selbst, erfindet keine fehlende Evidenz und füllt Lücken
nicht stillschweigend. ChenHai erkennt Unzulänglichkeit und fordert Nachlieferung
an; XianHai entscheidet über die Orchestrierung; Retrieval-Skills führen die
Recherche aus.

#### 🗂️ [WenHai（海玟）](https://github.com/HuDeyi-66/Wen_Hai_Files_Skill) — Skill für Dokumentenbestände

**WenHai** bewahrt Dokumente als dauerhafte Evidenzbestände.

- Registrierung von Dokumentenbeständen; dauerhafte Dateiidentität
- Bewahrung von Quellmetadaten; Verfolgung von Artefakten; Herkunft von Dokumenten
- stabile Dokumentreferenzen für nachgelagerte Skills

Zielmaterialien sind unter anderem Reden, politische Dokumente, Berichte,
öffentliche Erklärungen, Sitzungsprotokolle sowie institutionelle und
Unternehmensunterlagen. WenHai ist kein allgemeiner Dateimanager, kein Ersatz für
Cloud-Speicher und kein zeitlicher Reasoner.

#### 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — Skill für Evidenz- und Herkunftsgraphen

**JueHai** verbindet Evidenz über Beziehungen.

- typisierte Knoten für Evidenz, Behauptungen, Quellen und Ereignisse
- typisierte Relationen wie `supports`, `contradicts`, `derived_from`, `contained_in`, `references`, `corroborates`, `qualifies`
- Konstruktion von Herkunftspfaden und auditierbare Traversierung des Graphen

Er ersetzt keine universelle Knowledge-Graph-Plattform, verantwortet keine
zeitliche Orchestrierung, leitet keine ungestützten Kanten ab und verwandelt
Korrelation nicht stillschweigend in Evidenzstützung.

## 🧭 Wie ich diese Projekte denke

Eine wiederkehrende Struktur hinter meiner Arbeit ist:

**Soziale Wirklichkeit → Institutionen & Regeln → Evidenz → Informationssysteme → Künstliche Intelligenz**

Mich interessieren beide Richtungen dieser Kette:

- wie soziale und institutionelle Strukturen computational repräsentiert werden können;
- wie computationale Systeme die Produktion, Organisation und Nutzung von Evidenz verändern.

Hier überschneiden sich meine Interessen an **Rechtssoziologie, Künstlicher Intelligenz, Governance, Kritischer Soziologie und interkulturellen Studien**.

## 🛠 Ausgewählte Projekte

- 🌊 [SeaFlow](https://github.com/HuDeyi-66/SeaFlow) — öffentlicher Einstiegspunkt in das SeaFlow-Projekt und seine Architektur.
- 📘 [ShanHai（海珊）](https://github.com/HuDeyi-66/Shan_Hai_Code_Skill) — evidenzorientiertes Auffinden für Textquellen.
- 📊 [LuoHai（海珞）](https://github.com/HuDeyi-66/Luo_Hai_Tables_Skill) — evidenzorientierte Verarbeitung für strukturierte und tabellarische Quellen.
- 🧭 [SeaFlow Project Control](https://github.com/HuDeyi-66/seaflow-library-project-control) — öffentliche Projektsteuerungs- und Prüfseite für die SeaFlow-Entwicklung.
- 🕰️ [XianHai（海现）](https://github.com/HuDeyi-66/Xian_Hai_Time_Skill) — *Reserved / Planned* — zeitliche Evidenzorchestrierung: Evidenzzustände, Zeitachsen und zeitliche Lücken.
- 🔎 [ChenHai（海琛）](https://github.com/HuDeyi-66/Chen_Hai_Explore_Skill) — *Reserved / Planned* — Evidenzabdeckung, Erkennung von Unzulänglichkeit und Nachlieferungsempfehlungen.
- 🗂️ [WenHai（海玟）](https://github.com/HuDeyi-66/Wen_Hai_Files_Skill) — *Reserved / Planned* — Erfassung dauerhafter Dokumentenbestände und Herkunft von Dokumenten.
- 🕸️ [JueHai（海珏）](https://github.com/HuDeyi-66/Jue_Hai_Graph_Skill) — *Reserved / Planned* — herkunftsbewusste Evidenzgraphen mit typisierten Knoten und Relationen.

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
