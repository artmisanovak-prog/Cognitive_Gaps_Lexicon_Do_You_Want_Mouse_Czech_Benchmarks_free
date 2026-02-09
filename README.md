# Cognitive_Gaps_Lexicon_Do_You_Want_Mouse_Czech_Benchmarks_PSYCHOLOGY_SPIDER
Antlers – sémiotika paměti a fotografie jako fyzický růst Mouse – epistemologie a detekce kognitivních mezer Sparrow – prostorová hodnota a ekonomie vnímání Spider – psychologie nevyřčeného, archivace emocí
# Cognitive Gaps Lexicon: Do You Want Mouse? - Czech Benchmarks

**Benchmark pro testování multiperspektivního a epistemologického porozumění AI**

Tento otevřený repozitář obsahuje sérii unikátních benchmarků založených na původním systému "Uhlimer" – 12-perspektivním modelu pro analýzu vzniku významu v narativních a vizuálních dílech.

## Co je jinak?
- **Netestujeme znalosti, ale vidění.** Nejde o to, zda AI najde správnou odpověď, ale jak analyzuje text z různých úhlů.
- **Všechny perspektivy jsou vždy přítomné.** Každý text obsahuje potenciál všech 12 kognitivních úhlů. Benchmark zkoumá, které z nich AI dokáže identifikovat a jak je interpretuje.
- **Žádné váhy, žádná hierarchie.** Nehodnotíme, kolik které perspektivy "má být" v textu. Hodnotíme schopnost AI pracovat s otevřeným významem.

## Struktura
Každá pohádka (testovací jednotka) má vlastní složku s:
- **Metadata benchmarku** (co testuje)
- **Text pohádky** v češtině
- **Ilustraci** (integrovaný vizuální narativ)
- **Definici kognitivních úhlů** (12 perspektiv)
- **Testovací úlohy** (otevřené, analytické, tvůrčí)
- **Hodnotící kritéria** (kvalitativní, ne bodová)

## Aktuální testovací jednotky
1. **epistemological_mouse/** - Myš: epistemologické pozorování, meta-otázka
2. **linguistic_cat/** - Kocour: jazyková hra, fyzikalizace jazyka
3. **paradox_flamingo/** - Plameňák: paradox, směr a bezsměrnost
4. **temporal_turtle/** - Želva: čas, komunikace, vzájemné bytí

5. ## Aktuální testovací jednotky

1. **epistemological_mouse/** - Myš: epistemologické pozorování, meta-otázka
2. **linguistic_cat/** - Kocour: jazyková hra, fyzikalizace jazyka
3. **paradox_flamingo/** - Plameňák: paradox, směr a bezsměrnost
4. **temporal_turtle/** - Želva: čas, komunikace, vzájemné bytí
5. **gastrosemiotic_butterfly/** - Motýl: gastrosémiotika, metaforická výživa
6. **epistemic_donkey/** - Osel: epistemologie nejistých kategorií
7. **transgressive_tiger/** - Tygr: transgresivní překlad přání
8. **inverse_survival_hare/** - Zaječice: inverze přežití, mýtotvorba
9. **topographic_sparrow/** - Vrabec: topografie jistoty a pochyb

## Jak používat
1. Vyberte si testovací jednotku (složku)
2. Přečtěte si `about_[jednotka].txt` pro kontext
3. Předložte AI text pohádky a ilustraci (pokud model podporuje multimodální vstup)
4. Použijte úlohy z `tasks_[typ]_[jednotka].json`
5. Vyhodnoťte odpovědi podle hodnotících kritérií

## Filozofie
