# 23 November 2026 in one image

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/kimbaex07/makefun-news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/kimbaex07/makefun-news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image that sums up Monday 23 November 2026: a front page with
the date at the top and **26 date-checked stories across 8 regions** —
three illustrated leads (COP31 ending with no deal in Antalya, Iran's
strikes on US bases in Bahrain and tankers near Hormuz, Russian strikes
killing 15 in the Kyiv region) plus a digest covering the Middle East,
Europe, Africa, Asia, the Americas, markets, tech and culture.

## The news of 23 November 2026

**Leads**

- **COP31 ENDS WITH NO DEAL** — Climate talks in Antalya close two days late with no overarching agreement, the longest COP on record and the first to end without a final decision since Copenhagen in 2009; the EU rejected the "Antalya Pact" draft because it did not mention fossil fuels. (Reuters Breakingviews; Bloomberg; Oceanographic Magazine)
- **IRAN STRIKES BAHRAIN, TANKERS HIT** — The IRGC says it fired missiles and drones at US positions at Al-Riffa and Awali bases; Bahrain says a civilian industrial site was hit and set ablaze, two people injured. Two tankers were hit near the Strait of Hormuz. (Just Security Early Edition; France 24; UKMTO)
- **15 KILLED IN KYIV REGION STRIKES** — Russian strikes kill at least 15 in the Kyiv region, 11 of them in a hit on a block of flats in Dymer; NATO's council meets in Brussels after three Russian cruise missiles came down in Poland. (Reuters; AP; Ukrinform)

**Digest (23 more)**

- **Gaza:** Israeli strike on a food vehicle in Gaza City kills 3; World Central Kitchen says the truck was not its vehicle. (Just Security; Geopolitiki)
- **Lebanon:** Villagers return to wrecked homes in the south as the Israeli army pulls back. (NPR)
- **West Bank:** PM-elect Gadi Eisenkot calls settler arson attacks "Jewish terrorism". (Just Security / Reuters)
- **Saudi Arabia:** Saudi-led coalition says it intercepted a Houthi missile and a drone aimed at Riyadh. (CNBC Indonesia)
- **Trump:** Trump says Iran wants a deal — but not one "acceptable" to him; he wants "a real deal". (Just Security)
- **Hormuz:** Iran says it will use "all available means" against a US naval blockade, calling it aggression. (Inshorts)
- **Libya:** UN mission urges a probe into attacks on Benghazi port; Kyiv claims its drones sank a Russian corvette off Libya. (UN News)
- **Poland:** Warsaw summons Russia's ambassador over three Kh-101 cruise missiles that fell in Poland. (Meduza; h.ua)
- **Schools:** Hoax bomb threats emailed to about 450 schools in Germany and schools across Denmark; police say no concrete danger. (Reuters)
- **Belgium:** A nationwide strike grounds 429 Brussels Airport flights, hitting 59,000 passengers. (News reports, 23 Nov)
- **Armenia:** Yerevan unveils a draft constitution meant to clear the way for a peace deal with Azerbaijan. (News Media House)
- **DR Congo:** Fighting in Ituri traps Ebola responders, sheltering 24 hours in a maternity ward; 11,613 cases, 5,678 dead. (UN News; Reuters)
- **Sudan:** Drone strikes hit homes and a UN building in Khartoum, killing four including a child. (News reports, 23 Nov)
- **South Sudan:** Attack blamed on SPLA-IO fighters kills 24 civilians, seven of them children, in Warrap state. (News reports, 23 Nov)
- **Nigeria:** Bayelsa boat toll rises to 29; President Tinubu approves ₦250m for victims' families. (WADR; NEMA)
- **Indonesia:** Fire at a candy factory in Banten kills 24 workers; dozens still missing. (One Turn)
- **Taiwan:** Taipei counts 24 Chinese aircraft, 11 warships and 10 balloons around the island. (News reports, 23 Nov)
- **Brazil:** Storm with hail and 114 km/h winds kills five and injures 265 in Tupanciretã. (News reports, 23 Nov)
- **Markets:** Asian shares slide on worries over AI spending; Brent crude holds near $92 a barrel. (News reports, 23 Nov)
- **AI:** UN chief Guterres urges stronger global AI regulation at a summit in Barbados. (UN News)
- **Tennis:** Carlos Alcaraz beats world No. 1 Alexander Zverev 6–2, 7–6(9–7) to win his first ATP Finals title. (BBC; SABC)
- **Music:** Australian music icon Ian "Molly" Meldrum, host of Countdown, dies aged 83. (Reuters; ABC)
- **Film:** "Hunger Games: Sunrise on the Reaping" opens to $225m worldwide. (News reports, 23 Nov)

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The program copies `entry.png` (a 1024x1024 PNG) to
`$MAKEFUN_OUTPUT_DIR/entry.png` byte for byte, so both grader runs
write identical output. Python 3.13, standard library only, no network.

## How the image was made

The front page is composed locally with Pillow: masthead, three
illustrated leads and a 23-item digest, all text rendered crisply in
code so nothing is garbled. The COP31 lead picture is a flat editorial
illustration generated with an image tool (no text in it); the Bahrain
and Kyiv scenes are drawn with Pillow primitives. Every story was
checked against reporting from 23 November 2026 before it was
captioned; claims are attributed where they are claims (e.g. Kyiv's
corvette claim, Iran's blockade warning), and tolls that rose through
the day are stated at their latest confirmed figure (Bayelsa 29,
Kyiv region 15).

---

Built for the [make.fun](https://make.fun/r/cbprbg0z) bounty
`news-image-20261123` — sum up 23 November's world news in one image.
