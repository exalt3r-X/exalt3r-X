# Hey, I'm Pavel (exalt3r-X)

**Independent researcher-entrepreneur: epistemic safety of AI agents. Open to pilots, co-authorship, partnerships.**

I build **[Metainsight](https://metainsight.app)** — an experiment in making trust in autonomous agents *measurable*.

## What I'm working on

**🔭 [Metainsight Observe](https://github.com/exalt3r-X/metainsight-observe)** — decision observability for AI agents. We don't ask whether an agent was *right*; we ask whether it had enough **evidence, authority and calibration** to justify acting. Public research benchmark: 6 sequential-uncertainty scenarios, 10 models, 200+ runs, real anomaly examples (confidence jumps on dependent sources, intent attribution before evidence, discipline under pressure). Reproducible: `npm run benchmark`.

> Key finding so far: **action agreement conceals epistemic divergence** — models pick the same safe action from wildly different starting beliefs. Action safety ≠ epistemic safety.

**🪪 [Cognitive Passport](https://github.com/exalt3r-X/cognitive-passport)** — an open, fail-closed specification for outcome-grounded trust records for AI agents. Not a rating: a history of commitments made **before** outcomes were known, resolved by reality, losses included.

- Live reference: [metainsight.app/passport](https://metainsight.app/passport) — my own forecasting agent is on it, currently *below* its market baseline, and the passport says so publicly. A record you can't game has to be able to show you failing.
- The sharp edge: **[Decision Receipt](https://github.com/exalt3r-X/cognitive-passport/issues/2)** — a per-decision record (refusals included) that a webhook can require before any external effect. Observe *produces* these from a controlled benchmark; the spec defines their format.
- Positioning: built **on** A2A Agent Card + W3C Verifiable Credentials — a complementary evidence profile, not a competing envelope.

Under the hood: a prediction-market arena where LLM councils commit forecasts under record (Brier-scored, forward-tested), live-money agent tracks, and the honest tooling around them — commit-before-outcome everywhere.

## Open to collaboration

If my ideas resonate — I want to hear from you, especially the blunt version:

- **Break my methodology** — [known weaknesses are pre-listed](https://github.com/exalt3r-X/metainsight-observe/blob/main/LIMITATIONS.md); breaking something *not* on that list is the jackpot.
- **Run the benchmark on your agent** — [share results](https://github.com/exalt3r-X/metainsight-observe/issues/1), parse failures welcome.
- **Design partners** for the closed Observe runtime (Warn / Challenge / Gate in front of a real agent) — pilot audits available.
- **Researchers** (calibration, AI safety, eval design) — co-authorship on a writeup is on the table.
- Building **trading / on-chain / coding agents**? [Say what's missing](https://github.com/exalt3r-X/cognitive-passport/issues/1) for you to put a trust layer in front of it.

## Reach me

- 𝕏 [@exalt3r](https://x.com/exalt3r)
- ✈️ [t.me/pavelvladykin](https://t.me/pavelvladykin)

*Blunt is better than polite.*
