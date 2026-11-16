### Hi, I'm Demetrius 👋

I like turning messy, real-world questions into systems that answer them every day, and then checking whether the answers were actually right.

My main project is **Apex**, a sports prop-pricing system that runs around the clock on my Mac. It collects lines and stats, prices each prop with a probability model, checks it against sportsbook prices, posts ranked boards to Discord, and grades every pick against the real result.

**[▶ See how Apex works](https://demetriusreynolds251-maker.github.io/apex/)**: an interactive one-page tour.

```
 data feeds ─▶ warehouse ─▶ model ─▶ book check
                                         │
   grading ◀── discord ◀── boards ◀── rules & rank
      │
      └── real results feed back into "honest" probabilities
```

| Repo | What it is |
|---|---|
| [apex-tennis](https://github.com/demetriusreynolds251-maker/apex-tennis) | The live system: scheduler, model, boards, grading, Discord bot, dashboard |
| [apex-multisport](https://github.com/demetriusreynolds251-maker/apex-multisport) | The same approach for NFL, NHL, soccer, college sports and more |
| [apex-tennis-research](https://github.com/demetriusreynolds251-maker/apex-tennis-research) | Backtests and audits behind every rule |
| [apex-tennis-warehouse](https://github.com/demetriusreynolds251-maker/apex-tennis-warehouse) | Daily collector for the tennis stats database |

**What I care about when I build:** test it against history before trusting it, grade everything, make every change reversible, and alert only when something actually changes.

**Tools:** Python · SQLite · pandas · scikit-learn · XGBoost · Discord bots · REST APIs · macOS launchd · Git

<sub>Apex was designed and directed by me and built with AI coding assistants. I understand the code and architecture but am not a professional software engineer.</sub>
