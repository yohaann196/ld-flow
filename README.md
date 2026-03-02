# LD Flow!!
![GitHub stars](https://img.shields.io/github/stars/yohaann196/ld-flow?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/yohaann196/ld-flow?style=flat-square)
![Made with](https://img.shields.io/badge/made%20with-vanilla%20JS-yellow?style=flat-square)
![Supabase](https://img.shields.io/badge/backend-Supabase-3ecf8e?style=flat-square)
![Hosted on](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-blue?style=flat-square)

*flow tool built for Lincoln-Douglas debate.*

## Features (some are implemented; some are future ideas/checklist)

**flowing**
- 8 speech columns: AC, CX, NC, CX, 1AR, CX, NR, 2AR
- Tag each argument: value, contention, impact, or drop
- Cards (flow bullet points) auto-resize as you type, Shift+Enter to add a new card
- draggable arrows for argument tracking (?), drag and drop cards/copy paste cards (?)
- Toggle crossfire columns on/off to cut down on visual noise

**timers**
- Speech timer with a dropdown for each speech and its standard time
- Separate Aff and Neg prep timers - only one can run at a time
- Color feedback: blue while running, orange at 30 seconds, red when over

**export**
- Export any flow to a landscape PDF with speech columns, tags, and resolution header

**settings**
- Dark mode
- Rename, add, or remove tag labels
- Edit speech names, abbreviations, and time labels
- Show/hide crossfire columns
- Adjust prep time and card font size
- Settings persist locally across sessions

## stack

- Vanilla HTML, CSS, JavaScript — no framework
- [Supabase](https://supabase.com) for auth and cloud storage
- [jsPDF](https://github.com/parallax/jsPDF) for PDF export
- [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) via Google Fonts

---

If this saved you time at a tournament, consider starring the repo ⭐
