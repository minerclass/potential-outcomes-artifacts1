# Planning for Potential Outcomes — Interactive Artifact Set

Companion artifact set for the thought experiment *Planning for Potential Outcomes: A Thought Experiment on Data Use, Dissemination, and Contingent Interpretation in the Pedagogical Friction Study* (Miner, 2026), part of the dissertation proposal **Pedagogical Friction in the Age of Generative AI and Tertiary Algorithmicity: A Qualitative-Dominant Convergent Mixed Methods Study** (National Louis University, Ed.D. in Curriculum, Advocacy, and Policy).

> **Proposal stage.** No participant data have been collected and the study reports no findings. Every tool here is prospective: it models what *would* happen with findings, and collects nothing.

## What this is

Four interactive, dependency-free web tools that turn the written thought experiment into demonstrations a committee member, educator, or policymaker can use directly:

| Tool | Page | Thought experiment prompt |
|---|---|---|
| **Friction Audit Protocol** | `friction-audit.html` | Interventions and programs — a guided audit of any AI-touched assignment that classifies remaining difficulty as productive or exclusionary |
| **Ecological Systems Explorer** | `ecological-explorer.html` | Bronfenbrenner analysis — clickable nested-systems model mapping findings to micro/meso/exo/macro/chronosystems |
| **Dissemination Pipeline Map** | `dissemination-map.html` | Data use and dissemination — interactive trace from raw data to participant, scholarly, professional, and local tracks |
| **Outcome Scenario Explorer** | `scenario-explorer.html` | Contingent interpretation — pre-committed interpretive moves for null, unsupported, or contradictory findings |

`index.html` is the hub.

## Design commitments

- **No data collection.** Pure static HTML/CSS/JS. No server, database, account system, analytics, or storage — consistent with the IRB posture of the dissertation's instrument suite (GitHub Pages presents instruments; it never receives data).
- **Framework-honest.** The Pedagogical Friction Framework is presented as an empirical question. The Scenario Explorer exists to demonstrate that disconfirming evidence is planned for, not feared.
- **Practitioner-first language.** Framework terms appear alongside plain professional language (the head, the room, the world, the system).
- **No dependencies.** No frameworks, no CDNs, no build step. Open `index.html` in a browser or serve via GitHub Pages.

## Deploying to GitHub Pages

1. Create a repository (suggested name: `potential-outcomes-artifacts`) under `minerclass`.
2. Push these files to the `main` branch.
3. Settings → Pages → Deploy from branch → `main` / root.
4. Link from the dissertation hub and writing-sites hub.

## File tier (per repo conventions)

**Public.** Contains no participant data, student/staff data, district identifiers beyond published affiliations, or credentials. Safe to commit and share.

## Relationship to the dissertation

These artifacts are demonstrations of *potential* outcomes — anticipated interventions and dissemination structures. They are not study instruments, do not collect responses, and would be revised after findings. The Friction Audit verdict logic encodes the framework's productive-versus-exclusionary distinction as currently theorized; if the empirical findings revise the framework, the tool revises with it.

---

Micah J. Miner, CETL, Ed.S. · Director of Innovation & Technology, Beach Park District 3 · Doctoral candidate, National Louis University

## License

Dual-licensed to separate software from scholarship, matching the rest of the ecosystem:

- **Source code** (HTML, CSS, JavaScript, configuration): [MIT License](LICENSE)
- **Written and scholarly content** (framework descriptions, prose, figures):
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), with attribution to Micah J. Miner

The Pedagogical Friction framework and its terminology are the author's scholarly work; please cite
the dissertation and related publications when building on them.
