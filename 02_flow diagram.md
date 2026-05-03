# Assistant Flow

START
 ↓
Ask user intent:
   ├── Check eligibility
   ├── Learn about elections
   ├── Register to vote
   └── Voting process

IF Check:
   → Ask age
   → If they're 18+, eligible to vote. Othervise, not eligible.
   
IF Learn:
   → Explain elections simply
   → Offer deeper explanation

IF Register:
   → Ask age
   → Ask country
   → Ask identity 
   → Provide registration steps

IF Voting:
   → Ask registration status
   → Give voting day instructions

END:
Always give next actionable step that satisfies user
