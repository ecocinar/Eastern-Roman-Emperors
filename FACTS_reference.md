# Hard Numbers Reference — Byzantine State Capacity by Era

Companion reference for scoring `Difficulty` and `Effectiveness` in `ERE_List_20260226.csv`. This is a living document — add to it as new figures get sourced. Goal: ground subjective 1-20 scores in actual state-capacity data (population, army size, treasury) rather than gut feel alone, especially for "Difficulty at ascension."

**Important caveat:** Pre-700 AD figures are scholarly *estimates*, not census data. Cite them as "estimated by Treadgold / McEvedy-Jones," never as hard fact. Even later figures (army sizes especially) are contested — Treadgold's numbers in particular have been criticized by other historians (e.g. Haldon) as running high. Use these as directional anchors, not precise inputs.

---

## Population & Territory

Source: Wikipedia infobox (Byzantine Empire), citing Treadgold *A Concise History of Byzantium* (2001) and McEvedy & Jones *Atlas of World Population History* (1978).

| Year | Population (est.) | Territory (km²) | Context |
|---|---|---|---|
| 457 | ~16,000,000 | 2,350,000 | Leo I's accession |
| 565 | ~20,000,000 | 3,400,000 | Justinian I's peak (post-reconquest) |
| 775 | ~7,000,000 | 880,000 | Post-Arab-conquest nadir |
| 1025 | ~12,000,000 | 1,675,000 | Basil II's death |
| 1320 | ~2,000,000 | (fraction of above) | Late Palaiologan collapse |

**Key takeaway:** the empire lost roughly **65% of its population** between Justinian's 565 peak and the 775 trough (Arab conquests of Egypt, Syria, North Africa). Any emperor ascending in the 7th–8th century window (Constans II, Constantine IV, Justinian II, Leo III) inherited a genuinely decimated, existentially threatened state — strong quantitative support for high Difficulty scores in this era.

---

## Army Size

Source: Warren Treadgold, *Byzantium and Its Army, 284–1081* (Stanford, 1995) — the standard reference, though its high-end figures are disputed by some historians (Haldon et al.).

| Year | Army size (est.) | Emperor / Context |
|---|---|---|
| 305 | ~581,000 | Late Roman peak (per John the Lydian, pre-Byzantine) |
| 559 | ~150,000 | Justinian I — peak reconquest-era army |
| 773 | ~80,000 | Constantine V — post-collapse trough |
| 840 | ~120,000 | Theophilos — Amorian-era recovery |
| 1081 | ~20,000 (field army) | Alexios I's accession — post-Manzikert collapse |
| 1143 | ~50,000 (total) | Manuel I — Komnenian recovery peak |
| 1176 | ~30,000–35,000 (campaign force, incl. allies) | Manuel I — exceptional mobilization vs. Seljuks |
| 1279 | ~20,000 | Early Palaiologan recovery post-1261 |

**Key takeaway:** the drop from ~150,000 (559) to ~20,000 field army (1081) is one of the starkest data points in the whole dataset — a ~7x contraction following Manzikert (1071) and the subsequent civil wars. Strong quantitative backing for Alexios I's high Difficulty score.

---

## Treasury / Fiscal

Scattered figures — genuinely hard to find consistent series across 1,100 years. Log what's found; flag gaps for future research.

| Emperor | Year | Figure | Source note |
|---|---|---|---|
| Anastasios I | 518 (death) | 320,000 lb gold surplus | Best-documented treasury figure in the period; funded by tax/coinage reform (abolished the chrysargyron tax) |
| Basil II | 1025 | ~5.9 million nomismata annual budget | Per Treadgold/Morrisson estimates, cited in Milanovic's income-inequality study |
| Marcian | 450–457 | "Substantial surplus" (no firm figure found yet) | Achieved via tribute-refusal to Attila + tax reform; worth a dedicated search |

---

## Usurpations / Coups (quantitative anchor)

Source: Wikipedia "List of Byzantine usurpers" / cross-referenced with Grokipedia summary.

**At least 23 successful usurpations recorded between 306 and 1453** — i.e., roughly 1 successful violent seizure of the throne every ~50 years on average across the empire's lifespan, though heavily clustered in certain eras (7th–9th century instability, 11th century pre-Komnenian chaos, and the late Palaiologan civil wars).

**Named successful usurpers (partial list, chronological):**
Basiliscus (475–476) · Phocas (602–610) · Heraclius (610–641) · Leontius (695–698) · Tiberius III (698–705) · Philippicus (711–713) · Anastasius II (713–715) · Theodosius III (715–717) · Leo III (717–741) · Nikephoros I (802–811) · Leo V (813–820) · Michael II (820–829) · Basil I (867–886) · John I Tzimiskes (969–976) · Isaac I Komnenos (1057–1059) · Nikephoros III Botaneiates (1078–1081) · Alexios I Komnenos (1081–1118) · Andronikos I Komnenos (1183–1185) · Isaac II Angelos (1185, restored 1203)

**Usage note:** this list is useful for a binary "did this emperor's *ascension* itself require a violent coup" flag — could be cross-referenced against your CSV's `List_Number` to add a `Rose_Via_Usurpation` column, which would be a genuinely objective, sourced data point (as opposed to the subjective Difficulty/Effectiveness scores) supporting Difficulty scoring for these reigns specifically.

---

## Opposing Force Sizes — Existential Threats

### Siege of Constantinople, 626 (Heraclius)
Combined Sassanid-Avar-Slavic siege force vs. Byzantine capital, while Heraclius himself was campaigning in Persian territory.
- **Contemporary Byzantine sources (Theodore Synkellos):** Byzantine defenders "less than 8,000 troops, outnumbered 10+ to 1"
- **Contemporary Persian-aligned source (George of Pisidia):** attacking force ~80,000
- **Modern historical estimate:** Byzantine defenders closer to ~15,000 (12,000 cavalry + 1,000-2,000 palace guard + sailors) — still heavily outnumbered
- **Outcome:** siege failed, saved the empire from likely collapse — one of the most consequential defensive victories in Byzantine history

### Heraclius's field campaigns, 624–625 (Caucasus)
- **Battle of Ganzak:** Heraclius ~24,000 vs. Khosrow II ~40,000 — Byzantine victory, Khosrow fled the field
- **Caucasus campaign overall:** Heraclius ~24,000 vs. Sassanid ~70,000 — Byzantines still prevailed

**Key takeaway:** Heraclius repeatedly fought and won at 2-3x troop disadvantages, on top of defending the capital itself at 10:1 odds in the same war. Exceptionally strong quantitative support for his existing D=20 (max score) — this may be the single best-documented "genuinely extreme difficulty" case in the entire dataset.

### Siege of Constantinople, 1453 (Constantine XI)
- **Modern historian consensus range:** Ottoman force **60,000–80,000** fighting men (Britannica, TheCollector, Byzantine-world.com all converge here)
- **Contemporary chronicles:** inflated claims of 100,000+; some outlier estimates run as high as 200,000-300,000, but these are not the modern scholarly consensus
- **Byzantine defenders:** consistently cited at **~7,000-8,000** (breakdown per one source: ~5,000 Greeks + <2,000 foreign mercenaries, mainly Genoese/Venetian)
- **Ratio: roughly 10:1**, defending 14 miles of walls
- **Naval force:** Ottoman fleet ~320 vessels vs. Constantine XI's 26 ships
- **Duration:** 53-55 day siege

**Key takeaway:** this is probably the single most quantitatively lopsided "impossible odds" data point in the whole 90-emperor dataset — a legitimate, well-sourced case for Constantine XI's Difficulty sitting at or near the maximum, regardless of how the reign's brief length otherwise gets weighed.

---

## Still to gather (next session candidates)

- **Arab Caliphate force sizes** during the two great Arab sieges of Constantinople (674–678 under Constantine IV, 717–718 under Leo III) — not yet gathered, high priority given how central these are to two separate high-Difficulty reigns already in the dataset
- **Constantinople's own population** by era — found one figure so far (~400,000-500,000 at 6th-century Justinianic peak per *History of Istanbul*; ~40,000-50,000 by the 1450s per Britannica) — worth expanding into a fuller series, and the 1450s collapse figure is itself a striking data point for Constantine XI's context
- **Marcian's specific treasury surplus figure** (currently just "substantial," no hard number found)
- **Full usurper list completion** — the list above is partial; worth pulling the complete Wikipedia list including unsuccessful attempts, for a fuller picture of instability by era

---

## Emperors reviewed so far (score discussion log)

Running log of specific score-revision discussions, so rationale doesn't get lost between sessions.

| Emperor | Current D / E | Assessment | Suggested direction |
|---|---|---|---|
| Isaac I Komnenos | 8 / 10 | Capable reformer, first military coup in ~100 years, undone by short reign + elite backlash, not incompetence | Both likely too low |
| Basil II | 8 / 20 | Inherited decade-plus civil war (Bardas Skleros + Bardas Phokas) pushing empire to "brink of collapse," plus multi-front external threats | Difficulty too low — should be high teens |
| John VI Kantakouzenos | 17 / 1 | Capable administrator, gifted historian; catastrophic strategic error (inviting Ottomans into civil war) — but E=1 equates this with pure incompetence | Effectiveness likely too harsh — consider 3-4 |
| Michael IV the Paphlagonian | 3 / 11 | Inherited fraught court situation, wars in Bulgaria/Serbia, ruled while suffering severe epilepsy | Difficulty too low |
| Michael VIII Palaiologos | 16 / 16 | Recovered Constantinople (genuine achievement) but Union of Lyons was costly/unpopular/ineffective; resources diverted west may have starved Anatolian defense against nascent Ottoman threat | Effectiveness arguably too generous — worth a modest cut |
| Marcian | 12 / 12 | Refused Attila tribute (bold, paid off), amassed real fiscal surplus, convened Council of Chalcedon | Effectiveness slightly low — consider 14-15 |
| Leo I the Thracian | 8 / 11 | Inherited puppet-emperor position under kingmaker Aspar; broke his stranglehold (real achievement) but also oversaw catastrophic 1113-ship Vandal expedition disaster | Difficulty too low — consider 12-14 |
| Zeno | 15 / 16 | Constant rebellions/depositions survived; brilliantly redirected Theoderic/Ostrogoths to Italy at zero cost; Henotikon failed and caused Acacian Schism | Already reasonable — no change needed |
| Leo I the Thracian | 8→12 / 11→12 | Ascended as kingmaker Aspar's intended puppet — no bloodline claim, structurally precarious position; later broke Aspar's stranglehold (real achievement) but oversaw catastrophic Vandal expedition disaster | Difficulty raised (applied); Effectiveness roughly holds |
| Marcian | 12→9-10 / 12→14-15 | Ascension itself was smooth/negotiated (married Pulcheria, Aspar's backing, no rival) even though the external threat (Attila) was serious — "easy ascension, high external stakes" is a real distinction; refused Attila tribute, achieved major fiscal turnaround, convened Council of Chalcedon | Difficulty should drop (ascension was easy); Effectiveness raised (applied) |
| Theodosios I the Great | 16 / 16→15 | Ascended into post-Adrianople catastrophe (Valens killed, Eastern field army destroyed) — genuinely severe difficulty, holds up well; BUT never militarily defeated the Goths (382 settlement let them stay as armed autonomous federates, a precedent-setting failure), and his anti-pagan edicts enabled destruction of major cultural sites (e.g. the Serapeum) | Difficulty confirmed correct; Effectiveness lowered for military failure + cultural destruction (applied) |
| Theodosios II | 9 / 14 | Ascended peacefully as a child (low difficulty, uncontested) — but own Summary states he was "largely dominated by his sister Pulcheria and senior officials," while E=14 credits him personally for Walls/Council of Ephesos/Law Code achieved mostly by others | Effectiveness likely too high given the dataset's own text — consider 9-10 |
| Constantine VIII | 1 / 11 | Own Summary explicitly calls his sole reign "short and ineffective" — E=11 sits at the scale's midpoint, contradicting "ineffective" outright | Clear text/score contradiction — Effectiveness should drop to ~5-6 |
| Basil II (update) | 8→11 (partial) / 20 | Raised from 8 to 11 already, but the decade-plus civil wars (Bardas Skleros, Bardas Phokas) pushing the empire to "the brink of collapse" still likely warrant higher | Difficulty likely still too low — consider 15-17 |
| Michael III the Drunkard | 11 / 9 | Real achievements (Bulgarian conversion, educational revival) largely driven by regent Bardas, not Michael personally — same "credited for others' governance" pattern as Theodosios II and Constantine VII | Flagged as part of a systemic pattern (see note below), not a standalone fix |
| Constantine VII Porphyrogennetos | 9 / 12 | Scholarly patron-emperor; state actually run by Romanos I for most of the reign | Same systemic pattern — see note below |
| Nikephoros I | 8 / 14 | Violent coup against Eirene (D likely too low, same pattern as Basil I/Romanos I/John I Tzimiskes); reign ended in catastrophic defeat and death at the Battle of Pliska | Both figures worth revisiting — D up, E down |
| Anastasios II | 9 / 8 | Defensive/military preparations widely credited with directly enabling Leo III's successful defense of the 717-718 Arab siege a few years later — a real, consequential legacy often undersold by same-reign-only assessment | Effectiveness possibly underrated — consider 10-11 |
| Michael IV the Paphlagonian (walkback) | 3 / 11 | Earlier flagged as "Difficulty too low" — but on consistent application of the "at ascension" rule, his actual transition (favored by Zoe, no rival, no coup) genuinely was smooth | Walking back earlier flag — D=3 likely already defensible |

**Systemic pattern flagged, needs a standing decision:** at least three reigns (Theodosios II, Michael III, Constantine VII) score Effectiveness fairly high despite the Summary text explicitly stating a regent/official actually ran the state. Worth deciding as a matter of project policy: should Effectiveness reward *state outcomes* regardless of who drove them, or specifically the *emperor's own personal agency*? Current scoring appears to apply this inconsistently across similar cases.

