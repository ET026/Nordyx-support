# Nordyx — App Store Screenshot Plan (8 languages)

> **Hand-off brief for the agent generating App Store screenshots.**
> App: **Nordyx: AI Workout Planner** · `id6755626982` · iPhone-only · Health & Fitness.
> Goal: localized, keyword-aware screenshots for all 8 supported languages that
> rank in search (Apple indexes screenshot captions since June 2025) **and** convert.

---

## 0. Non-negotiables (read first)

1. **First 3 screenshots do 90% of the work.** ~90% of users never scroll past the
   3rd screenshot, and only the first 3 show in search results. Frames 1–3 must each
   carry the strongest value prop + a keyword-rich caption.
2. **Captions are indexed.** Put real search keywords in caption text (see keyword
   list §5). Do NOT repeat words already in the title/subtitle wastefully, but the
   high-value gym/strength/tracker/log terms SHOULD appear in captions.
3. **One narrative, 7 frames, same order in every language.** Only the caption text
   changes per locale — layout, device frame, and screen content stay identical.
4. **Caption length:** headline ≤ ~32 chars, subline ≤ ~42 chars. Keep it readable
   on a phone thumbnail. German/Portuguese run long — tighten, don't shrink the font.

---

## 1. Required image specs (iPhone-only app)

Apple requires the **6.9" display** size. 6.5" is optional but recommended for older devices.
No iPad set needed (app is "Designed for iPhone").

| Display | Resolution (portrait) | Required? |
|---|---|---|
| 6.9" (iPhone 16 Pro Max) | **1320 × 2868** px (1290 × 2796 also accepted) | ✅ Required |
| 6.5" (iPhone 11 Pro Max / XS Max) | 1242 × 2688 px | Optional (Apple upscales 6.9" if omitted) |

- Format: PNG or JPG, RGB, no alpha/transparency, flattened.
- Up to **10 per locale**; we ship **7**.
- 72 dpi is fine (App Store ignores dpi, only pixel dimensions matter).
- Export at exact pixel size — no rounding.

---

## 2. The 7-frame narrative (same for all locales)

| # | Screen to capture | Theme | In search? |
|---|---|---|---|
| 1 | AI plan generation result (weekly plan view) | **The hook: AI builds your plan** | ✅ visible |
| 2 | Adaptive/deload or fatigue indicator screen | **Adapts to recovery (the differentiator)** | ✅ visible |
| 3 | Session logger (set/rep/weight entry) | **Fast workout log/tracker** | ✅ visible |
| 4 | AI coach chat screen | AI coach |  |
| 5 | Apple Health / recovery (sleep, HRV) screen | Privacy + on-device recovery |  |
| 6 | Progress charts (1RM / volume trends) | See strength climb |  |
| 7 | Paywall / free-tier screen | Closer: start free, 7-day trial |  |

**Design rules per frame:**
- Caption sits in the top ~22% of the frame (above the device mockup), large bold
  headline + lighter subline.
- Use the brand palette: ink background `#0a0a0c`, signal accent `#fe6601`,
  paper text `#f4f1ea`. Fonts: **Anton** (headlines), **Hanken Grotesk** (sublines)
  — same as the website, for cross-channel consistency.
- Device: clean iPhone 16 Pro mockup, screen content must be the **localized** UI
  (i.e. capture the app running in that language, not English with translated captions only).

---

## 3. Localized captions — copy/paste table

Format per frame: **Headline** / *subline*. Use these verbatim.

### Frame 1 — AI builds your plan
| Locale | Headline | Subline |
|---|---|---|
| EN | Your plan, built by AI | Personalized in seconds |
| NL | Jouw plan, gemaakt door AI | In seconden persoonlijk |
| DE | Dein Plan, von KI erstellt | In Sekunden personalisiert |
| FR | Ton plan, créé par l'IA | Personnalisé en quelques secondes |
| ES | Tu plan, creado por IA | Personalizado en segundos |
| IT | Il tuo piano, creato dall'IA | Personalizzato in pochi secondi |
| PT-BR | Seu plano, feito por IA | Personalizado em segundos |
| TR | Planın, yapay zekâ ile | Saniyeler içinde sana özel |

### Frame 2 — Adapts to recovery (differentiator)
| Locale | Headline | Subline |
|---|---|---|
| EN | Adapts to your recovery | Detects fatigue, schedules deloads |
| NL | Past zich aan je herstel aan | Herkent vermoeidheid, plant deloads |
| DE | Passt sich deiner Erholung an | Erkennt Ermüdung, plant Deloads |
| FR | S'adapte à ta récupération | Détecte la fatigue, planifie les deloads |
| ES | Se adapta a tu recuperación | Detecta la fatiga y programa descargas |
| IT | Si adatta al tuo recupero | Rileva la fatica e pianifica gli scarichi |
| PT-BR | Adapta-se à sua recuperação | Detecta fadiga e agenda deloads |
| TR | Toparlanmana göre uyarlanır | Yorgunluğu algılar, deload planlar |

### Frame 3 — Fast workout log
| Locale | Headline | Subline |
|---|---|---|
| EN | Log every set, fast | Sets, reps, weight — no clutter |
| NL | Log elke set, snel | Sets, reps, gewicht — overzichtelijk |
| DE | Jeden Satz schnell loggen | Sätze, Wdh., Gewicht — übersichtlich |
| FR | Note chaque série, vite | Séries, reps, charge — sans fioritures |
| ES | Registra cada serie, rápido | Series, reps, peso — sin lío |
| IT | Registra ogni serie, veloce | Serie, reps, peso — senza confusione |
| PT-BR | Registre cada série, rápido | Séries, reps, carga — sem bagunça |
| TR | Her seti hızlıca kaydet | Set, tekrar, ağırlık — sade |

### Frame 4 — AI coach
| Locale | Headline | Subline |
|---|---|---|
| EN | An AI coach in your pocket | Answers grounded in your data |
| NL | Een AI-coach op zak | Antwoorden op basis van jouw data |
| DE | Ein KI-Coach für unterwegs | Antworten basierend auf deinen Daten |
| FR | Un coach IA dans ta poche | Des réponses basées sur tes données |
| ES | Un entrenador IA en tu bolsillo | Respuestas basadas en tus datos |
| IT | Un coach IA in tasca | Risposte basate sui tuoi dati |
| PT-BR | Um coach de IA no bolso | Respostas baseadas nos seus dados |
| TR | Cebinde yapay zekâ koçu | Verilerine dayalı yanıtlar |

### Frame 5 — Recovery data on device (privacy)
| Locale | Headline | Subline |
|---|---|---|
| EN | Recovery data stays on device | Sleep & HRV shape your plan |
| NL | Hersteldata blijft op je toestel | Slaap & HRV vormen je plan |
| DE | Erholungsdaten bleiben am Gerät | Schlaf & HRV formen deinen Plan |
| FR | Tes données restent sur l'appareil | Sommeil & VFC adaptent ton plan |
| ES | Tus datos no salen del dispositivo | El sueño y la VFC moldean tu plan |
| IT | I dati restano sul dispositivo | Sonno e HRV plasmano il piano |
| PT-BR | Seus dados ficam no aparelho | Sono e VFC moldam seu plano |
| TR | Verilerin cihazında kalır | Uyku ve HRV planını şekillendirir |

### Frame 6 — Progress / strength climb
| Locale | Headline | Subline |
|---|---|---|
| EN | Watch your strength climb | 1RM & volume trends |
| NL | Zie je kracht groeien | 1RM- en volumetrends |
| DE | Sieh deine Kraft wachsen | 1RM- & Volumen-Trends |
| FR | Vois ta force progresser | Tendances 1RM & volume |
| ES | Mira crecer tu fuerza | Tendencias de 1RM y volumen |
| IT | Guarda crescere la tua forza | Andamento di 1RM e volume |
| PT-BR | Veja sua força crescer | Tendências de 1RM e volume |
| TR | Gücünün arttığını gör | 1RM ve hacim grafikleri |

### Frame 7 — Start free (closer)
| Locale | Headline | Subline |
|---|---|---|
| EN | Start free — no account needed | 7-day trial on all plans |
| NL | Begin gratis — geen account nodig | 7 dagen proberen op alle abonnementen |
| DE | Kostenlos starten — ohne Konto | 7 Tage testen, alle Tarife |
| FR | Commence gratuitement — sans compte | 7 jours d'essai sur tous les forfaits |
| ES | Empieza gratis — sin cuenta | 7 días de prueba en todos los planes |
| IT | Inizia gratis — senza account | 7 giorni di prova su tutti i piani |
| PT-BR | Comece grátis — sem conta | 7 dias de teste em todos os planos |
| TR | Ücretsiz başla — hesap gerekmez | Tüm planlarda 7 gün deneme |

---

## 4. App Store Connect locale codes & file naming

Upload each language to its matching App Store Connect localization:

| Lang | ASC locale code | Folder/prefix suggestion |
|---|---|---|
| English | `en-US` | `en/` |
| Dutch | `nl-NL` | `nl/` |
| German | `de-DE` | `de/` |
| French | `fr-FR` | `fr/` |
| Spanish | `es-ES` | `es/` |
| Italian | `it-IT` | `it/` |
| Portuguese (Brazil) | `pt-BR` | `pt-BR/` |
| Turkish | `tr` | `tr/` |

**Suggested file naming** (sorts correctly, frame order preserved):
```
<locale>/6.9/01_plan.png
<locale>/6.9/02_recovery.png
<locale>/6.9/03_log.png
... 04_coach, 05_health, 06_progress, 07_free
```
Apple displays screenshots in filename sort order — always zero-pad (`01`, not `1`).

---

## 5. Keyword cheat-sheet (bake into captions where natural)

From the competitor gap analysis — terms the top apps rank for that Nordyx must reinforce:

`gym` · `tracker` · `log` · `strength` · `training` · `trainer` · `personal` · `fitness` · `home` · `routine` · `hypertrophy`

Differentiator long-tail (low competition, Nordyx-unique): `deload` · `recovery` · `HRV` · `fatigue` · `adaptive`.
Frames 2, 3 and 5 already lean on these — keep them.

---

## 6. Production workflow (suggested for the other agent)

1. **Set the app to each language** and capture clean screens for the 7 frames
   (real localized UI, status bar at 100% battery / full signal / no clock clutter
   — or use a faked clean status bar).
2. **Build one template** (background, caption zones, device mockup) parameterized by
   `{headline, subline, screenshot}`. Render 7 × 8 = **56 images** programmatically
   so layout stays pixel-identical across locales.
3. Pull caption strings from §3 (consider a small JSON/CSV so it's data-driven).
4. Export at **1320 × 2868** (6.9"). Optionally also 1242 × 2688 (6.5").
5. Run the QA checklist (§7) before upload.

---

## 7. QA checklist before upload

- [ ] Exactly 7 screenshots per locale, identical order in all 8.
- [ ] Each image is exactly 1320 × 2868 (and/or 1242 × 2688), RGB, no alpha.
- [ ] Caption text is in the **correct language** for that locale (no English left in NL/DE/etc.).
- [ ] Screen content (the UI inside the mockup) is in that locale's language too.
- [ ] Headlines don't clip; German/PT sublines fit on one or two lines, not cut off.
- [ ] No personal data / debug text / placeholder copy visible in any screen.
- [ ] Frames 1–3 each have a keyword-rich caption (gym/strength/tracker/log/AI/recovery).
- [ ] Special characters render correctly (Turkish ı/ş/ğ, accents in FR/ES/IT/PT).
- [ ] File names zero-padded so App Store order = intended order.

---

## 8. Notes / open decisions for Erenay

- **Brazilian Portuguese vs European Portuguese:** the app lists pt-BR. Captions above
  are written for **pt-BR** (e.g. "aparelho", "grátis"). If you ever add pt-PT, adjust.
- **English store:** if you also enable `en-GB`, the same EN captions work (no spelling
  conflicts in the chosen words).
- **Don't translate "deload" / "HRV" / "1RM":** these are accepted as-is by lifters in
  every locale — translating them hurts both clarity and keyword value.
- Tone is informal/"je/du/tu" throughout to match the app's voice and the website copy.
