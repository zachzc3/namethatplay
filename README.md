# Name that Play

Watch a famous sports moment, guess when it happened, flip the card.

- **Shuffle deck** of plays, each with a YouTube clip. The clip plays first; flip the card to see the year, the full date, the sport and a one-line explanation of the play.
- Filter by sport, decade or fame. Works offline except for the clips themselves.
- Open a specific card with `?p=p042`.

`plays.json` is generated from `Name that Play - Master List.xlsx` with `Build Tools/build_plays_json.py`.
Edit the spreadsheet, run the script, commit `plays.json`. Card ids are tied to the YouTube video id and never renumber.
