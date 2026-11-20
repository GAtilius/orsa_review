# FA49 ORSA Skill Set Study

A static website, served with GitHub Pages:

- `index.html`: landing page
- `deck/`: the five-slide briefing (arrow keys to move, **N** for speaker notes, **Print / save PDF** for a handout)
- `analyzer/`: the survey analyzer for future Microsoft Forms exports

The site makes no requests to outside hosts. Fonts and the spreadsheet reader are included in the repository.

## Survey data stays off this site

The analyzer reads `.xlsx`, `.xlsm` and `.csv` files in the browser. Nothing is uploaded. **Never commit survey exports to this repository:** it is public. `.gitignore` blocks spreadsheet and CSV files as a safeguard.

## Updating the analyzer for a new survey

The analyzer finds questions by their wording, not their column position. New skill questions in the form's standard wording ("Select the statement that best reflects your educational training & your ability to …") are picked up automatically. Any other new question appears on the **Answers by question** and **Free text** tabs.

## Disclaimer

Unofficial working product. Not an official U.S. Army website or publication, and not endorsed by the Department of the Army or the Department of Defense.

## Third-party components

See `THIRD-PARTY-NOTICES.md`.
