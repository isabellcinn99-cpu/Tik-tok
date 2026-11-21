# Video-Vorlage – Skript & Prompts

> **Lebende Vorlage.** Gerüst für jedes Video der Reihe. Muster-Beispiel: `skripte/02-widder-ehrlich.md`.
> Regeln (Länge, Hook, Dramaturgie, Stil) stehen im Skill `.claude/skills/astro-psychologie-videos/SKILL.md` und gehen immer vor. Wird die Vorlage verbessert (z. B. nach neuen Referenzbildern), unten im **Änderungsprotokoll** eintragen.
> Platzhalter stehen in `[ECKIGEN KLAMMERN]`.

---

# [ZEICHEN]-Video – Skript & Prompts

[DATUM] · @Isabell

## Überblick

Ein [ZEICHEN]-Video, ca. [LÄNGE] Sekunden, [FORMAT], gesprochen von Clara. Kernaussage: [EIN SATZ: das Missverständnis über das Zeichen und die psychologische Wahrheit dahinter].

| Eckdaten | Wert |
|---|---|
| Phase | [1: 25–30 s / 65–80 Wörter · 2: über 60 s / 150–175 Wörter] (Skill, Regel F5) |
| Format | [16:9 oder 9:16], 1080p |
| Länge | ca. [X–Y] s |
| Wörter | [ANZAHL] |
| Szenen | [N] Bilder → [N] Clips, Schnitt alle ca. 2–3 s |
| Stimme | Clara Modern Narration – Calm & Clear (ElevenLabs, Eleven v3) |
| Bildstil | Röntgen-Hologramme: [ZEICHEN] als [TIER/FIGUR] mit [AKZENTFARBE]em Kern, das Gegenüber als menschliche Röntgen-Figur; [AKZENTFARBE] als einzige Akzentfarbe |
| Psychologie-Begriff | [BEGRIFF] – [Erklärung in einem Satz] |

**Woran wir erkennen, dass das Video gut ist:** Der Hook ist nach höchstens 1,5–2,5 s gesagt. Jeder Satz hat ein eigenes Bild. Es gibt eine überraschende Pointe und einen Schlusssatz zum Speichern. Am Ende steht ein CTA, der Kommentare auslöst.

**Workflow**

1. Stimme in ElevenLabs erzeugen (Abschnitt „ElevenLabs“). So steht das echte Timing fest.
2. [N] Bilder erzeugen (Nano Banana oder Higgsfield). Dabei jedes Mal das Hook-Bild als Referenz hochladen.
3. Jedes Bild als Startbild animieren (Grok Imagine oder Higgsfield), 3–6 s pro Clip.
4. In CapCut Audio und Clips zusammenschneiden, Wort-für-Wort-Untertitel und Musik dazu.

> Wird über Higgsfield generiert (Skill, Regel F4): vorher mit `higgsfield generate cost …` die Kosten ermitteln und der Creatorin Modell, Prompt/Einstellungen, **Credits pro Stück und gesamt** sowie den Kontostand zeigen. Erst nach ihrem „Ja“ generieren. Jeder neue Versuch und jede Änderung braucht eine neue Freigabe.

## Hook-Varianten

| # | Muster (Skill §2) | Hook |
|---|---|---|
| 1 | Provokante Identitäts-These | [HOOK] |
| 2 | „Kennst du das?“-Szene | [HOOK] |
| 3 | „Bist du schon mal …“-Frage | [HOOK] |

**Empfehlung:** [#] – [warum].

## Skript

Formel: Hook mit Widerspruch → Wiedererkennung → psychologisches Warum → Wendung („Was dir niemand sagt“) → überraschende Pointe → Schlusssatz zum Speichern → CTA.

**Zum Lesen am Stück:**

> [GANZES SKRIPT]

**Szenen und Timing** (geschätzt bei Tempo 1,1; nach der Sprachaufnahme an die echte Tonspur anpassen):

| # | Zeit | Block (Skill §3) | Gesprochen | Bild | Wort in [AKZENTFARBE] |
|---|---|---|---|---|---|
| 1 | 0,0–1,5 s | Hook | [SATZ] | [BILD] | [WORT] |
| … | | | | | |

**Wortzahl:** [ANZAHL] Wörter.

Wird die Aufnahme zu lang: zuerst Tempo auf 1,15, dann Tonspur in CapCut auf 1,1x, dann [STREICHKANDIDAT: Satz + Szene] streichen.

## ElevenLabs

Clara mit dem Modell Eleven v3. Regieanweisungen in eckigen Klammern werden nicht mitgesprochen.

**Text zum Einfügen:**

```
[serious] [SKRIPT MIT REGIEANWEISUNGEN: [serious], [amused], [softly], [whispers]; ein Wort in GROSSBUCHSTABEN für Betonung]
```

**Einstellungen:**

| Einstellung | Wert | Warum |
|---|---|---|
| Stimme | Clara Modern Narration – Calm & Clear | feste Account-Stimme |
| Modell | Eleven v3 | Regieanweisungen funktionieren nur hier |
| Stability | Natural (klingt es flach: Creative) | Robust ignoriert die Anweisungen weitgehend |
| Speed | 1,1 | gegen den Meditations-Effekt |
| Takes | 3–4 erzeugen | die Anweisungen wirken nicht jedes Mal gleich |

**So prüfst du die Aufnahme:**

- Länge [X–Y] s.
- Beim Wendepunkt („[WENDESATZ]“) wird sie hörbar leiser.
- [WEITERER PRÜFPUNKT, z. B. Tonfall einer Pointe]
- Passt ein Satz in keinem Take: nur diesen Satz neu erzeugen und in CapCut austauschen. [whispers] zu leise → [softly].

Mit Multilingual v2: alle eckigen Klammern löschen. Stability 35 %, Similarity 75 %, Style 25 %, Speed 1,1.

## Bild-Prompts

Hauptfigur: [BESCHREIBUNG DER FIGUR DES ZEICHENS]. Gegenüber: [BESCHREIBUNG], ohne [AKZENTFARBE]en Kern. So bleibt [AKZENTFARBE] immer das Zeichen von [ZEICHEN].

**So gehst du vor:**

- Bei jedem Bild das **Hook-Bild** als Referenz hochladen. Es legt Stil und Figur fest.
- Ab Bild 3 zusätzlich **Bild 2** hochladen, wenn das Gegenüber vorkommt.
- Seitenverhältnis auf **[FORMAT]** stellen.
- Prompts auf Englisch.

**Fester Stil-Baustein** (an jeden Prompt anhängen, Farbe anpassen):

```
Style: exactly the look of the reference image: cinematic 3D render, [16:9 widescreen | 9:16 vertical], starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray hologram bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is [ACCENT COLOR]. No text, no letters, no logos, no watermark.
```

**Bild [N] – [TITEL]**

```
Use the attached [FIGURE] image as the reference for the [FIGURE] and the style[, and the attached [COUNTERPART] image for the [COUNTERPART]]. New scene: [EINSTELLUNG + WAS PASSIERT, wörtlich passend zum Satz]. [Mouth closed.] [STIL-BAUSTEIN]
```

## Clip-Prompts (Image-to-Video)

Jeder Clip hat ein eigenes **Ereignis** und eine eigene **Kamerabewegung**. Keine zwei Clips hintereinander bewegen sich gleich. Ein Clip kurz vor dem Ende ist bewusst ruhig (Kontrast).

| Clip | Kamera | Ereignis |
|---|---|---|
| 1 | [KAMERA] | [EREIGNIS] |
| … | | |

**Einstellungen:** Image-to-Video, 720p, Startbild ist das jeweilige Bild. Ton des Video-Tools in CapCut stumm schalten. Bei schnellen Kamerabewegungen 2 Varianten erzeugen.

**Erfahrungen mit Grok (aus dem Widder-Video):**

- Kamerabewegungen klappen gut, Stil und Figuren bleiben über 4 s stabil.
- Feuer/Energie wird übertrieben: Atem-Wörter → Feuerspeien, „pulses once“ → Explosion. Solche Wörter weglassen, Verbote wirken kaum.
- Bei großen Kamerafahrten verschwinden wichtige Dinge → „[OBJEKT] stays visible in the frame“ ergänzen.
- Das Hauptereignis liegt meist bei 0,5–2,5 s.

**Fester Schluss-Baustein:**

```
Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of [KÖRPERTEILE/GESICHTER].
```

**Clip [N] – [TITEL] ([DAUER] s)**

```
[WAS SICH BEWEGT/PASSIERT]. [KAMERABEWEGUNG]. [SCHLUSS-BAUSTEIN]
```

## CapCut-Schnittanleitung

Wichtigste Regel: **erst die Stimme, dann der Schnitt.** Jeder Schnitt sitzt auf einem Satzanfang.

1. **Projekt vorbereiten:** Format [FORMAT], Clips importieren, jeden Clip auf **Lautstärke 0**, CapCut-Abspann löschen, Claras Aufnahme an den Anfang.
2. **Schnitte setzen:** Tabelle Szene | Gesprochen | Clip von–bis | Tempo | Länge danach (wird nach der Generierung ausgefüllt).
3. **An die Stimme anlegen:** jeden Clip auf seinen Satzanfang; Tempo nicht unter 80 %; nur harte Schnitte.
4. **Effekte:** Zoom/Boom auf den Hook, Blitz + Wackeln auf Einschläge, Zoom-Punch (100 → 108 → 100 % in 0,2 s) auf Schlüsselwörter, ruhige Szene ohne Effekte mit leiser Musik, kurze Weißblende vor dem CTA.
5. **Untertitel:** automatisch, Deutsch, Wort für Wort, mittig, fett + kursiv, Großbuchstaben, weiß mit schwarzer Kontur. Schlüsselwörter in [AKZENTFARBE] ([HEX]); weiß lassen, wo die Bildmitte schon [AKZENTFARBE] leuchtet.
6. **Musik:** dunkles Ambient/Cinematic-Pulse, 10–15 %, in der ruhigen Szene auf ca. 5 %.
7. **Prüfen & Export:** einmal ohne Ton ansehen (versteht man es nur über Bild + Untertitel?), Länge prüfen, Export 1080p, 30 fps, als KI-generiert kennzeichnen.

**Beschreibung zum Posten:**

```
[1–2 SÄTZE MIT NEUGIER-LÜCKE] [FRAGE AN DIE ZUSCHAUER?] #[zeichen] #sternzeichen #astrologie #psychologie #sternzeichen[zeichen]
```

Erster eigener Kommentar: „Welches Sternzeichen soll als Nächstes kommen?“

## Check (Skill §10)

- [ ] Länge und Wortzahl passen zur Phase (F5)
- [ ] Hook ≤ 2,5 s, Thema im ersten Wort/Frame
- [ ] Wendepunkt vorhanden (Phase 1: ~13–16 s, Phase 2: 25–35 s), Kernwahrheit erst danach
- [ ] Mikro-Haken alle 8–12 s („Doch …“, „Aber …“)
- [ ] Ein Psychologie-Begriff, einfach erklärt
- [ ] Jede Szene illustriert den Satz wörtlich; Bildwechsel alle 1,5–3 s
- [ ] 1-Wort-Untertitel, Schlüsselwörter farbig
- [ ] Emotionaler Peak + CTA/offene Frage am Ende, kein Outro
- [ ] Nur Sternzeichen, Astrologie als Tendenz
- [ ] Generierung nur nach Freigabe mit Credit-Angabe (F4)
- [ ] Alle Feedback-Regeln eingehalten

---

## Änderungsprotokoll der Vorlage

| Datum | Änderung | Anlass |
|---|---|---|
| 21.11.2026 | Vorlage aus dem Widder-Video (`skripte/02-widder-ehrlich.md`) abgeleitet | Creatorin findet den Aufbau gut, will ihn mit weiteren Referenzbildern verbessern |
