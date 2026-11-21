# Widder-Video – Skript & Prompts

> **Quelle:** Claude-Doc „Widder-Video – Skript & Prompts (Clara, 16:9, ~33 s)“ (https://claude.ai/artifact/KppMngCA8CdD5odKLvrXHZ), Stand 21.11.2026, Revision 43. Ins Projekt übernommen als **Muster-Beispiel** für `vorlagen/video-vorlage.md`.
> Hinweis: Dieses Video ist mit 31–34 s noch vor Regel F5 entstanden (Phase 1 heute: 25–30 s).

2026-11-17 · @Isabell

## Überblick

Ein Widder-Video, ca. 33 Sekunden, 16:9, gesprochen von Clara. Kernaussage: Widder sind nicht aggressiv, sie sind ehrlich, und ihr Streit ist ein Liebesbeweis.

| Eckdaten | Wert |
|---|---|
| Format | 16:9, 1080p |
| Länge | ca. 31–34 s (Ziel: unter 35 s) |
| Wörter | 87 |
| Szenen | 13 Bilder → 13 Clips, Schnitt alle ca. 2–3 s |
| Stimme | Clara Modern Narration – Calm & Clear (ElevenLabs, Eleven v3) |
| Bildstil | Röntgen-Hologramme: der Widder als Tier mit orangem Feuerkern, das Gegenüber als menschliche Röntgen-Frau; orange Energie als einzige Akzentfarbe |

**Woran wir erkennen, dass das Video gut ist:** Der Hook ist nach 1,5 s gesagt. Jeder Satz hat ein eigenes Bild. Es gibt eine überraschende Pointe und einen Schlusssatz zum Speichern. Am Ende steht ein CTA, der Kommentare auslöst.

**Workflow**

1. Stimme in ElevenLabs erzeugen (Abschnitt „ElevenLabs“). So steht das echte Timing fest.
2. 13 Bilder in Nano Banana erzeugen. Dabei jedes Mal dein Widder-Hook-Bild als Referenz hochladen.
3. Jedes Bild in Grok Imagine 1.5 Lite als Startbild hochladen und mit dem passenden Bewegungs-Prompt animieren (3–6 s pro Clip). Das Video übernimmt automatisch das 16:9-Format des Bildes.
4. In CapCut Audio und Clips zusammenschneiden, Wort-für-Wort-Untertitel und Musik dazu.

## Skript

Das Skript hat 87 Wörter und folgt der Formel aus den Vorlagen: Hook mit Widerspruch, Wiedererkennung, psychologisches Warum, überraschende Pointe, „Was dir niemand sagt“, Schlusssatz zum Speichern, CTA.

**Zum Lesen am Stück:**

> Widder sind nicht aggressiv. Sie sind nur die Einzigen, die es dir ins Gesicht sagen. Während andere innerlich kochen, sagt ein Widder sofort, was ihn stört. Denn Schweigen fühlt sich für ihn an wie Lügen. Seine Wut ist ein Gewitter. Und zehn Minuten später fragt er dich, ob du Hunger hast. Aber was dir niemand sagt: Ein Widder streitet nur mit Menschen, die ihm wichtig sind. Hört er auf, mit dir zu streiten, hat er aufgehört, um dich zu kämpfen. Widder? Schreib dein Geburtsdatum in die Kommentare.

**Szenen und Timing** (geschätzt bei Tempo 1,1; nach der Sprachaufnahme an die echte Tonspur anpassen):

| # | Zeit | Gesprochen | Bild | Wort in Orange |
|---|---|---|---|---|
| 1 | 0,0–1,5 s | Widder sind nicht aggressiv. | Widder, Feuerkern flammt auf, Funken und Feuerbälle aus den Nüstern | AGGRESSIV |
| 2 | 1,5–3,4 s | Sie sind nur die Einzigen, | Widder und Röntgen-Frau stehen sich gegenüber | – |
| 3 | 3,4–5,6 s | die es dir ins Gesicht sagen. | Profil: orange Schallringe treffen das Gesicht des Gegenübers | GESICHT |
| 4 | 5,6–7,1 s | Während andere innerlich kochen, | Ruhige Frau, im Röntgen-Brustkorb brodelt Orange | KOCHEN |
| 5 | 7,1–9,7 s | sagt ein Widder sofort, was ihn stört. | Widder stampft mit dem Huf, orange Druckwelle | SOFORT |
| 6 | 9,7–13,0 s | Denn Schweigen fühlt sich für ihn an wie Lügen. | Röntgen-Kopf und Hals, oranger Knoten zieht sich zu | LÜGEN |
| 7 | 13,0–14,9 s | Seine Wut ist ein Gewitter. | Orange Blitze aus einer Wolke über dem Widder | GEWITTER |
| 8 | 14,9–19,3 s | Und zehn Minuten später fragt er dich, ob du Hunger hast. | Gewitter vorbei, Widder schiebt ihr eine dampfende Schüssel hin | HUNGER |
| 9 | 19,3–21,8 s | Aber was dir niemand sagt … | Kamera fährt langsam in das leuchtende Gehirn | NIEMAND |
| 10 | 21,8–25,5 s | Ein Widder streitet nur mit Menschen, die ihm wichtig sind. | Streit mit Funken, aber ein oranger Faden verbindet beide Herzen | WICHTIG |
| 11 | 25,5–28,5 s | Hört er auf, mit dir zu streiten … | Widder dreht sich weg, Feuerkern erlischt | – |
| 12 | 28,5–31,4 s | hat er aufgehört, um dich zu kämpfen. | Faden reißt, Widder geht ins Dunkle | KÄMPFEN |
| 13 | 31,4–34,0 s | Widder? Schreib dein Geburtsdatum in die Kommentare. | Großes oranges Widder-Symbol, viele kleine Figuren | GEBURTSDATUM |

Wird die Aufnahme länger als 35 s: zuerst Tempo auf 1,15 stellen. Findest du den Speed-Regler bei v3 nicht, beschleunige die Tonspur in CapCut auf 1,1x. Reicht das nicht, den Satz „Denn Schweigen fühlt sich für ihn an wie Lügen.“ und Szene 6 streichen.

## ElevenLabs

Nimm Clara mit dem Modell Eleven v3. Nur v3 versteht die Regieanweisungen in eckigen Klammern; sie werden nicht mitgesprochen.

**Text zum Einfügen:**

```
[serious] Widder sind nicht aggressiv. Sie sind nur die Einzigen, die es dir ins Gesicht sagen.
Während andere innerlich kochen, sagt ein Widder SOFORT, was ihn stört. Denn Schweigen fühlt sich für ihn an wie Lügen.
Seine Wut ist ein Gewitter. [amused] Und zehn Minuten später fragt er dich, ob du Hunger hast.
[softly] Aber was dir niemand sagt …
[whispers] Ein Widder streitet nur mit Menschen, die ihm wichtig sind.
[serious] Hört er auf, mit dir zu streiten … hat er aufgehört, um dich zu kämpfen.
Widder? Schreib dein Geburtsdatum in die Kommentare.
```

**Einstellungen:**

| Einstellung | Wert | Warum |
|---|---|---|
| Stimme | Clara Modern Narration – Calm & Clear | feste Account-Stimme |
| Modell | Eleven v3 | Regieanweisungen funktionieren nur hier |
| Stability | Natural (klingt es flach: Creative) | Creative ist ausdrucksstärker, aber unberechenbarer; Robust ignoriert die Anweisungen weitgehend |
| Speed | 1,1 | gegen den Meditations-Effekt, näher am Tempo der Vorlagen |
| Takes | 3–4 erzeugen | die Anweisungen wirken nicht jedes Mal gleich |

**So prüfst du die Aufnahme:**

- Länge 31–35 s.
- Bei „Aber was dir niemand sagt“ wird sie hörbar leiser.
- „ob du Hunger hast“ klingt leicht amüsiert, nicht ernst.
- Wenn ein Satz in keinem Take passt: nur diesen Satz neu erzeugen und in CapCut austauschen. Wird der Satz mit [whispers] zu leise, ersetze die Anweisung durch [softly].

Falls du doch Multilingual v2 nimmst: alle eckigen Klammern löschen (v2 liest sie sonst vor). Dann Stability 35 %, Similarity 75 %, Style 25 %, Speed 1,1.

Die Angaben zu v3 stammen aus der [ElevenLabs-Anleitung zu Eleven v3](https://cdntest.elevenlabs.io/docs/best-practices/prompting) und den [ElevenLabs Best Practices](https://elevenlabs.io/docs/product/speech-synthesis/prompting).

## Nano-Banana-Prompts

Hauptfigur ist dein Widder aus dem Hook-Bild: ein kräftiger Widderbock als Röntgen-Hologramm mit orangem Feuerkern. Das Gegenüber ist eine menschliche Röntgen-Frau mit Pferdeschwanz, ohne Feuerkern. So bleibt Orange immer das Zeichen des Widders.

**So gehst du vor:**

- Lade bei jedem Bild dein **Widder-Hook-Bild** als Referenz hoch. Es legt Stil und Widder fest.
- Ab Bild 3 zusätzlich **Bild 2** hochladen, wenn die Frau vorkommt. Dann sieht sie in allen Szenen gleich aus.
- Seitenverhältnis im Tool auf **16:9** stellen.
- Prompts sind auf Englisch, weil Bildmodelle damit zuverlässiger arbeiten.

**Bild 1 – Hook:** erledigt, dein Widder-Bild.

**Bild 2 – Gegenüber**

```
Use the attached ram image as the reference for the ram and for the style. New scene: wide side view on the glowing grid floor. On the left the ram from the reference (powerful bighorn-style ram, two thick spiral horns, translucent blue x-ray body with visible skeleton and glowing blue brain, burning orange fire core in its chest), on the right a female human x-ray hologram figure with a ponytail (translucent blue body, visible skeleton, glowing blue brain, no fire core). They face each other a few meters apart, calm but tense, as if a conversation is about to start. Keep the space between them in the middle of the frame empty. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray hologram bodies, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark.
```

**Bild 3 – Ins Gesicht sagen**

```
Use the attached ram image as the reference for the ram and the style, and the attached woman image for the woman. New scene: close side-profile shot of two heads facing each other: on the left the ram's x-ray head with its two spiral horns, mouth closed; on the right the woman's x-ray head with her ponytail. Concentric glowing orange sound-wave rings travel from the ram's head toward the woman's face and touch it. Keep the center between the heads fairly clear. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, translucent glowing electric-blue x-ray hologram bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark.
```

**Bild 4 – Innerlich kochen**

```
Use the attached ram image as the style reference and the attached woman image for the woman. New scene: centered medium shot of the woman (female human x-ray hologram figure with a ponytail, no fire core) standing calmly with relaxed arms, looking composed from the outside, while inside her translucent chest and throat an orange-red liquid glow is boiling and bubbling, pressure visibly building up. No ram in this image. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray body with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red. No text, no letters, no logos, no watermark.
```

**Bild 5 – Sofort sagen**

```
Use the attached ram image as the reference for the ram and the style. New scene: dynamic wide shot, slight low angle. The ram stamps one front hoof forward onto the grid with its head raised confidently, and a bright orange circular shockwave ring bursts outward from the hoof across the grid floor. Its orange fire core glows strongly. Mouth closed. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray body with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark.
```

**Bild 6 – Schweigen wie Lügen**

```
Use the attached ram image as the reference for the ram and the style. New scene: extreme close-up of the ram's x-ray head and throat in profile: glowing blue brain inside the skull, a spiral horn in the background, and inside its throat a tight knot of tangled glowing orange wires, as if unspoken words are stuck there. Mouth closed. Dark, intimate, shallow depth of field. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, deep navy-black background with soft blue haze and tiny particles, translucent glowing electric-blue x-ray anatomy with visible skull, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red. No text, no letters, no logos, no watermark.
```

**Bild 7 – Gewitter**

```
Use the attached ram image as the reference for the ram and the style. New scene: wide dramatic shot. The ram stands firmly in the center of the grid while a dark storm cloud forms above its horns and jagged orange lightning bolts strike down around it, lighting the blue haze orange. Mouth closed. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray body with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark.
```

**Bild 8 – Hunger?**

```
Use the attached ram image as the reference for the ram and the style, and the attached woman image for the woman. New scene: calm aftermath, the storm is gone and a few fading orange sparks drift in the air. On the left the ram, now relaxed with a soft gentle glow in its chest, nudges a glowing wireframe bowl with soft rising steam across the grid floor toward the woman on the right, who tilts her head in surprise. Warm, slightly humorous mood. Wide shot. Mouth closed. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red. No text, no letters, no logos, no watermark.
```

**Bild 9 – Was dir niemand sagt**

```
Use the attached ram image as the reference for the ram and the style. New scene: front view close-up of the ram's x-ray head, its two spiral horns framing the image, the glowing blue brain in the center, tiny orange sparks flickering deep inside it, surrounded by darkness. Mouth closed. Mysterious, intimate, quiet. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, deep navy-black background with soft blue haze and tiny particles, translucent glowing electric-blue x-ray anatomy with visible skull, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red. No text, no letters, no logos, no watermark.
```

**Bild 10 – Streit mit Verbindung**

```
Use the attached ram image as the reference for the ram and the style, and the attached woman image for the woman. New scene: wide shot. The ram on the left and the woman on the right face each other in a heated argument, the ram's head lowered, orange sparks flying between them, but a thin glowing orange thread runs from the ram's fire core to the woman's heart, unbroken and strong. Mouth closed. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark.
```

**Bild 11 – Er hört auf**

```
Use the attached ram image as the reference for the ram and the style, and the attached woman image for the woman. New scene: wide shot, darker and quieter lighting. The ram on the left has turned away from the woman on the right and looks into the distance in silence. The fire core in its chest has dimmed to a faint cold blue, and the orange thread between them is faint and flickering. Melancholic mood. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is a faint orange-red. No text, no letters, no logos, no watermark.
```

**Bild 12 – Nicht mehr kämpfen**

```
Use the attached ram image as the reference for the ram and the style, and the attached woman image for the woman. New scene: wide cinematic shot. The ram walks away into the dark distance along the glowing grid floor, its chest core cold and dim, while the orange thread that connected it to the woman snaps and dissolves into falling orange particles. The woman stands alone in the foreground, looking after it. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red. No text, no letters, no logos, no watermark.
```

**Bild 13 – CTA**

```
Use the attached ram image as the reference for the ram and the style. New scene: wide epic shot. The ram stands proudly in the center of the grid, its orange fire core blazing, and above it floats a large glowing orange hologram sculpture of two curved ram horns (the Aries sign as a 3D shape). Many small blue human x-ray figures gather around and look up at it. Inviting, powerful mood. Mouth closed. Style: exactly the look of the reference image: cinematic 3D render, 16:9 widescreen, starry deep navy-black background with soft blue nebula haze, glowing blue perspective grid floor, translucent glowing electric-blue x-ray bodies with visible skeleton and glowing blue brain, high contrast neon glow, sci-fi medical-scan aesthetic. The only accent color is orange-red fire. No text, no letters, no logos, no watermark; the ram-horn shape is the only symbol.
```

## Grok-Imagine-Prompts

Jeder Clip hat ein eigenes **Ereignis** und eine eigene **Kamerabewegung**. Keine zwei Clips hintereinander bewegen sich gleich. So arbeiten auch die @tiefenseele-Vorlagen: In jeder Einstellung passiert etwas (Einschlag, Explosion, Verwandlung), und die Bildgröße springt bei fast jedem Schnitt. Nur Clip 11 ist bewusst ruhig, das macht den Kontrast.

| Clip | Kamera | Ereignis |
|---|---|---|
| 1 | schneller Push-in | Funkenexplosion, Feuerbälle aus den Nüstern |
| 2 | Bogen hinter die Schulter der Frau | Widder schnaubt, Kern flammt auf |
| 3 | Crash-Zoom auf ihr Gesicht | Schallringe treffen, Pferdeschwanz weht zurück |
| 4 | Schwenk von der Brust hoch zum Gesicht | Brodeln steigt, Bläschen platzen als Funken |
| 5 | bodennah, erschüttert, dann Kran hoch | Huf schlägt, Feuerring explodiert, Glut fliegt zur Kamera |
| 6 | seitliche Fahrt am Hals entlang zum Gehirn | Knoten zieht sich im Herzschlag zu |
| 7 | statisch, wackelt bei jedem Einschlag | Blitze schlagen neben ihm ein |
| 8 | sanfte Handkamera vom Widder zur Frau | Wolken zerfallen, er hebt den Kopf |
| 9 | Flug zwischen den Hörnern ins Gehirn | Nervenbahnen rauschen vorbei, Funke zündet |
| 10 | seitliche Begleitfahrt mit Wackeln | Funken im Takt, Faden vibriert und hält |
| 11 | sehr langsamer Rückzug (ruhigster Moment) | Kern erlischt, Faden hängt durch |
| 12 | Kran nach oben in die Vogelperspektive | Faden reißt, Widder geht |
| 13 | von oben herab, dann auf den Widder zu | Zeichen zündet, Lichtwelle über die Menge |

**Einstellungen:** Image-to-Video, 720p, Startbild ist immer das jeweilige Bild, Länge wie angegeben. Das Video übernimmt das 16:9-Format des Bildes ([xAI-Doku](https://docs.x.ai/developers/model-capabilities/video/overview)); möglich sind 1–15 s ([Runware](https://runware.ai/docs/models/xai-grok-imagine-video-1-5-lite/guides/generating-video)). Den Ton von Grok in CapCut stumm schalten. Bei schnellen Kamerabewegungen lohnt es sich, 2 Varianten zu erzeugen und die bessere zu nehmen.

**Was Clip 1–5 über Grok gezeigt haben:**

- Kamerabewegungen setzt Grok gut um, Stil und Figuren bleiben über 4 s stabil.
- Feuer und Energie werden übertrieben: Atem-Wörter erzeugen Feuerspeien, „pulses once“ wird zur Explosion. Solche Wörter weglassen, Verbote wirken kaum.
- Bei großen Kamerafahrten verschwinden wichtige Dinge aus dem Bild. Darum steht bei den Clips jetzt „stays visible in the frame“.
- Das Hauptereignis liegt meist bei 0,5–2,5 s. Den besten Abschnitt im Schnitt auswählen.

**Clip 1 – Hook (4 s):** erledigt. Im Schnitt nur die ersten ca. 1,5 s verwenden.

**Clip 2 – Gegenüber (4 s)**

```
The ram snorts a short puff of glowing orange breath and its fire core flares once, the woman flinches slightly. The camera arcs quickly to the right around the woman into an over-the-shoulder view, looking past her at the ram. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns, legs or faces.
```

**Clip 3 – Ins Gesicht sagen (4 s)**

```
The orange sound-wave rings pulse faster and hit the woman's face in a rhythmic beat, her ponytail whips back as if hit by a gust of wind. Fast crash zoom toward her face, then hold. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns or faces.
```

**Clip 4 – Innerlich kochen (3 s)**

```
The boiling orange glow in her chest surges upward, glowing bubbles rise through her throat and burst into tiny sparks at her neck, while her face stays perfectly calm. The camera tilts up slowly from her boiling chest to her calm face. Keep the exact holographic x-ray style, colors and lighting of the image. No animals, no text, no morphing of the face or body.
```

**Clip 5 – Sofort sagen (4 s)**

```
The ram slams its hoof down, the fiery ring explodes outward as a shockwave across the grid, glowing embers fly toward the camera, its fire core pulses once. Low ground-level camera that shakes on the impact, then cranes up as the embers settle. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns or legs.
```

**Clip 6 – Schweigen wie Lügen (5 s)**

```
The orange knot in the ram's throat pulls tighter in a heartbeat rhythm, its wires glow brighter with every pulse and a few sparks escape. The camera glides slowly upward from the knot to the brain, keeping the orange knot visible in the frame. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no text, no morphing of the skull or horns.
```

**Clip 7 – Gewitter (4 s)**

```
A lightning bolt strikes the grid right next to the ram with a bright orange flash, sparks and debris fly, a second bolt follows on the other side, the ram stands firm. Static camera that shakes hard with every strike. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns or legs.
```

**Clip 8 – Hunger? (6 s)**

```
The last storm sparks dissolve into drifting particles, soft white steam curls up from the bowl, the ram slowly raises its head and looks at the woman, she looks from the bowl to the ram in surprise. The bowl stays on the floor. Gentle handheld camera drifting slowly from the ram toward the woman. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns, legs or faces.
```

**Clip 9 – Was dir niemand sagt (4 s)**

```
The camera flies forward between the horns straight into the glowing brain, blue neural pathways rush past the lens, and deep inside a tiny orange spark ignites into a small flame. Accelerating fly-through, mysterious and hypnotic. Keep the exact holographic x-ray style, colors and lighting of the image. No text, no morphing of the horns.
```

**Clip 10 – Streit mit Verbindung (6 s)**

```
Sparks burst between the ram and the woman in sharp rhythmic bursts, the ram tosses its head, and the orange thread between its fire core and her heart vibrates like a plucked string but never breaks. Lateral tracking shot with a slight handheld shake, both figures and the thread stay visible in the frame. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns, legs or faces.
```

**Clip 11 – Er hört auf (5 s)**

```
Everything slows down: the ram's chest stays cold blue, the faint orange thread sags and flickers, the woman stays frozen. Very slow pull-back, the calmest and quietest shot of the video. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns, legs or faces.
```

**Clip 12 – Nicht mehr kämpfen (5 s)**

```
The last piece of the orange thread dissolves into embers that drift down, the ram keeps walking away into the darkness, the woman stays still. The camera cranes up into a high angle, making her look small and alone, the woman and the dissolving thread stay visible in the frame. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns, legs or faces.
```

**Clip 13 – CTA (5 s)**

```
The floating orange ram-horn symbol ignites with a bright burst and sends a wave of orange light across the crowd, the figures lift their heads, the ram's fire core blazes and sparks rain down. The symbol keeps its exact shape and does not rotate. Slow push-in toward the ram, the symbol stays visible at the top of the frame. Keep the exact holographic x-ray style, colors and lighting of the image. Mouth stays closed, no fire breathing, no new animals, no text, no morphing of horns or legs.
```

Verformt sich etwas: Clip neu erzeugen oder nur die ersten 2–3 Sekunden verwenden, die sind fast immer sauber.

## CapCut-Schnittanleitung

Dein Rohvideo (59,6 s) enthält alle 13 Clips in der richtigen Reihenfolge, aber ungeschnitten und mit dem Ton von Grok. Geschnitten wird es ca. 34 s lang. Wichtigste Regel: **erst die Stimme, dann der Schnitt.** Jeder Schnitt sitzt auf einem Satzanfang.

### Schritt 1 – Projekt vorbereiten

1. Neues Projekt, Format **16:9**. Die 13 Einzelclips importieren (oder dein Rohvideo).
2. Jeden Clip antippen → **Lautstärke 0**. Der Grok-Ton muss raus.
3. Den CapCut-Abspann am Ende (die letzten ca. 2 s mit Logo) löschen.
4. Claras Sprachaufnahme als Audio importieren und ganz an den Anfang legen.

### Schritt 2 – Schnitte setzen

So geht es: Abspielkopf auf „Rohvideo von“ → **Teilen**. Abspielkopf auf „Rohvideo bis“ → **Teilen**. Die Stücke außerhalb löschen. Dann **Geschwindigkeit → Normal** auf den Wert aus der Tabelle stellen. Arbeitest du mit den Einzelclips, gilt dieselbe Reihenfolge; die Zeiten beziehen sich dann auf den Anfang des jeweiligen Clips (Rohvideo-Zeit minus Clipstart).

| Szene | Gesprochen (hier beginnt der Clip) | Rohvideo von–bis | Tempo | Länge danach |
|---|---|---|---|---|
| 1 | Widder sind nicht aggressiv. | 0,00–1,50 s | 100 % | 1,5 s |
| 2 | Sie sind nur die Einzigen, | 4,07–5,67 s | 85 % | 1,9 s |
| 3 | die es dir ins Gesicht sagen. | 8,10–12,13 s | 180 % | 2,2 s |
| 4 | Während andere innerlich kochen, | 12,93–14,43 s | 100 % | 1,5 s |
| 5 | sagt ein Widder sofort, was ihn stört. | 15,70–18,30 s | 100 % | 2,6 s |
| 6 | Denn Schweigen fühlt sich für ihn an wie Lügen. | 19,73–23,03 s | 100 % | 3,3 s |
| 7 | Seine Wut ist ein Gewitter. | 24,47–27,27 s | 150 % | 1,9 s |
| 8 | Und zehn Minuten später fragt er dich, ob du Hunger hast. | 29,30–33,37 s | 90 % | 4,5 s |
| 9 | Aber was dir niemand sagt … | 34,37–37,37 s | 120 % | 2,5 s |
| 10 | Ein Widder streitet nur mit Menschen, die ihm wichtig sind. | 37,40–41,10 s | 100 % | 3,7 s |
| 11 | Hört er auf, mit dir zu streiten … | 43,93–46,93 s | 100 % | 3,0 s |
| 12 | hat er aufgehört, um dich zu kämpfen. | 51,07–53,47 s | 83 % | 2,9 s |
| 13 | Widder? Schreib dein Geburtsdatum in die Kommentare. | 53,53–56,53 s | 100 % | 3,0 s |

### Schritt 3 – An die Stimme anlegen

1. Timeline groß ziehen, bis du die Wellenform der Stimme gut siehst.
2. Jeden Clip so verschieben, dass er genau am Anfang seines Satzes aus der Tabelle beginnt. Satzanfänge erkennst du an den kleinen Lücken in der Wellenform.
3. Ist ein Satz länger als der Clip: Tempo des Clips etwas senken (nicht unter 80 %). Ist er kürzer: das Clipende abschneiden.
4. Zwischen den Clips **keine Übergänge** einfügen, nur harte Schnitte. Einzige Ausnahme steht in Schritt 4 (Szene 12 → 13).

### Schritt 4 – Effekte

Weniger ist mehr: Die Clips sind schon lebendig. Diese Effekte setzen die Akzente.

| Szene | Effekt | So geht es in CapCut |
|---|---|---|
| 1 | Zoom auf 130 %, nur der Widder im Bild | Clip antippen, Bild mit zwei Fingern aufziehen |
| 1 | tiefer Boom-Sound auf das erste Wort | Audio → Soundeffekte → „Boom“ oder „Impact“ |
| 5 | weißer Blitz + Wackeln genau beim Huf-Aufschlag (auf „sofort“) | Effekte → Video-Effekte → „Blitz“ bzw. „Flash“ auf 2–3 Frames kürzen; dazu „Wackeln“ bzw. „Shake“ für ca. 0,5 s |
| 6 | langsames Heranfahren an den Knoten | zwei Keyframes: Anfang 100 %, Ende 120 %, Mitte auf dem Knoten |
| 7 | Blitz + Wackeln bei beiden Einschlägen | wie Szene 5, zweimal |
| 3, 6, 8, 10 | kurzer Zoom-Punch auf GESICHT, LÜGEN, HUNGER, WICHTIG | drei Keyframes in 0,2 s: 100 % → 108 % → 100 % |
| 9 → 10 | harter Schnitt von Funken zu Funken | nichts einfügen, nur sauber schneiden |
| 11 | keine Effekte, Musik leiser | Musik-Spur: Keyframe-Lautstärke für diese 3 s auf ca. 5 % |
| 12 → 13 | kurze Weißblende, wenn das Licht zurückkommt | Übergang → „Blitz“ bzw. „Weißblende“, Dauer 0,2 s |

### Schritt 5 – Untertitel

1. Text → **Automatische Untertitel**, Sprache Deutsch.
2. Eine Vorlage wählen, die **Wort für Wort** einblendet, mittig im Bild.
3. Schrift fett und kursiv, Großbuchstaben, weiß mit schwarzer Kontur.
4. Orange einfärben (#FF6A1A): AGGRESSIV, SOFORT, LÜGEN, GEWITTER, HUNGER, NIEMAND, WICHTIG, KÄMPFEN.
5. **Weiß lassen**: GESICHT (Szene 3), KOCHEN (Szene 4), GEBURTSDATUM (Szene 13), weil dort die Bildmitte schon orange leuchtet. GEBURTSDATUM in Szene 13 etwas höher setzen, zwischen Symbol und Lichtwelle.
6. Alle Untertitel einmal auf Tippfehler prüfen, vor allem „Widder“ und „Geburtsdatum“.

### Schritt 6 – Musik

Dunkle, ruhige Ambient- oder Cinematic-Pulse-Musik aus der CapCut-Bibliothek, Lautstärke ca. 10–15 %. Die Stimme muss immer klar vorne liegen. In Szene 11 die Musik absenken (siehe Schritt 4), ab Szene 13 wieder hoch.

### Schritt 7 – Prüfen und exportieren

1. Einmal komplett ohne Ton anschauen: Versteht man die Geschichte nur über Bilder und Untertitel?
2. Länge prüfen: 31–35 s.
3. Export: **1080p, 30 fps**.

**Beschreibung zum Posten:**

```
Widder sind nicht so, wie du denkst. #widder #sternzeichen #astrologie #psychologie #sternzeichenwidder
```

Als ersten Kommentar kannst du selbst fragen: „Welches Sternzeichen soll als Nächstes kommen?“ Das bringt zusätzliche Kommentare und Ideen für die Serie.

## Quellen

- Analysierte Vorlagen: [@mindloop65 – Widder](https://www.tiktok.com/@mindloop65/video/7704056758716681486), [@mindloop65 – Fische](https://www.tiktok.com/@mindloop65/video/7703307181105351950), [@tiefenseele](https://www.tiktok.com/@tiefenseele/video/7663165611941301536), [@social._verena](https://www.instagram.com/reel/DfhSzZSNgvk/), [@tomboekenkroeger](https://www.instagram.com/reel/Dcyqe-psfNp/)
- [ElevenLabs – Prompting Eleven v3](https://cdntest.elevenlabs.io/docs/best-practices/prompting)
- [ElevenLabs – Best Practices](https://elevenlabs.io/docs/product/speech-synthesis/prompting)
- [xAI – Video-Modelle](https://docs.x.ai/developers/model-capabilities/video/overview)
- [Runware – Grok Imagine Video 1.5 Lite](https://runware.ai/docs/models/xai-grok-imagine-video-1-5-lite/guides/generating-video)
