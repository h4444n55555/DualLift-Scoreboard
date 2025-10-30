# DualLift-Scoreboard Interface Flow 

## 1. Start: Event Selection Screen
- User selects the type of competition:
    - **Olympic Weightlifting** (Snatch, Clean & Jerk)
    - **Powerlifting** (Squat, Bench Press, Deadlift)
- This choice dynamically configures subsequent inputs and scoring logic.

## 2. Competition Setup
- Input field: **Competition Name**
- Input fields: **Weight Categories** for the event (e.g., 61kg, 73kg)
- These define the categories available for lifter registration.

## 3. Lifter Registration Form
- Fields captured for each lifter:
  - Name
  - Team/College
  - Bodyweight
  - Date of Birth
  - Weight Category (from setup categories)
  - Division (A, B, etc.)
  - First Lifts (initial attempt weights relevant to event type)
- Form dynamically adjusts fields based on event type.

## 4. Attempt Logging and Result Input
- For each lifter:
  - Manual input of attempted weight for each lift.
  - Success/Fail/Under Review status toggles:
    - Good lift: green indicator
    - No lift: red indicator
    - Under review: yellow indicator
- Track 3 attempts per lift type (snatch/cj or squat/bench/deadlift).

## 5. Displays
### Audience Display
- Shows the current lifter’s name.
- Current attempt weight.
- Referee decision indicators (white and red lights).

### Detailed Scoreboard
- Shows all lifters in the competition.
- Displays attempts with weight and result status (color coded).
- Lifter details: Name, DOB, Team, Total score, Rank.
- Updates live as attempts are logged.

## 6. Timer Component
- Visible countdown timer for each attempt.
- Buttons to start, stop, reset timer.
- Editable timer length to customize attempt duration.

## 7. Miscellaneous Notes
- Designed primarily for desktop use initially.
- Later versions may consider responsive design for tablets and phones.
- Simple, clear UI prioritized for ease of use during competitions.
- All inputs and displays update dynamically for live event management.

---
