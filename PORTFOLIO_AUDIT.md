# GitHub portfolio audit — 16 October 2026

## Verdict

The public portfolio supports a Senior Game Producer / Product Owner story: practical domain workflows, scoped game prototypes and explicit validation limits. Its strongest evidence is something a visitor can try or inspect immediately. It does not yet establish external adoption, measured player outcomes or commercial performance.

This review covers the profile README and all nine public project READMEs, repository metadata, recent GitHub Actions history, selected repository trees and the two new games' release evidence. Private repositories were excluded from the public assessment. This is a portfolio and onboarding audit, not a full code, security or legal audit.

## Changes applied

- Rewrote the profile to lead with role, playable demos and inspectable project evidence.
- Added Air Fighter and Pocket Reels to the profile with direct play/source/case-study links.
- Distinguished game product direction and AI-assisted implementation from commercial validation.
- Replaced pre-deployment wording in both game READMEs with their deployed Pages links.
- Added a short PORTFOLIO.md to each game: problem, role, scope, evidence, limits and next validation.
- Replaced generic server/install instructions in the prompt-only repository with relevant use and contribution guidance.
- Removed unsupported percentage-of-work and model-comparison claims from that prompt library.

Existing career metrics were not independently verified in this audit. The shorter profile uses responsibilities and career history rather than repeating numerical impact claims that the repositories cannot substantiate. That is not a finding that those claims are false.

## Project-by-project assessment

| Public project | Portfolio value | Main friction or gap | Next useful action |
| --- | --- | --- | --- |
| [Retro Air Fighter](https://github.com/canmils/retro-air-fighter) | Immediate playable evidence of a scoped game release | Early prototype; simulation tests do not validate control feel or real-device compatibility | Observe first-time keyboard and phone players; log difficulty, completion and voluntary retry |
| [Pocket Reels](https://github.com/canmils/pocket-reels) | Strong fit with iGaming; clear rules and exhaustively enumerated model | Model correctness is separate from browser correctness and player comprehension | Ask players to explain a bet, line payout and balance change; log errors |
| [SteamLens](https://github.com/canmils/steamlens) | A clear user problem with free output and optional AI | Main README provides local setup/cloud deployment instructions, but no deployed public demo URL | Publish or supply the verified free-only demo URL; add one annotated output example |
| [Slot PM Agents](https://github.com/canmils/slot-pm-agents) | Strong domain judgement, data contracts and inspectable reports | Agent naming can suggest more automation than the two runnable examples provide | Lead demonstrations with one concrete report and document a review decision it supports |
| [Slot-REA](https://github.com/canmils/Slot-REA) | Source preservation and explicit unknowns are useful product decisions | Several workflows and legacy environments make first use harder | Give first-time users one evidence-pack → questions → draft walkthrough before legacy tools |
| [AdLens](https://github.com/canmils/adlens) | Clear evidence collection/export workflow | Browser install and best-effort capture add friction; no homepage URL in repo metadata | Lead with the fictional screenshot workflow; share a verified interface URL with backend limits |
| [Weekly Report Agent](https://github.com/canmils/weekly-report-agent) | Relevant production workflow and explicit draft review | AI generation requires a key; improvement over manual reporting is unmeasured | Compare correction effort on fictional notes before claiming time savings |
| [Catalan Music Radar](https://github.com/canmils/catala-music-radar) | A specific personal user problem with CSV output | Less relevant to gaming hiring; ambiguous artist matches and partial coverage are documented | Keep as a supporting project; improve identity matching if real usage warrants it |
| [AI Prompts for Game Production](https://github.com/canmils/ai-prompts-for-game-production) | Useful supporting practice material | Prompts alone provide weaker evidence than runnable products | Add a small fictional before/after example with explicit review criteria |

## Verification evidence

Both game deployment workflows succeeded for the initial MVP commits:

- [Air Fighter deployment](https://github.com/canmils/retro-air-fighter/actions/runs/38885575277)
- [Pocket Reels deployment](https://github.com/canmils/pocket-reels/actions/runs/38887166840)

Successful main-branch runs were observed for SteamLens, AdLens, Slot-REA, Slot PM Agents, Weekly Report Agent and Catalan Music Radar. Some newest runs belong to feature branches; their status was not substituted for main-branch evidence.

No workflow run was returned for the prompt-only repository. That is not inherently a defect for a documentation library.

All nine public projects have a detected MIT or Apache-2.0 licence. At review time each had zero GitHub stars and forks. Those counts do not measure total users, and no traffic or retention analytics were obtained.

The public-page fetch tool could not retrieve the profile or Pages sites in this environment. Deployment success, repository files and the owner's Air Fighter play report support release claims; this review did not perform fresh browser or phone QA.

## Account-level settings still to apply

The available connector can edit repository files but does not expose profile bio, pin ordering, repository About/homepage or topic updates. These settings were inspected where available but were not changed.

### Suggested pins, in order

1. Retro Air Fighter — immediate playable game.
2. Pocket Reels — playable iGaming prototype with transparent maths.
3. SteamLens — broader gaming/product tool.
4. Slot PM Agents — domain-specific decision workflows.
5. Slot-REA — sourced evidence and documentation.
6. AdLens — research tooling beyond game production.

The profile README already gives visitors this selection even before pins are changed.

### Suggested profile bio

Senior Game Producer & Product Owner | Gaming, iGaming and product delivery | Playable prototypes and practical tools | Barcelona, Spain

### Suggested repository About fields

| Repository | Description | Website |
| --- | --- | --- |
| retro-air-fighter | Playable retro shooter MVP with keyboard/touch controls, a complete mission and automated simulation tests. | https://canmils.github.io/retro-air-fighter/ |
| pocket-reels | Playable fictional-credit slot prototype with five paylines, transparent rules and an exhaustively evaluated mathematical model. | https://canmils.github.io/pocket-reels/ |

Suggested topics: Air Fighter — gamedev, arcade-game, javascript, canvas, browser-game. Pocket Reels — gamedev, slot-machine, javascript, game-math, browser-game.

Other existing project descriptions are already specific enough to retain. Do not invent a hosted homepage for a local-only tool.

## Hiring interpretation

Use these repositories as supporting evidence for scope decisions, release discipline, source handling and collaboration with technical implementation. AI-assisted code is not evidence of independent software-engineering expertise.

The next portfolio improvement should be a documented playtest or user-observed iteration. Record the initial problem, the change and what happened afterwards. Do not claim F2P expertise, increased retention, saved hours or revenue from the existence of a prototype alone.
