# Right to Second Life Ontario: campaign landing page

Landing page for **Right to Second Life Ontario**, a fictional organization created by Team 4 for a Seneca Polytechnic course assignment. The campaign calls for opt-out organ and tissue donation in Ontario for everyone 16 and older, with no family veto.

Live site: https://righttosecondlife.netlify.app/ (mirror: https://trangphan0301.github.io/right-to-second-life-ontario/)

## What's on the page

- The three main actions: **Download & print the petition**, **Pledge your support** and **Find a signing location**
- The counter "Paper signatures collected: 500 of 10,000"
- The Issue: waitlist and registration figures, with sources
- Our Ask: what the proposed law would include
- Stories: the animated film *A Decision Made at 16*, with voice-over and a transcript (dramatization; characters are fictional)
- Petition: the paper petition (PDF), how to collect signatures, and the pledge form
- Newsroom: media kit, spokespeople and media contact

The pledge form is a demo. It collects no names, emails or other personal information, and a pledge is stored only in the visitor's own browser. Ontario accepts paper petitions only, so pledges are not counted as signatures.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole page: content, styles and scripts |
| `media/a-decision-made-at-16.mp4` | The animated film with voice-over (1:22) |
| `media/poster.jpg` | Video poster and link-preview image |
| `media/petition.pdf` | Printable petition, one letter-size page |

## Updating the signature counter

Open `index.html` and find this line:

```html
<div class="tally" id="tally" data-collected="500" data-goal="10000">
```

Change `500` to the new number of paper signatures, then commit. The number, the progress bar and the screen-reader label update automatically.

## Sources

- Trillium Gift of Life Network (2026): waitlist as of Oct. 18, 2026, deaths while waiting, support and registration rates.
- CBC News (2016): families of registered donors who declined donation, 2015 data.

The page and the animated film were made with help from Claude, an AI model by Anthropic.
