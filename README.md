# TSON: Take a Ticket

A casual browser game simulating a queue at a Kazakh public service center (TSON).
Single file, no external dependencies - opens in any browser.

## How to play
Open `index.html` in a browser, or play the hosted version via GitHub Pages.

- Take a ticket (e.g. B-148) and wait for your number on the board
- Each turn pick an action: wait, check the board, visit the buffet, ask to skip ahead
- Random events: operator's lunch break, frozen board, a grandma with "just one question", a queue jumper, EDS on a flash drive left at home, a call to 1414
- Watch your nerves (0% = you walk away with nothing) and the clock (18:00 = closing time)
- Finale: a rank from "TSON Legend" to "Hero on the edge" + a shareable result text

## Notes
- Game UI text is in Russian (target audience: Kazakhstan)
- Code and comments are in English
- No em-dashes in any user-facing text, per project style rules
- Session record kept in memory; share button uses the `SHARE_URL` constant
