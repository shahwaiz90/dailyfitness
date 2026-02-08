# 📚 FitFlow Feature Documentation

## ⚠️ **PERSONAL USE APPLICATION - NOT PRODUCTION READY**

Before reading features, understand:
- This app is **for personal use only**
- Data is **NOT encrypted**
- **NOT suitable for multiple users**
- **NOT compliant with HIPAA/GDPR**
- **NOT designed to scale beyond personal use**

---

## Table of Contents
1. [Dashboard Features](#dashboard-features)
2. [Tracking Features](#tracking-features)
3. [Analysis Features](#analysis-features)
4. [Profile Features](#profile-features)
5. [Advanced Features](#advanced-features)

---

## 🎯 Dashboard Features

### Quick Stats Cards

#### Net Calories Card 🔥
- **Shows:** Total calories from diet minus exercise calories
- **Color:** Purple gradient
- **Formula:** Diet - Exercise = Net Calories
- **Example:** 2000 cal eaten - 300 cal exercised = 1700 net
- **When to use:** Check this to see your actual calorie balance

#### Remaining Calories Card 🎯
- **Shows:** How many calories you can still eat today
- **Color:** Pink gradient
- **Formula:** Daily Target - Net Calories = Remaining
- **Example:** If target is 2000 and net is 1500, remaining is 500
- **When to use:** Plan your meals around remaining calories

#### BMI Card ❤️
- **Shows:** Your Body Mass Index and health status
- **Color:** Green gradient
- **Categories:**
  - Underweight: < 18.5 (blue)
  - Normal: 18.5-24.9 (green)
  - Overweight: 25-29.9 (orange)
  - Obese: ≥ 30 (red)
- **Formula:** (Weight kg / Height m²)
- **When to use:** Track overall health category

#### Weight Card ⚖️
- **Shows:** Your current weight vs target
- **Color:** Blue gradient
- **Updates:** When you log weight or on page refresh
- **Tracking:** Shows today's logged weight or last known weight
- **When to use:** Monitor weight progress daily

---

## 📝 Tracking Features

### Diet Intake Section

#### Quick Menu 📋
- **Purpose:** Fast add predefined foods
- **How to use:**
  1. Click "Menu" button in Diet section
  2. Browse foods tailored to your fitness goal
  3. Click any food to add it
- **Foods included:**
  - Weight Loss: 12 low-calorie options
  - Muscle Gain: 12 high-protein options
  - Endurance: 12 balanced options
- **Benefit:** 1-click adding, no typing needed!

#### Custom Entry 🎨
- **Name field:** Type any food name
- **Calories field:** Enter estimated calories
- **Add button:** Creates entry with timestamp
- **Example:** "Homemade pasta" + "450" calories
- **Tip:** Google "calories in [food]" for quick estimates

#### Entry List 📝
- **Shows:** All foods logged today
- **Info per entry:**
  - Food name
  - Time logged (HH:MM format)
  - Calorie amount
  - Delete button
- **Sorting:** Chronological (oldest first)
- **Editing:** Delete and re-add to modify

#### Total Calories Display 📊
- **Shows:** Sum of all diet entries
- **Color:** Orange
- **Updates:** Real-time when adding/removing
- **Example:** "1,850 cal" in bold

---

### Exercise Section

#### Quick Menu 💪
- **Purpose:** Fast add predefined exercises
- **How to use:**
  1. Click "Menu" button in Exercise section
  2. Browse exercises for your fitness goal
  3. Click any exercise to add it
- **Exercises included:**
  - Weight Loss: 10 high-intensity options
  - Muscle Gain: 10 strength options
  - Endurance: 10 balanced options
- **Shows:** Exercise name + duration + calories

#### Custom Entry 🏋️
- **Name field:** Type any exercise name
- **Calories field:** Calories burned (estimated)
- **Add button:** Creates entry with timestamp
- **Example:** "30 min jog" + "300" calories
- **Tip:** Use fitness watches or online calculators

#### Entry List 📝
- **Shows:** All exercises logged today
- **Info per entry:**
  - Exercise name
  - Time logged (HH:MM format)
  - Calories burned (negative display "-300")
  - Delete button
- **Color:** Red for burned calories

#### Total Calories Burned Display 📊
- **Shows:** Sum of all exercise entries
- **Color:** Red
- **Updates:** Real-time when adding/removing
- **Example:** "450 cal" means 450 calories burned

---

### Weight Logging 🏃

#### Weight Input
- **Frequency:** Once per day recommended
- **Best time:** Morning (before eating)
- **Unit:** Kilograms (kg)
- **Precision:** Can log 0.1 kg increments

#### Logging Process
1. Enter weight in input field
2. Click "Log Today's Weight"
3. Weight saves automatically
4. Updates on weight progress chart

#### Weight Tracking
- **Displayed:** In blue stat card
- **Stored:** With daily data
- **Used for:** Weight progress charts
- **Privacy:** Stored locally, never sent anywhere

---

## 📊 Analysis Features

### GitHub-Style Contribution Graph 📈

#### What It Shows
Visual representation of your tracking consistency over 52 weeks
- Each square = 1 day
- Green intensity = tracking activity level
- 7 squares per column = 1 week

#### Color Meanings
- **Empty (light):** No tracking that day
- **Low (light green):** <50% of target calories logged
- **Medium (medium green):** 50-100% of target
- **High (bright green):** 100%+ of target

#### Interactive Features
- **Hover:** Shows date and calories for that day
- **Visual:** Scales up slightly on hover
- **Update:** Refreshes after each log entry

#### Why It Matters
- Shows your consistency visually
- Similar to GitHub contribution graph
- Motivates daily logging
- Identifies patterns (active weeks vs inactive)

---

### Calorie Trend Chart 📉

#### What It Shows
30-day line chart of net calories

#### Data Points
- X-axis: Date (last 30 days)
- Y-axis: Net calorie amount
- Line: Your daily calorie trend

#### Visual Features
- **Line color:** Purple
- **Points:** Marked with dots
- **Area:** Filled gradient
- **Smooth:** Curved line for readability

#### What It Indicates
- If line trends down: Eating below target (deficit)
- If line is stable: Consistent eating
- If line trends up: Eating above target (surplus)
- Peaks and valleys: Calorie variation

---

### Weight Progress Chart 📊

#### What It Shows
30-day line chart of weight changes

#### Data Points
- X-axis: Date (last 30 days)
- Y-axis: Weight in kg
- Line: Your weight trend

#### Visual Features
- **Line color:** Green
- **Points:** Marked with dots
- **Area:** Filled gradient
- **Smooth:** Curved line for readability

#### What It Indicates
- Downward trend: Weight loss (if goal is loss)
- Upward trend: Weight gain (if goal is gain)
- Stable: No significant change
- Fluctuations: Normal (water, food weight)

#### Note
Only shows days when you logged weight.

---

### Statistics Cards

#### Average Daily Calories 📈
- **Calculation:** Sum of all net calories / days tracked
- **Updates:** After each log entry
- **Use case:** See if you're on track overall
- **Example:** "2,100 cal/day average"

#### Total Workouts 💪
- **Calculation:** Count of all exercise entries
- **Updates:** When you add exercise
- **Use case:** See how many times you've exercised
- **Example:** "47 total workouts"

#### Days Tracked 📅
- **Calculation:** Count of unique days with entries
- **Updates:** When you first log something that day
- **Use case:** See your consistency
- **Example:** "28 days tracked"

---

## 👤 Profile Features

### Profile Overview

#### Personal Information
- **Name:** Your entered name
- **Fitness Goal:** Selected goal with emoji
- **Current Weight:** Today's logged weight or starting weight
- **Height:** In centimeters
- **Target Weight:** Your goal weight

#### Health Metrics
- **BMI:** Calculated from weight and height
- **BMI Status:** Category (Normal, Overweight, etc.)
- **Daily Calorie Target:** Auto-calculated for your goal
  - Weight Loss: Deficit-based
  - Muscle Gain: Surplus-based (base + 500)
  - Endurance: Balanced

#### Goal Information
- **Weight to Lose/Gain:** Total amount needed
- **Timeline:** How many months to goal
- **Monthly Rate:** kg per month needed
- **Example:** "10 kg in 4 months = 2.5 kg/month"

#### Progress Bar
- **Visual:** Filled percentage
- **Shows:** Days elapsed / total days
- **Updates:** Daily
- **Color:** Purple to pink gradient

---

## 🎓 Advanced Features

### Nutrition Information Panel

#### Content When Expanded
1. **Average Daily Intake**
   - Women: 1,600-2,400 cal/day
   - Men: 2,200-3,000 cal/day

2. **Weight Loss Facts**
   - 500 cal deficit = 0.5 kg/week
   - Safe rate: 0.5-1 kg/week
   - Requires consistent deficit

3. **Muscle Gain Facts**
   - +300-500 cal surplus needed
   - Requires strength training
   - Consistent protein intake important

4. **Calorie Facts**
   - 1 kg fat = 7,700 calories
   - 1 lb fat = 3,500 calories
   - Deficit or surplus needed for change

---

### Motivation Card

#### Daily Motivation Display
- **Title:** "Keep Going!" 
- **Emoji:** Changes based on status
  - 🎯 When calories remaining
  - 🎉 When goal met

#### Information Shown
1. **Remaining Calories Message**
   - Dynamic text based on remaining amount
   - "You have X calories left to enjoy today!"

2. **Progress Bar**
   - Visual percentage of calorie usage
   - Fills as you eat more
   - Gradient color fill

3. **Daily Badge**
   - Shows current day number
   - Shows total days in goal
   - "Day 15 of 90" format

#### Psychological Benefits
- Daily affirmation
- Visual progress feedback
- Keeps you engaged
- Celebratory messaging when goal met

---

### Pie Chart (Calorie Summary)

#### What It Shows
Daily calorie breakdown:
1. **Consumed (Orange)** - Calories eaten
2. **Burned (Red)** - Calories from exercise
3. **Remaining (Purple)** - Remaining calories

#### Interactive Features
- **Hover:** Shows values for each segment
- **Legend:** Below chart with labels
- **Updates:** Real-time as you add entries

#### Interpretation
- Large consumed section = ate a lot
- Large burned section = exercised a lot
- Large remaining section = haven't eaten much
- All three balanced = good control

---

## 🔐 Data & Privacy Features

### Local Storage
- **Location:** Browser's localStorage
- **What's stored:**
  - User profile (name, weight, height, goal, date)
  - Daily entries (diet, exercise, weight)
  - All data from day one
- **Access:** Only this browser/device
- **Backup:** Manual via browser developer tools

### Data Persistence
- **Automatic:** Saves after every action
- **Sync:** Not synced across devices
- **Offline:** Works without internet
- **Backup:** No automatic cloud backup

### Privacy
- ✅ No data sent to servers
- ✅ No analytics tracking
- ✅ No account required
- ✅ No personal data collection
- ✅ 100% private and local

---

## ⚙️ Calculation Methods

### BMI Calculation
```
BMI = (Weight in kg) / (Height in cm)² × 10,000

Example:
- Weight: 85 kg
- Height: 180 cm
- BMI = 85 / (180)² × 10,000
- BMI = 85 / 32,400 × 10,000
- BMI = 26.2 (Overweight)
```

### Daily Calorie Target

#### For Weight Loss
```
Base BMI Calories:
- BMI < 18.5: 2,000 cal
- BMI 18.5-25: 2,200 cal
- BMI 25-30: 2,400 cal
- BMI > 30: 2,600 cal

Weekly Deficit Needed:
- Total kg to lose × 7,700 / (months × 4.3 weeks)

Daily Target:
= Base Calories - Weekly Deficit / 7
Minimum: 1,200 calories
```

#### For Muscle Gain
```
Base BMI Calories:
- Calculate same as weight loss

Adjust:
- Add 500 calories
- Results in ~0.5 kg gain/week (mostly muscle with training)
```

#### For Muscle Endurance
```
Base BMI Calories:
- Calculate same as weight loss
- No adjustment (maintenance)
- Focus on consistent moderate exercise
```

---

## 🎯 Fitness Goals Explained

### Weight Loss ⚡
**Best for:** Reducing body fat, belly fat, overall weight loss

**Recommended foods:**
- Grilled chicken breast
- Fish and salmon
- Vegetables and greens
- Eggs and egg whites
- Greek yogurt (low-fat)

**Recommended exercises:**
- Jumping jacks
- High knees
- Burpees
- Running
- Jump rope
- Mountain climbers
- Swimming

**Calorie approach:** Deficit (eat less than target)

**Timeline:** 3-6 months

---

### Muscle Gain 💪
**Best for:** Building muscle mass, strength training, bulking

**Recommended foods:**
- Chicken breast (150g portions)
- Ground beef
- Salmon and fish
- Whole eggs
- Protein shakes
- Rice and pasta
- Peanut butter
- Nuts and seeds

**Recommended exercises:**
- Push-ups
- Bench press
- Squats
- Deadlifts
- Pull-ups
- Rows
- Shoulder press
- Leg press

**Calorie approach:** Surplus (eat more than target)

**Timeline:** 3-6 months for noticeable gains

---

### Muscle Endurance 🏃
**Best for:** Toning, stamina improvement, balanced fitness

**Recommended foods:**
- Lean turkey
- White fish
- Eggs and egg whites
- Quinoa and lentils
- Low-fat dairy
- Vegetables

**Recommended exercises:**
- Circuit training
- HIIT
- Yoga
- Pilates
- Boxing
- Kettlebell training
- Calisthenics

**Calorie approach:** Maintenance (eat at target)

**Timeline:** 8-12 weeks for noticeable results

---

## 🔄 Workflow Examples

### Complete Daily Workflow

**Morning:**
1. Open FitFlow
2. Log breakfast → Click Menu → Choose "Greek Yogurt"
3. Eat snack → Add "Apple" manually
4. Log morning weight
5. Check remaining calories

**Midday:**
6. Log lunch → Click Menu → Choose "Grilled Chicken Breast"
7. Check stats
8. Plan afternoon meal

**Evening:**
9. Log dinner → Manual or menu
10. Log workout → Click Menu → Choose "Running"
11. Check summary pie chart
12. Review daily stats

**Before bed:**
13. Check motivation message
14. Plan next day

### Analytics Review Workflow

**Weekly:**
1. Open Analytics tab
2. Check 30-day calorie trend
3. See if trending down (deficit) or up (surplus)
4. Review weight chart
5. Check GitHub contribution graph for consistency

**Monthly:**
1. Review full monthly progress
2. Calculate average daily calories
3. See total workouts completed
4. Days tracked consistency
5. Adjust goals if needed

---

## 💡 Pro Usage Tips

### Maximizing Accuracy
1. Weigh food when possible
2. Use food labels
3. Log within 30 minutes of eating
4. Be consistent with portions
5. Google calorie estimates when unsure

### Staying Consistent
1. Log immediately (don't delay)
2. Set daily reminder
3. Use quick menu to save time
4. Review progress weekly
5. Adjust goals if too strict

### Interpreting Data
1. Look at trends, not daily fluctuations
2. Weight varies 1-2 kg daily (normal)
3. Consistency matters more than perfection
4. Track at least 2 weeks to see patterns
5. Give changes 4 weeks minimum to see results

---

## ⚠️ Important Disclaimers

### Medical Disclaimer
- FitFlow is NOT medical advice
- Consult doctor before major changes
- Don't go below 1,200 cal/day
- Listen to your body
- Stop if feeling unwell

### Accuracy Notes
- Calorie estimates are approximate
- Individual needs vary
- Metabolism differs per person
- Exercise burns vary by fitness level
- These are estimates, not absolutes

### Data Safety
- Always backup important data
- Don't clear browser cache
- Use same browser/device
- Be aware localStorage can be cleared
- No automatic cloud backup

---

## 🚀 Feature Roadmap

### Coming Soon
- Macro tracking (proteins, carbs, fats)
- Weekly meal planning
- Workout routine templates
- Data export to CSV
- Multi-language support
- Dark/Light theme toggle

### Being Considered
- Mobile app
- Cloud sync (optional)
- Social sharing
- Community challenges
- Advanced analytics
- Smart recommendations

---

## 📞 Support

For detailed questions about features:
1. Check this documentation
2. Read QUICKSTART.md
3. Review README.md
4. Check in-app help (Nutrition Info)
5. Create issue on GitHub

---

**Last Updated:** February 2026  
**Version:** 2.0  
**Status:** ✅ Complete & Functional

Enjoy using FitFlow! 🎉