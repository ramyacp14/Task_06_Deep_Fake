
# AI Video Interview – Syracuse Women’s Lacrosse 2025

## 🎯 Project Overview

This project demonstrates how to convert verified sports analytics into a broadcast-style AI video interview. Using **HeyGen**, we produced a stadium stand-up segment where an AI reporter presents key insights from Syracuse Women’s Lacrosse’s 2025 season. The video is grounded in verified statistics and avoids any invented data.

---

## 📊 Data & Background

* **Dataset:** Player statistics from 32 athletes, covering:

  * Goals (G), Assists (A), Shots (SH), Shooting % (SH%), Shots-on-Goal % (SOG%), Ground Balls (GB), Caused Turnovers (CT), Draw Controls (DC), Fouls, Games Played/Started (GP–GS)
* **Source:** 2025 Syracuse University Lacrosse Statistics
* **Key Stats Highlighted in Script:**

  * Team total: 347 points (235 goals, 112 assists) across 19 games
  * Leading scorers: Emma Muchnick – 34 goals, Angela Beardsley – 46 assists
  * Defensive standouts: Coco Vandiver – 40 caused turnovers
  * Efficiency leaders: Olivia Adamson – 55.6% shooting
  * Clutch performers: Caroline Trinkaus – 4 game-winning goals
  * Two-way impact: Joely Caramelli – 20 points, 23 ground balls, 11 CT

---

## 🛠 Tools Used

* **HeyGen:** Script → AI avatar video with stadium background, subtitles, and light music.
* **NotebookLM:** Cross-checked phrasing and ensured data accuracy from source statistics.
* *(Optional for future)* Colossyan or Lumen5 for multi-presenter or b-roll data visualization.

---

## 🎬 Workflow

1. **Script Development:**

   * Write concise, stadium-style stand-up script (1–2 sentences per key point) using verified statistics.
2. **Verify Data:**

   * Cross-reference Task 05 notebook outputs and source CSV to ensure accuracy.
3. **HeyGen Video Production:**

   * Paste script → select presenter, 16:9 stadium background → subtitles on → light background music.
   * Review pacing, numeric overlays, and lip-sync alignment.
4. **Export & Share:**

   * Export MP4 → add public share link → archive script + data + video for reproducibility.

---

## 📄 Video:

[Watch the AI Interview](https://app.heygen.com/videos/bfd67633f59644bf80eedcceff917f37)

---

## 📄 Script (AI Reporter, \~60s)

> *Live from Syracuse, we’ve broken down the Orange women’s lacrosse season through the numbers.*
>
> Across 19 games, the team scored 347 total points — that’s 235 goals and 112 assists.
>
> Up front, Emma Muchnick set the pace with 34 goals, while Angela Beardsley was the playmaker, leading with 46 assists.
>
> On the defensive end, Coco Vandiver stood out with 40 caused turnovers, shutting down opponents at key moments.
>
> Efficiency tells its own story. Olivia Adamson posted the best shooting percentage at 55.6% on more than 20 shots. And when games were on the line, Caroline Trinkaus delivered — scoring 4 game-winners.
>
> One of the most complete players? Joely Caramelli, balancing 20 points on offense with 23 ground balls and 11 caused turnovers.
>
> Strategically, Syracuse shines with versatile midfielders but still shows a defensive gap — opponents scored 337 points compared to the Orange’s 347.
>
> The takeaway? Finishers, creators, and two-way players drove Syracuse’s success, but shoring up defense could define their next season.

---

## ✅ Outputs

* **Final Video (HeyGen):**

  * 16:9 stadium stand-up with subtitles and light music
  * **Public Link:** *(Insert your HeyGen share link here)*
* **Script & Data Artifacts:**

  * Task 05 Notebook: `playerperformance.ipynb`
  * CSV: `data/Player_Stats.csv`
  * Prompt history & notes: `LLMResponses.docx`

---

## 🔁 Reproducibility Steps

1. Confirm stats from source dataset or Task 05 notebook.
2. Copy the finalized script into **HeyGen**.
3. Choose avatar + stadium background + subtitles → generate video.
4. Review timing, overlays, and lip-sync → export MP4.
5. Archive script, dataset, and video link for documentation.

---

## 💡 Reflections & Next Steps

* **Successes:** Concise script reads naturally, numeric overlays enhance clarity, NotebookLM prevented wording drift.
* **Improvements:** Consider two-presenter interviews, add b-roll charts (scatter plots for efficiency correlations), export SRT captions for accessibility, and experiment with prompt variations for different broadcast tones.

