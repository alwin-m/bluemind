BlueMind is a vanilla HTML/CSS/JS web application that renders a personalized “life in weeks” timeline based on user-provided name and birth date. It computes elapsed time, remaining lifespan (80-year model), and a suite of derived biometric / behavioral metrics, presenting them through interactive, progressively-enhanced UI components.

Core Model: 80 years × 52 weeks = 4 160 discrete week units.
Rendering: CSS Grid + DOM for the week matrix, animated progress bar, stat cards, motivational overlays.
Interactivity: Form validation, birthday detection, quote rotator, reset flow, smooth page transitions.
Deployment: Zero-dependency; static file hostable (GitHub Pages, Netlify, Vercel, etc.).

Data Flow

Input → userName, birthdate (HTML <input>).
Validation → Real-time enable/disable of submit; max-date = today.
Computation → calculateStats() returns a plain object:

<img width="1200" height="1200" alt="BlueMind" src="https://github.com/user-attachments/assets/a0595ee4-9ecb-463b-a1cc-c8e2ea627de8" />

