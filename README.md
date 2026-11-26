# My Student Portal (`CSIT248-portal-5073`)

- **Name:** Sherov Mironshox
- **Enrolment Number:** 5073

## Computed Values
- **P (password min length):** 9
- **M (name max characters):** 25
- **S (students in JSON):** 6
- **K (my marks):** 60
- **T (pass mark):** 43
- **C (accent colour):** `steelblue`

## Reflection
1. **Bug that cost the most time:** Fetching `students.json` failed initially because I opened `board.html` directly via `file://` instead of a local HTTP server.
2. **How I found it:** I opened the browser DevTools Console and saw the CORS/fetch error, then switched to VS Code Live Server (`http://127.0.0.1:5500`).
3. **One thing I would add with another hour:** I would add a search input on the marks board to filter students by name or city in real time.
