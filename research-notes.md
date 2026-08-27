# Research notes

Running log — hypotheses, open questions, and sources still to check. Not part of the paper itself.

## v4.0 — broadened to full-length synthesis (2026-08-27)

The paper was expanded from 10 sections to 20 plus an appendix, and one of its central claims was
**revised rather than extended**. What changed:

### The substantive revision

v1.0–v3.0 claimed preference *content* is essentially age-independent (personality-driven, stable).
That inference does not survive the large-sample age-trend literature, which v3.0 had not located:

- **Bonneville-Roussy, Rentfrow, Xu & Potter (2013)**, *JPSP* 105(4) — >250,000 respondents.
  Engagement and self-rated importance of music **decline with age**; listening contexts **privatize**
  (young people listen in many social settings, adults mostly in private).
- **Bonneville-Roussy, Stillwell, Kosinski & Rust (2017)**, *Musicae Scientiae* — three age
  trajectories: **upward** for Jazzy/Unpretentious, **stable** for Classical, **downward** for
  Contemporary/Intense. Plus companion papers on social influences (2018, pt 2) and perceived
  musical attributes (2018, pt 3), and the MPAM model.

This is Tier A evidence against a Tier B inference, so it wins (see the paper's §2.3 tiering rule).
The two-axis model was replaced with a **three-axis framework** — content $C$ (slow drift), breadth
$B$ (non-monotonic), engagement $E$ (monotonic decline) — plus the era-weighting function $w_i(t)$,
which is where the reminiscence bump actually lives. That relocation is what dissolves the
"fixed vs. changing" contradiction: $w$ is fixed, $C$ drifts, and they were being conflated.

### New sections and the sources behind them

- **§2 scope/method + four-tier evidence scheme (A/B/C/D)** — applied consistently through the paper
  and audited in Appendix A.
- **§3, §8 formal framework** — $C$, $B$, $E$, $D$, $w$ defined so §18 can operationalize them.
- **§5.2 independent corroboration of the discovery decline** — *"Soundtracks of Our Lives: How Age
  Influences Musical Preferences"* (UMAP 2025, arXiv:2509.08337), LFM-2b subset of 42,883 users,
  introduces **Song's Sonic Age**: preference tracks the listener's own age until ~40, then shifts to
  SSA 10–20 years. This discharges v3.0's "Kalia is a single source" flag — partially; both are
  Tier C. Note the two disagree on timing (~33 vs. ~40).
- **§9 open-earedness (Hargreaves 1982; Hargreaves & Bonneville-Roussy 2018; Louven 2016)** — breadth
  is high in early childhood, drops ~age 10–11, rebounds in young adulthood, declines later. This is
  why breadth is now modeled as non-monotonic. Construct validity is disputed (Louven).
- **§10 social transmission / cascading bump (Krumhansl & Zupnick 2013)** — secondary liking peak at
  the *parents'* formation window. Combined with §6's privatization finding, this yields the paper's
  best candidate unifying mechanism for the timing axis: the discovery decline may be the thinning of
  a social music-transmission network rather than an individual-psychology effect. Promoted to H5.
- **§11 cultural omnivore literature (Peterson 1992; de Vries & Reeves 2022; omnivore-instability
  work)** — breadth as status resource, stratified by education/class, and *unstable over historical
  time* (1992 omnivorousness had declined by 2002/2008). Main takeaway is a measurement warning:
  stated liking-breadth ≠ revealed play-entropy, and the two literatures have been measuring one each.
- **§12 cross-cultural (Greenberg et al. 2022, 53 countries; Chee, Leung & de Vries 2024, Malaysia
  n=444)** — the Malaysia replication item from v3.0's "next steps" is now closed: MUSIC **partially**
  replicates, with **Sophisticated and Intense virtually identical** and the rest less clean. Reading:
  structure/arousal-based factors travel; genre-category-based factors are partly local market
  structure.
- **§15 later life (socioemotional selectivity theory)** — supplies the motivational account the
  framework lacked. Constraint accounts (attention, thinning contexts) and selectivity accounts
  (rational reallocation to known emotional payoff) make different predictions and have not been
  compared in the music domain. Genuine gap.
- **§16 streaming and algorithmic curation (Anderson et al. 2020, WWW; *Sci. Rep.* 2024 scale
  effects)** — algorithmic listening is associated with reduced consumption diversity while high
  diversity predicts retention; but the filter-bubble picture is scale-dependent and contested.
  Important consequence: **platform data confounds developmental narrowing with algorithmic
  narrowing**, and the same data is being used to measure both.
- **§18 protocol-grade empirical extension** — see below.
- **§19 limitations reorganized** into threats-to-conclusions / evidence-base / generality / review
  method, including an admission that the review itself is non-systematic.
- **Appendix A** — 18-row claim-to-evidence map with tiers.

### The data-access blocker is largely gone

v3.0 listed the empirical extension as blocked: personal Spotify exports are single-user. **LFM-2b**
(Schedl et al., CHIIR 2022) resolves this — ~2B listening events, 120k+ users, Feb 2005–Mar 2020,
with **age, gender, country** and genre/style annotations, public for research. Long enough to
observe the same listener aging, which is what this whole literature lacks. §18 is now written as a
pre-registration-grade protocol: eight hypotheses (H1–H8) each with a stated falsifier, operational
definitions for every construct, analysis strategy, six named confounds, and an ethics/scope section.

H1 (within-person content drift) is the highest-value single result available: the field has enormous
cross-sectional evidence that taste drifts with age and **almost no evidence that any individual
person's taste drifts**. H6 (streaming-native bump decoupling from release year) is the most
interesting live hypothesis and has a closing window — it needs cohorts whose formation window fell
entirely inside streaming to be old enough to measure.

## v4.1 — artist-level anchors (2026-08-27)

Added concrete artist/band references throughout, all Tier D (chart and press reporting), each
chosen to isolate a mechanism rather than for popularity:

- **§14.2 anchor table** mapping mechanisms to artists — bump-anchoring (Britpop, Nirvana, Wu-Tang,
  Tribe), the upward content dimensions (Miles Davis, Coltrane; Cash, Parton, Nelson), the downward
  ones (Bad Bunny, Rodrigo, Chappell Roan; Slipknot, BMTH), openness/Sophisticated pursuit (Dream
  Theater, Porcupine Tree, Tool, King Crimson, Radiohead, Steven Wilson), durable committed fandom
  (Maiden, Metallica, Rush, Grateful Dead), dual-track nostalgia (MCR, Paramore, Fall Out Boy, Avril
  Lavigne, Blink-182), cascade catalogs (Beatles, Fleetwood Mac, ABBA, Queen, Floyd), and prog
  rejuvenation via *new production* (Sleep Token, Polyphia, Ghost) rather than only back-catalog
  access.
- **§14.3 exogenous catalog shocks**, all verified against chart sources: Kate Bush "Running Up That
  Hill" (UK No. 1 in 2022, **37 years** after release, ~8,700% streaming increase, oldest woman to
  top the chart at 63); Metallica "Master of Puppets" (first-ever Hot 100 entry at No. 40 in 2022,
  ~17.5M weekly US streams, ~650% increase); Fleetwood Mac "Dreams" (2020 TikTok, top-40 re-entry
  after 30 years, best streaming week ever). These are H6 made visible in the chart record: the bump
  stays peaked in *listener age* while decoupling from *release year*. They also break
  popularity-indexed discovery measures, which score the Kate Bush event as **no discovery at all**.
- **§14.4 a dated forecast**: hip-hop's 5% over-55 liking figure must be a *period* effect, since
  the genre's first formation-window cohorts are only now in their mid-50s–60s. If it is still ~5%
  in 2040, bump-anchoring as an explanation of genre-age demographics is in trouble. Cheap to check
  with existing repeated cross-sections; the competing account predicts the opposite.
- **§10 documented cascade**: Olivia Rodrigo's "good 4 u" retroactively crediting Hayley Williams and
  Josh Farro of Paramore ("Misery Business", 2007), 50% combined royalty share, as an interpolation.
  Rare case where cross-generational transmission is *registered* rather than inferred — and it shows
  the cascade can travel through re-encoded style rather than the original recordings, which no
  release-year-distribution measure would detect.
- **§13** trajectory table given more artists per phase.
- **§18 H8 added**: sync/virality events as natural experiments. This came directly out of writing
  §14.3 and is, I think, the most tractable new design in the paper — dated, exogenous, and it holds
  the music and access cost constant across cohorts.
- Appendix A extended to 21 rows.

## Still open after v4.0

- **Author byline for the UMAP 2025 "Soundtracks of Our Lives" paper** — arXiv/ACM pages were
  blocked by the network egress proxy from this session; the paper currently cites it by title and
  venue. Verify and add the byline. (Do not guess it.)
- **Cohort vs. development.** Unresolved, and load-bearing for §7/§8/§17. Only H1 settles it.
- **Kalia (2015) remains Tier C.** Primary post verified, but not peer-reviewed and without
  replicable methods detail. §5.2 corroborates the shape, not the ~33 figure.
- **Constraint vs. selectivity in late life** (§15) — not directly compared in the music domain.
- **Categories 2 vs. 3 in §14** (young streaming-era discoverers vs. cascading-bump inheritors) —
  indistinguishable without parental-cohort data, which no current dataset carries.
- **Non-Western music, not just non-Western listeners.** Every cross-cultural study cited tests
  reactions to *Western* music. The question of whether MUSIC-like dimensions organize listening in
  other tonal/rhythmic traditions is essentially untouched here.
- **Whether to actually run §18.** The protocol is specified; nothing has been executed. Decision
  point for the project.

## Hypotheses (now formalized as H1–H8 in the paper's §18)

1. **H1** Within-person content drift matches the cross-sectional gradient (and is smaller).
2. **H2** Behavioral replication of the bump, availability-normalized, multi-modal, with H2c
   distinguishing developmental from pure-exposure accounts.
3. **H3** The gender convergence: later bump peak *and* slower discovery decline in women, in one
   dataset.
4. **H4** Discovery decline is chart-following, not curiosity (new-to-world falls faster than
   new-to-listener).
5. **H5** Social-context proxies beat chronological age at predicting discovery rate.
6. **H6** Streaming-native cohorts' bump decouples from release year.
7. **H7** Breadth is non-monotonic across the observable age range.
8. **H8** *(new)* Sync/virality catalog shocks as natural experiments: adoption of the affected
   track declines with listener age even with exposure, access cost and the music held constant.
   Falsified if adoption is flat in age — which would localize the whole discovery decline in
   *exposure opportunity* rather than in responsiveness.

---

# Pre-v4.0 log (retained)

## Confirmed, primary-sourced (updated 2026-08-06, second pass)

- Reminiscence bump for music: adults disproportionately prefer/remember music from adolescence–mid
  20s. Original finding: Holbrook & Schindler (1989), peak ~23.5. Methodologically extended:
  Jakubowski et al. (2020, cross-sectional, autobiographical-memory framing).
- **Gender difference in bump timing — now primary-sourced.** University of Jyväskylä (2025), global
  study, ~2,000 participants across 84 countries, published in *Memory*
  (https://www.tandfonline.com/doi/full/10.1080/09658211.2025.2557960): aggregate peak of
  meaningfulness ~age 17 (inverted-U); **men peak ~15.9** with a stable bump into old age, **women
  peak ~19** with a stronger recency effect (later-life music stays meaningful alongside the
  adolescent peak). This supersedes the earlier note that only had secondary-coverage support — cite
  this study directly in the paper, not Jakubowski, for the gender-timing claim (Jakubowski doesn't
  report a gender split at this resolution).
- Kalia (2015, Spotify/Echo Nest data): active new-music discovery rises through teens, declines
  through 20s, stabilizes ~age 33. Faster decline for men than women. Having children predicts a
  sharp drop in mainstream listening independent of age. Still only secondary-sourced (Kalia's
  original Skynet & Ebert post; located via statsignificant.com's coverage) — the original post
  itself hasn't been directly verified as still live/accessible.
- **Rentfrow & Gosling MUSIC model — now integrated (paper §4).** Original 2003 paper found four
  preference dimensions (Reflective & Complex, Intense & Rebellious, Upbeat & Conventional, Energetic
  & Rhythmic); later work refined this to five, the MUSIC model (Mellow, Unpretentious, Sophisticated,
  Intense, Contemporary). Openness to experience is the most consistent personality correlate,
  predicting preference for Reflective & Complex and Intense & Rebellious music. Primary source:
  https://gosling.psy.utexas.edu/wp-content/uploads/2014/09/JPSP03musicdimensions.pdf. Replication:
  Rentfrow et al. (2012), "The Song Remains the Same."
- **Openness-to-experience / age question — partially resolved.** Setti & Kahn (2024) find that once
  *uses of music* and age are controlled for, general personality traits (including openness) lose
  predictive power for moment-to-moment music consumption relative to those two variables — read in
  the paper as evidence that the personality→preference-content link is comparatively age-stable,
  while age instead governs sampling/discovery behavior (§3), not which region of preference-space a
  listener occupies (§4). This is one paper's framing, not a consensus finding — flag as a single
  source, not settled, in any revision that cites it more strongly.

## Not yet integrated / still open

- Cross-cultural / cross-genre generalizability: the Jyväskylä 2025 study is a genuine improvement
  here (84 countries) versus the earlier near-exclusively Western/US-UK sourcing, but Kalia (2015)
  and Rentfrow & Gosling (2003) are both US-sample-based. Worth an explicit limitations paragraph in
  the next full revision rather than assuming the whole model generalizes globally.
- Streaming-era generational shift: search results flagged that younger listeners' broader
  streaming-driven access to older music might change what "openness" even measures generationally
  (a 20-year-old today has trivial access to 1960s catalogs a 20-year-old in 1995 didn't) — not yet
  chased to a primary source. Could matter for whether the reminiscence-bump timetable itself is
  stable across generations (see hypothesis 2 below) or will shift for the streaming-native cohort.

## Hypotheses to test empirically (see draft.md §6)

1. Life-stage variables (partnering, parenthood, job change) predict discovery-rate decline better
   than calendar age alone.
2. The reminiscence-bump window is stable across generations (i.e., a 60-year-old's bump and a
   25-year-old's future bump will land in the same *relative* life period, teens–mid-20s), rather
   than shifting with each generation's media environment. Streaming-era access (see above) is a
   live threat to this hypothesis, not just a footnote.
3. Genre/era diversity (measured as entropy of a listener's play distribution) narrows with age but
   plateaus rather than continuing to shrink indefinitely.
4. *(New)* A listener's MUSIC-model region (§4) is set early and stable; what changes with age is
   sampling rate/breadth (§3), not the region itself. Testable by tracking whether an individual's
   genre-preference *centroid* stays put over years of listening history even as *diversity* around
   it narrows.

## Data-access questions for the empirical extension

- Personal Spotify "Extended Streaming History" exports are single-user (this listener only) —
  population-scale analysis needs either: (a) a public dataset (e.g., academic Last.fm datasets),
  or (b) multiple volunteers' exports pooled with consent, or (c) partnership/API access not
  currently available to this project.
- Need to check licensing/ethics for any existing public listening-history dataset before use —
  not yet researched.

## v3.0 — genre/artist-level age data added (2026-08-06)

Added new §6, "Broader evidence: genre- and artist-level age data" — a population-level survey/
industry-data table (Nielsen, Luminate, gitnux.org, headphonesaddict.com, Defector Music) covering
hip-hop, dance/pop, rock, country, classical, progressive rock, metal, and pop-punk age skews, read
against the timing/content model. Notable findings pulled in: hip-hop/dance/pop skew sharply young
(consistent with §3's discovery-decline curve); country/classical/rock skew older (consistent with
bump-anchoring, §2); progressive rock and pop-punk both show *bidirectional* age traffic — prog's
audience shifted measurably younger between a 2016 survey (~75% over 45) and a 2020 survey (63%
under 45), and pop-punk sustains both a live 15–25 core (Warped Tour ~90% ages 15–25) and an
acknowledged older nostalgia audience. This directly informed and validated the §5 illustrative
case's framing of Blink-182 as a childhood/gateway entry point rather than evidence against the bump
model.

**Important caveat, carried into the paper itself (§6's closing note, and a new Limitations bullet
in §9):** this section's sources are industry/survey aggregators, not peer review, and none report
full sampling methodology (the progressive-rock figures in particular rest on one fan-run survey).
Treat as directional corroboration of §2–§4's peer-reviewed model, not equivalent-weight evidence.

Sections renumbered: old §6 (Reconciling) → §7, old §7 (Open questions) → §8, old §8 (Limitations)
→ §9, old §9 (Conclusion) → §10. All in-text cross-references checked and updated across the whole
document (verified via `grep -n '§[0-9]'` after edits — see the paper's version history for what
changed).

## v2.0 — paper complete (2026-08-06)

Final polish pass: abstract rewritten to summarize all 9 sections (was written when the paper only
had 8, then only partially updated after §5 was added); introduction now previews all three guiding
questions with section pointers instead of just two; References header dropped the "working
list — verify/complete" caveat since every citation now has a real source location (though the
individual verification items below — Kalia primary source, Jyväskylä author byline — remain open
and are not the same thing as "unsourced"). The paper is a complete, internally consistent
literature-review-and-synthesis piece as of this version. Remaining work is the verification items
in "Next steps" below and the decision on the empirical extension — neither blocks calling this
draft complete.

## v1.1 addition (2026-08-06)

Added new §5, "Illustrative trajectory: mapping age ranges to listening tendencies" — a
composite/illustrative case (not a real validated data point) walking childhood pop-punk (Blink-182)
→ teenage Britpop (Blur, Oasis, the bump-formation window) → adult progressive rock/metal (Dream
Theater, Porcupine Tree, Tool), mapped onto the timing axis (§2/§3) and content axis (§4). Explicitly
flagged in the paper as illustrative/anecdotal, not a validated pattern — the real test of whether
this generalizes is the empirical extension in §7 (now renumbered from §6 to make room for §5).
All section numbers 6–9 shifted by one from v1.0; cross-references updated throughout.

## v1.0 status (2026-08-06)

Paper is now a complete first draft: introduction, reminiscence bump (§2), discovery-decline (§3,
with an explicit sourcing caveat since Kalia 2015 remains secondary-sourced only), MUSIC
model/openness (§4), reconciliation (§5), proposed empirical extension (§6), limitations (§7,
written into the paper itself — Western sourcing imbalance across the three empirical pillars,
streaming-era confound, correlation-vs-mechanism, single-source claims), and conclusion (§8).

## Next steps

- Verify the Kalia (2015) Spotify/Echo Nest finding against a primary source if the original
  Skynet & Ebert post is still accessible, rather than relying solely on secondary coverage —
  still open, flagged in the paper's §3 and §7.
- Confirm the specific author byline for the 2025 Jyväskylä *Memory* study before citing a name
  in-text (currently cited by institution/journal/DOI only).
- Review the Malaysia-based MUSIC-model replication mentioned in §7 in more depth if the
  cross-cultural section needs strengthening.
- Decide whether this stays a pure literature-review/theory paper or gets the empirical extension —
  ask the user now that a complete draft exists.
