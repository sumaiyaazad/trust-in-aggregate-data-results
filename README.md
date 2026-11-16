# Explaining Trust in Aggregate Data Results

Study materials for a think-aloud study of how people decide whether to trust an average computed from public NYC taxi data, with and without a short data-quality check. The study was my individual project for CS 6540, Graduate Human-Centered Computing, at the University of Utah in Fall 2026.

## The study interface

The study ran on one web page, which is in this repository as `index.html`. It is live at:

https://sumaiyaazad.github.io/trust-in-aggregate-data-results/

To try it, pick a participant number and click Begin session. The page then runs a full session: consent, four background questions, a warm-up with a tour, four scored cases, six closing questions and a debrief. Nothing installs and nothing is uploaded. At the end the page offers a session file to download.

Each participant number has a fixed order of cases. Tasks 1 and 2 use one version of the screen and tasks 3 and 4 use the other. The basic screen shows the sentence to check, four summary tiles and the trip table. The explanation screen adds a yellow box with a one-line finding, the rows it refers to highlighted in the table, and the average without those rows.

## What is here

| Folder or file | Contents |
|---|---|
| `index.html` | The study interface, as used in the sessions with the bugs found during collection fixed afterwards |
| `materials/consent_form.md` | The on-screen consent form |
| `materials/questions.md` | The four background questions and six closing questions |
| `materials/session_script.md` | How a session was run, with the exact words said |
| `materials/pilot_checklist.md` | What the pilot session found and what changed |
| `screenshots/` | The warm-up tour, the basic screen and the explanation screen |

## Data

The cases come from the NYC Taxi and Limousine Commission Yellow Taxi Trip Records for June 2024, a public dataset. The duplicated trips in two of the cases were added on purpose; the zero-mile trips in the other two are in the source data.

Participant recordings, transcripts and session files are not included.
