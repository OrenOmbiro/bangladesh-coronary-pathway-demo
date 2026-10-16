# Bangladesh coronary pathway demo — screen mock-ups

Clickable mock-ups for the dummy demo of the NCD corner → cath-lab hub pathway, with the coordination layer between them.

- `index.html` — landing page with links to both systems
- `NCD_corner_screens.html` — five corner screens (due-list, visit, patient journey, referral and Find-a-service, inbox)
- `Cath-lab_hub_screens.html` — four hub screens (referrals, discharge and plan, hub review, service register)
- `UHC_decision_support.html` — the UHC record with recommendations: a worklist, a reminder tray, and three encounters (chest pain in the emergency room, upper abdominal pain in outpatients, a hypertension review at the NCD corner) in which the prompts fire as the clinician enters the complaint, orders and results; `#patient/karim`, `#patient/rokeya`, `#patient/shirin` and `#reminders` open a given screen

Each file is self-contained: open it in a browser, or serve it from GitHub Pages. Screens re-date themselves to the current week; `?site=sylhet` switches the facility names, ambulance times and cath-lab centres from Bogura to Sylhet; `#visit`, `#review` and the other menu slugs open a given screen.

The corner and hub screens are static mock-ups: buttons do not act. In the UHC record the recommendations respond, but nothing is saved or sent; the AI reads, the cardiologist's replies and the hub's acknowledgements are simulated and arrive a few seconds after you act. Public facilities are real; the private clinic is invented, and all patients, staff names, dates and appointment slots are illustrative. The ECGs are synthetic traces drawn to scale.
