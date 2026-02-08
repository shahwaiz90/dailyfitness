# 🔥 FitFlow - Personal Calorie & Fitness Tracker

<div align="center">

![FitFlow](https://img.shields.io/badge/FitFlow-Personal%20Tracker-ff6b6b?style=flat-square&logo=fire)
![Version](https://img.shields.io/badge/Version-2.0-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Scope](https://img.shields.io/badge/Scope-Personal%20Use-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-NOT%20Production%20Ready-red?style=flat-square)

**A beautiful personal fitness companion - Track calories, log workouts, monitor progress locally!**

⚠️ **IMPORTANT:** Personal-use application only. [See critical limitations](#-critical-limitations)

[📖 Docs](#-features) • [✨ Features](#-features) • [🎯 How to Use](#-how-to-use) • [⚠️ Limitations](#-critical-limitations)

</div>

---

## ⚠️ **CRITICAL LIMITATIONS**

### ❌ **NOT Suitable For:**
- ❌ Multi-user environments
- ❌ Commercial applications  
- ❌ Enterprise deployments
- ❌ Production use at any scale
- ❌ Regulated industries (healthcare, finance)
- ❌ HIPAA/GDPR compliance needs
- ❌ Millions of users or any number of external users

### ✅ **Best Used For:**
- ✅ Personal fitness tracking (single user, your device)
- ✅ Individual self-improvement projects
- ✅ Learning/educational purposes
- ✅ Hobby projects
- ✅ MVP/proof of concept

### 🔐 **Security Architecture (Local Device Only):**
- Data stored in **unencrypted localStorage**
- **No user authentication** (anyone with browser access can view all data)
- **No data encryption** (vulnerable to XSS attacks)
- **No backup or recovery system**
- **No cross-device sync**
- **No GDPR/HIPAA compliance**
- **Single-user only** (not designed for multiple users)

---

## 🎯 What is FitFlow?

FitFlow is a **beautiful, free personal fitness tracker** built with pure HTML, CSS, and JavaScript. Perfect for individuals tracking their own fitness journey.

**Perfect for:** Individual fitness tracking! 💪  
**NOT for:** Multi-user, commercial, or regulated applications

---

## ⚠️ **IMPORTANT DISCLAIMER**

### For Personal Use Only
This application is **NOT production-ready** for commercial, multi-user, or regulated use. Designed exclusively for **personal single-user fitness tracking on your own device**.

### Security/Privacy Limitations
- ❌ Data NOT encrypted (plain text localStorage)
- ❌ No user authentication (anyone with browser access sees data)
- ❌ No backup system (clearing cache = permanent loss)
- ❌ Not HIPAA/GDPR compliant
- ❌ No cross-device sync
- ❌ Impossible to scale to millions of users

### Health Data Warning
- Your weight, fitness data stored unencrypted
- Not suitable for regulated health applications
- Not compliant with healthcare standards
- For personal use only

---

## ✨ Features

### 📊 Smart Tracking
- ✅ **Daily Calorie Tracking** - Log meals and exercise with one click
- ✅ **Predefined Menus** - Quick-add foods and exercises tailored to your goal
- ✅ **Smart Calorie Calculation** - Auto-calculates your daily target based on BMI and goals
- ✅ **Weight Logging** - Track weight changes over time
- ✅ **Real-time Stats** - See your net calories, remaining calories, and BMI instantly

### 🎨 Beautiful Visualizations
- ✅ **GitHub-Style Contribution Graph** - See your 52-week tracking consistency
- ✅ **Calorie Trend Charts** - 30-day line graph showing your progress
- ✅ **Weight Progress Charts** - Track weight loss/gain visually
- ✅ **Calorie Breakdown Pie Chart** - See consumed vs burned vs remaining
- ✅ **Dashboard Stats** - At-a-glance view of all your metrics

### 🎯 Fitness Goal Customization
Three personalized tracking modes:
1. **⚡ Weight Loss** - High-intensity exercises, low-calorie foods, aggressive deficit
2. **💪 Muscle Gain** - Strength training, calorie surplus, protein-focused meals
3. **🏃 Muscle Endurance** - Balanced exercises, toning meals, sustainable approach

### 🚀 Smart Features
- 🔐 **Local Data Storage** - Your data stays on YOUR device (no cloud tracking)
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- ⚡ **Lightning Fast** - Pure HTML/CSS/JS, zero dependencies needed
- 🌙 **Beautiful Dark Theme** - Gorgeous gradient UI with glass-morphism effects
- 💾 **Auto-Save** - Never lose your data
- 🔄 **Real-time Updates** - See changes instantly

### 📚 Educational Content
- 📖 **Nutrition Info Panel** - Learn about daily calorie intake recommendations
- 🎓 **Fitness Tips** - Weight loss, muscle gain, and calorie facts
- 📊 **Statistics** - Average daily calories, total workouts, days tracked

---

## 🚀 Live Demo

**[👉 Click here to open FitFlow](https://your-username.github.io/fitflow)**

*Replace `your-username` with your actual GitHub username*

---

## 🎯 How to Use

### 1️⃣ **Initial Setup** (Takes 2 minutes)
- Enter your name, current weight, height, and target weight
- Choose your timeline (how many months to reach your goal)
- Select your fitness goal (Weight Loss, Muscle Gain, or Endurance)
- Click "Start Tracking" 🚀

### 2️⃣ **Daily Tracking**
- **Log Food**: Click the Menu button or type your food name and calories
- **Log Exercise**: Add your workout with calories burned
- **Log Weight**: Update your weight once a day (optional but recommended)

### 3️⃣ **Monitor Progress**
- Check your stats dashboard for daily overview
- Use the Analytics tab to see 30-day trends
- Watch your GitHub-style contribution graph grow!

### 4️⃣ **Get Motivated**
- See your remaining calories for the day
- Track your weight progress with beautiful charts
- Celebrate daily achievements with the motivation card

---

## 📋 Installation

### Option 1: Deploy to GitHub Pages (Recommended)
1. **Fork this repository**
   ```bash
   Click "Fork" button in the top right
   ```

2. **Go to Settings → Pages**
   - Under "Source", select `main` branch
   - Click "Save"

3. **Your site will be live at:**
   ```
   https://your-username.github.io/fitflow
   ```

### Option 2: Run Locally
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/fitflow.git
   cd fitflow
   ```

2. **Open in your browser**
   ```bash
   # Simply double-click index.html or:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

### Option 3: Use Without Installation
Just download `index.html` and open it in any modern browser!

---

## 🏗️ Project Structure

```
fitflow/
├── index.html          # Complete app (HTML + CSS + JS)
├── README.md           # This file
└── .gitignore          # Git configuration
```

**That's it!** Just one HTML file with everything built-in. No build process, no dependencies, no Node modules!

---

## 💡 Key Concepts

### BMI Calculation
```
BMI = (Weight in kg / (Height in cm)²) × 10,000
```
- **Underweight:** BMI < 18.5
- **Normal:** BMI 18.5-24.9
- **Overweight:** BMI 25-29.9
- **Obese:** BMI ≥ 30

### Daily Calorie Target
Your target is calculated based on:
- Your BMI and fitness goal
- Weight loss required
- Timeline to reach goal
- Deficit of ~500 cal/day = ~0.5 kg/week loss

### Predefined Menus

#### 🏃 Weight Loss Exercises
- Jumping Jacks (8 cal/min)
- High Knees (12 cal/min)
- Burpees (10 cal/rep)
- Jump Rope (15 cal/min)
- Running (12 cal/min)
- Swimming (11 cal/min)
- And more...

#### 💪 Muscle Gain Exercises
- Push-ups (7 cal/set)
- Bench Press (8 cal/set)
- Squats (9 cal/set)
- Deadlifts (10 cal/set)
- Pull-ups (9 cal/set)
- And more...

#### 🥗 Diet Options
Pre-filled with healthy foods for each goal:
- Grilled Chicken Breast (165 cal)
- Baked Salmon (206 cal)
- Greek Yogurt (80 cal)
- Eggs, Rice, Vegetables...
- And many more!

---

## 📊 Data Storage

FitFlow uses **browser localStorage** - this means:
- ✅ Your data is stored locally on YOUR device
- ✅ No internet required to use the app
- ✅ Complete privacy - we never collect any data
- ✅ Data persists across browser sessions

**To clear your data:**
1. Go to Profile tab
2. Click "Reset Profile"
3. Or manually clear browser localStorage

---

## 🎨 Visual Features

### Dashboard Stats
- 🔥 **Net Calories** - Purple gradient card
- 🎯 **Remaining Calories** - Pink gradient card  
- ❤️ **BMI Status** - Green gradient card
- ⚖️ **Current Weight** - Blue gradient card

### Charts & Graphs
- **Doughnut Chart** - Daily calorie breakdown
- **Line Charts** - 30-day trends
- **Contribution Graph** - GitHub-style 52-week view

### Color Coding
- 🟠 **Orange** - Food/Diet
- 🔴 **Red** - Exercise/Burned
- 🟣 **Purple** - Overall/Net
- 🟢 **Green** - Weight/Health

---

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Glass-morphism, gradients, animations
- **Vanilla JavaScript** - No frameworks, pure JS
- **Chart.js** - Beautiful charts (via CDN)
- **Font Awesome** - Icons (via CDN)
- **localStorage API** - Data persistence

**Total Package:** Single HTML file, ~50KB uncompressed, **zero dependencies!**

---

## 📱 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ 90+ | Full support |
| Firefox | ✅ 88+ | Full support |
| Safari | ✅ 14+ | Full support |
| Edge | ✅ 90+ | Full support |
| Mobile Chrome | ✅ | Full support |
| Mobile Safari | ✅ | Full support |

**Minimum requirement:** Any modern browser with ES6 support (2016+)

---

## 🚀 Performance

- ⚡ **Ultra-fast** - No build process, no bundle, instant loading
- 📦 **Tiny** - Single HTML file (~50KB)
- 🔋 **Efficient** - localStorage for offline access
- 🎯 **Responsive** - Instant UI updates

---

## 🎓 Learning Resources

### About Fitness & Nutrition
- 📖 **Average Calorie Intake:**
  - Women: 1,600-2,400 cal/day
  - Men: 2,200-3,000 cal/day

- 🏃 **Weight Loss:**
  - 1 kg fat = 7,700 calories
  - Safe rate: 0.5-1 kg/week
  - Requires ~500 cal daily deficit

- 💪 **Muscle Gain:**
  - Requires +300-500 cal surplus
  - Protein: 1.6-2.2g per kg of body weight
  - Consistent strength training essential

- ⚖️ **Calorie Deficit:**
  - Largest factor in weight loss
  - Exercise + diet combined most effective
  - Consistency matters more than perfection

---

## 🤝 Contributing

Contributions are welcome! Here's how to help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Ideas for Contributions
- [ ] Add more exercises/foods to predefined menus
- [ ] Implement macro tracking (proteins, carbs, fats)
- [ ] Add meal planning features
- [ ] Export data to CSV/PDF
- [ ] Dark/Light theme toggle
- [ ] Multi-language support
- [ ] Workout routines library
- [ ] Social sharing features

---

## 📝 Future Roadmap

- 🔜 Macro tracking (proteins, carbs, fats)
- 🔜 Weekly meal plans
- 🔜 Workout routine templates
- 🔜 Export data functionality
- 🔜 Multiple language support
- 🔜 Cloud sync option (optional)
- 🔜 Mobile app version
- 🔜 Community challenges

---

## 🐛 Bug Reports & Feedback

Found a bug or have a feature request? 
- **Open an issue** on GitHub
- **Describe** the problem clearly
- **Include** screenshots if possible
- **Suggest** solutions if you have any

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

**TL;DR:** Use it, modify it, share it - do whatever you want with it! 🎉

---

## ⭐ Show Your Support

If FitFlow helped you achieve your fitness goals, please:
- ⭐ **Star this repository** - It helps others discover it!
- 🔗 **Share** with friends who need a fitness tracker
- 💬 **Leave feedback** - Your suggestions make it better
- 🐛 **Report bugs** - Help us improve

---

## 🙏 Credits & Acknowledgments

- **Chart.js** - For beautiful chart visualizations
- **Font Awesome** - For stunning icons
- **Community** - For amazing feedback and suggestions
- **You** - For using FitFlow on your fitness journey! 💪

---

## 📞 Get in Touch

- 📧 **Email:** [Create an issue for contact]
- 🐦 **Twitter:** [@YourHandle]
- 💼 **LinkedIn:** [Your Profile]
- 🌐 **Website:** [Your Website]

---

## 🎯 Success Stories

Share your FitFlow success story! If you've reached your fitness goals using FitFlow, we'd love to hear about it:

1. Create an issue titled "Success Story: [Your Name]"
2. Tell us your journey
3. Share your results
4. We'll feature you in the README! 🌟

---

## 📊 Stats

- 🎯 **Fitness Goals:** 3 (Weight Loss, Muscle Gain, Muscle Endurance)
- 🏃 **Predefined Exercises:** 30+
- 🥗 **Predefined Foods:** 36+
- 📱 **Mobile Optimized:** Yes
- ⚡ **Load Time:** < 1 second
- 💾 **Data Privacy:** 100% Local

---

## ⚠️ Disclaimer

**FitFlow is a tracking tool, not medical advice.** Please:
- Consult a doctor before starting any fitness program
- Don't use extreme calorie deficits (minimum 1,200 cal/day)
- Listen to your body
- Adjust goals based on how you feel
- Combine tracking with healthy habits

---

<div align="center">

### 🚀 Ready to Start Your Fitness Journey?

**[Launch FitFlow Now →](https://your-username.github.io/fitflow)**

**Made with ❤️ for fitness enthusiasts everywhere**

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=your-username.fitflow)

</div>

---

## 📚 Table of Contents

- [What is FitFlow?](#what-is-fitflow)
- [Features](#-features)
- [Live Demo](#-live-demo)
- [How to Use](#-how-to-use)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Key Concepts](#-key-concepts)
- [Data Storage](#-data-storage)
- [Visual Features](#-visual-features)
- [Technologies Used](#-technologies-used)
- [Browser Support](#-browser-support)
- [Performance](#-performance)
- [Contributing](#-contributing)
- [Future Roadmap](#-future-roadmap)
- [Bug Reports](#-bug-reports--feedback)
- [License](#-license)
- [Credits](#-credits--acknowledgments)

---

**Last Updated:** February 2026  
**Version:** 2.0.0  
**Status:** ✅ Active & Maintained