# Pilot checklist

Run **one or two pilot sessions** before the first real participant. Pilot participants
are not counted among the six and their data is not analyzed.

The pilot exists to find problems in the study interface, not to preview the results.

## What the pilot must confirm

**Timing**
- [ ] Whole session fits in 45 minutes without rushing the interview
- [ ] Warm-up is long enough to make the screen familiar
- [ ] Record the actual per-task times to set expectations

**Comprehension**
- [ ] Participant understands what one "result" covers, one zone, one hour, one date
- [ ] All four decision options are distinguishable. **Watch "not yet, something needs
      checking" against "fix a specific problem" especially.** That pair carries the
      over-cleaning measure: a participant who cannot tell them apart may pick "fix"
      because it sounds more decisive, and be recorded as over-cleaning when they were
      misreading the menu. If a pilot participant cannot articulate the difference,
      reword before the real sessions
- [ ] Participant knows what the confidence rating is about (the decision, not the data)
- [ ] No column heading needs explaining twice

**Think-aloud**
- [ ] Participant actually talks. If not, lengthen the think-aloud warm-up
- [ ] The neutral prompts do not feel like corrections

**Interface**
- [ ] Sorting and filtering work under real use
- [ ] The interface-switch notice is noticed and understood
- [ ] The sensitivity preview is not read as "the right answer" *by design*, if the
      pilot participant reads it that way, that is a finding, but check the wording is
      not causing it
- [ ] Nothing on screen reveals which cases were manipulated

**Facilitation**
- [ ] I can take useful notes and stay quiet at the same time
- [ ] No accidental leading, confirming, or reacting. Review the recording for this
- [ ] Session JSON downloads and contains everything expected

**Materials**
- [ ] Consent form is clear without verbal explanation
- [ ] Screening rule in the background questionnaire is workable
- [ ] Interview questions produce more than one-word answers

## After the pilot

The changes are recorded at the end of this file.

> **The only output of a pilot is a list of changes**, recorded below. Nothing from a
> pilot session enters the analysis or the findings.

> **If a change alters what participants see or how decisions are scored**, case
> content, decision wording, the answer key, note it explicitly in the report, since
> the design was otherwise frozen before data collection. Changes to my
> phrasing, timing, or note-taking do not require this.

## Pilot 1: what it found and what changed

The session took 54 minutes.

| What the pilot showed | Evidence | Change made |
|---|---|---|
| The warm-up taught nothing about the check panels; the participant met them cold in case 3 | "this is new", "what does sensitivity mean", "I'm gonna have to take some time here" | Warm-up now uses the explanation layout for everyone, with a four-step on-screen tour that shows an example of a fired check and a highlighted row |
| Too much text in the explanation condition | "there's a lot of reports here"; "the sensitivity preview was too weird for me to analyze, I totally skipped it" | Three panels collapsed into one yellow box: one-line finding, the row IDs, one hedge sentence, one line giving the average without those rows |
| Comparable zone-hours confused rather than helped, and drove confidence to 1 on N1 | "what does this have to do with the three problematic rows"; "what is the metric being used here for similarity"; explanation: "the similarity metrics were not mentioned" | Comparable zone-hours removed from the interface. The condition is now three components, not four |
| Extra table columns were noise | "The last four column names were confusing. If those columns were not necessary, why keep them there?" | Table reduced to Row, Pickup, Drop-off, Minutes, Miles, Fare. No horizontal scroll |
| "Mean" and "Min" were confused | "I don't understand what does it mean to have a mean fare"; "mean like average I'm talking about M-I-N" | Tiles say "Average fare" etc.; the column is "Minutes" |
| The task itself was unclear | "Tell me, what am I supposed to check?"; "I'm judging the correction right?" | Each case now leads with the draft sentence in quotes, and the decision asks "Should this sentence go into the draft?" |
| The query panel was never used | no mention in 54 minutes | Removed; replaced by "Computed from the 38 trips below" |
| Too many questions | 11 background, 13 closing; session 54 min | 4 background, 6 closing |
| 38-row tables were more than one screen could show, and more than the participant could scan | "There were too many data points for me to look at"; "it's a lot of data to look at" | Cell-size band tightened from 20–60 to 20–24 trips and all four scored cases regenerated (T0 unchanged). Every case now fits on one screen. Side effect: the 0.6% duplicate is gone; both pairs are matched on effect size |

Everything in the right-hand column changes what participants see, so it is logged here
before any study session. The analysis plan and coding rules were updated to match.
