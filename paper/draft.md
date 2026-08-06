# Taste as It Ages: Age, Openness, and the Evolution of Music Preference Across the Listening Life

*Working draft — v0.1*

## Abstract

Music preference is often treated as fixed once formed, but a growing body of psychological and
behavioral-data research shows it follows a predictable arc across the lifespan: rapid crystallization
in adolescence and young adulthood, a lasting bias toward music from that period (the "reminiscence
bump"), and a gradual narrowing of active discovery from the late 20s onward. This paper reviews that
evidence, proposes an integrated model of *why* taste stabilizes when it does, and outlines an
empirical extension using streaming listening-history data to test the model against real cohorts
rather than retrospective self-report alone.

## 1. Introduction

Ask someone what music "moved" them most and, disproportionately, the answer comes from their
teens or twenties — regardless of how old they are now. This is not simple nostalgia; it is a
well-documented and repeatable finding across self-report and behavioral data. This paper asks two
related questions:

1. **How does music taste change with age** — what widens, what narrows, and when?
2. **Why** does it change on that particular timetable, rather than continuously or randomly?

## 2. The reminiscence bump

The reminiscence bump is the finding that autobiographical memories — and preferences tied to them —
cluster disproportionately around adolescence and early adulthood. Applied to music, adults rate
songs from roughly their teens through mid-20s as most personally significant and most preferred,
even decades later. Holbrook & Schindler's foundational 1989 study put the peak of preference at
around age 23.5. More recent cross-sectional work (Jakubowski, Eerola, Tillmann, Perrin & Heine,
2020) replicates the effect and finds it is not uniform: men's bump tends to peak earlier, around
16, while women's peaks later, past 19 — consistent with the idea that musical identity consolidates
around different developmental milestones (peer-driven independence for men, relationship and
emotional milestones extending later for women, per the psychological literature reviewed).

Two mechanisms are usually invoked to explain the bump:

- **Neurocognitive**: adolescence and early adulthood are a period of heightened memory encoding
  generally (the same bump appears for autobiographical memories unrelated to music), so anything
  experienced then — including music — gets consolidated more vividly.
- **Identity formation**: music functions as a social and identity marker precisely during the years
  when identity is actively being built, giving songs from that window outsized emotional weight
  independent of memory mechanics alone.

## 3. The narrowing: when do we stop finding new music?

Self-report explains *what* people say they prefer; behavioral data shows *what they actually do*.
Kalia's 2015 analysis of U.S. Spotify listening data (combined with Echo Nest artist-popularity
metrics) found active discovery of new/mainstream music rises through the teens, then declines
steadily through the 20s, with listeners statistically settling into a stable, non-expanding
repertoire by around **age 33**. The decline is not identical across groups: it is faster for men
than women, and the arrival of children predicts a sharp drop in mainstream/new-music listening
regardless of the listener's age at the time — suggesting the mechanism is at least partly about
*available attention and lifestyle bandwidth*, not age itself.

This distinction matters: age may be a proxy for several independent forces (identity stabilizing,
free time shrinking, social contexts that introduce new music becoming less frequent) rather than a
direct cause.

## 4. Reconciling the two effects

Put together, the reminiscence bump and the discovery-decline finding describe the same arc from two
angles:

- **Formation** (teens–mid-20s): high discovery rate, active identity-building, taste crystallizes
  and gets emotionally "stamped" with above-average intensity.
- **Stabilization** (late 20s–30s): discovery rate falls, the already-crystallized catalog from the
  formation window becomes the enduring reference point, and new intake increasingly gets filtered
  through — or judged against — that reference point rather than evaluated fresh.
- **Maintenance** (30s onward): taste doesn't disappear or freeze completely — openness varies by
  individual, and life events (not just birthdays) can reopen active discovery — but the *default*
  trajectory is toward a stable, bump-anchored repertoire rather than continued expansion.

This reframes "does taste change with age" as a question with two different correct answers depending
on what's measured: preference *content* stays remarkably stable once formed (bump-anchored), while
preference *breadth/discovery behavior* has a real, largely monotonic decline that only loosely tracks
calendar age and more directly tracks life-stage variables (partnering, parenthood, career demands).

## 5. Open questions / proposed empirical extension

The above is a synthesis of prior literature, not new data. To test it rather than restate it, a
natural next step is a **cohort analysis on real listening-history data** (e.g., Spotify extended
streaming history, Last.fm scrobbles) that can separate:

- Age at time of listening vs. age of the music being listened to (bump timing, replicated
  behaviorally rather than by self-report).
- Discovery rate over time per listener, checked against life-event proxies where available
  (self-reported, or inferred) rather than age alone — to test whether "life stage" outperforms
  "age" as a predictor, per the children-effect finding above.
- Genre/era diversity (entropy of listening distribution) as a function of age, to see whether
  breadth narrows smoothly or whether it plateaus and holds.

See [`research-notes.md`](../research-notes.md) for the running list of hypotheses, data-access
questions (most listening-history exports are single-user and not population-scale without
partnership access), and sources still to review.

## References (working list — verify/complete before final draft)

- Holbrook, M. B., & Schindler, R. M. (1989). Some exploratory findings on the development of
  musical tastes. *Journal of Consumer Research*.
- Jakubowski, K., Eerola, T., Tillmann, B., Perrin, F., & Heine, L. (2020). A cross-sectional study
  of reminiscence bumps for music-related memories in adulthood. *Music & Science*.
  https://journals.sagepub.com/doi/10.1177/2059204320965058
- Kalia, A. (2015). *Skynet & Ebert* — Spotify/Echo Nest listening-data analysis on age and music
  discovery decline (age ~33 finding). Referenced via secondary coverage:
  https://www.statsignificant.com/p/when-do-we-stop-finding-new-music
- Frontiers in Psychology (2024). Revisiting the musical reminiscence bump: insights from
  neurocognitive and social brain development in adolescence.
  https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2024.1472767/full
- Rentfrow, P. J., & Gosling, S. D. (2003). The do re mi's of everyday life: The structure and
  personality correlates of music preferences. *Journal of Personality and Social Psychology*.
  (MUSIC model — to be integrated in next revision; not yet checked against current search results.)
