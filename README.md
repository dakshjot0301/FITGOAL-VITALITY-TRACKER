# FITGOAL-VITALITY-TRACKER

Vitality — Diet & Fitness Tracker
A single-file, browser-based health tracker. No server, no account, no installs — just open the HTML file and start tracking.

Getting Started

Download vitality_tracker.html
Open it in any modern browser (Chrome, Firefox, Safari, Edge)
Everything runs locally — your data is saved in the browser's localStorage


Features
Dashboard
The home screen gives you a daily snapshot:

Calories consumed vs. your goal
Protein intake
Water glasses logged
Workouts completed this week
Macro progress bars (calories, protein, carbs, fat)
Today's food log and calorie balance
Recent workout history

Calorie Calculator
A 3-step wizard using the Mifflin-St Jeor equation:

Enter age, sex, height, weight
Choose activity level and goal (lose / maintain / gain)
Get your daily calorie target, BMR, TDEE, and recommended macros

Results can be saved directly to your profile goals with one click.
Age-specific guidance is included for children, adolescents, adults, and seniors.
Diet Log

Log meals by type: Breakfast, Lunch, Dinner, Snack, Pre/Post-workout
Track calories, protein, carbs, and fat per meal
Quick-add buttons for 10 common foods (eggs, oats, chicken breast, dal, roti, etc.)
Daily totals with comparison against your goals
Filter log by date

Workout Log (Hevy-style)
Exercise tracking modelled after the Hevy app:

Exercise cards — each exercise gets its own card
Set-by-set rows — log weight (kg) and reps individually per set
Completion checkboxes — mark sets done; rows turn green, volume auto-calculates
Add / remove sets freely per exercise
Quick templates — Push Day, Pull Day, Leg Day, Cardio, HIIT, Yoga load pre-built exercises with 4 empty sets each
History view — past workouts display each exercise with individual set pills

Progress Tracker

Log body weight, body fat %, and waist circumference over time
Weight trend chart (Chart.js line graph)
Summary stats: current weight, total change, lowest recorded, entries count
Full history table with delete option

Profile & Goals

Personal info: name, age, height, weight, sex, activity level
Set custom daily goals: calories, protein, carbs, fat, water
Goals saved to localStorage and used across all views


Data & Privacy
All data is stored in your browser's localStorage — nothing is sent to any server, ever.
Export
Go to Profile → Export as JSON to download a full backup of your meals, workouts, progress, and goals.
Clear Data
Profile → Clear all data permanently wipes everything from localStorage and reloads the app.
