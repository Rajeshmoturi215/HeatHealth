HEATHEALTHAI SIH 2026 — STEPS 7, 8, 9 FINAL

STEP 7 — Automated Heat Action Plan
- Converts current HTSI/priority into recommended heat-action measures.
- Cooling centres, hospital preparedness, outdoor-work changes, vulnerable checks, power and water readiness.

STEP 8 — Emergency Prioritisation
- Ranks demo local areas using thermal stress + vulnerability + exposure.
- Shows top-priority areas and population.

STEP 9 — Heat Action Command Centre
- Shows intervention triggers and operational owners.
- Demonstrates the flow: risk detected -> area prioritised -> action recommended -> authority activates.

Important:
- This is an SIH prototype.
- Population figures are synthetic/demo values.
- Mortality and hospitalization values are risk indicators, not clinical probabilities.
- The intervention engine recommends actions; it does not claim autonomous government activation.
- No real SMS/WhatsApp messages are sent by Steps 7–9.

Run:
1. cd C:\Users\user\Desktop\SIH2026
2. py -m pip install -r requirements.txt
3. py -m uvicorn main:app --reload
4. In another terminal:
   cd C:\Users\user\Desktop\SIH2026\frontend
   py -m http.server 5500
5. Open http://127.0.0.1:5500
