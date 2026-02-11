# 🎓 Peer Educator Training Cards

An interactive card game designed to train peer educators, tutors, and mentors through scenarios, learning science principles, deep reflection, and collaborative dialogue.

## 🎯 Purpose

This game creates a space for peer educators to:
- **Practice** responding to real tutoring scenarios
- **Learn** evidence-based principles from cognitive science and pedagogy
- **Reflect** on their own teaching practices and biases
- **Engage** in deep dialogue with fellow educators
- **Build** a community of practice around effective teaching

Inspired by games like Cards Against Humanity, but designed to build skills, not just laughs (though humor is included!).

## 🧠 Pedagogical Foundation

This game is grounded in:

1. **Jeff Anderson's Teaching Philosophy** (Foothill College)
   - Ungrading and student agency
   - Meta-learning as the foundation
   - Deep learning over shallow learning
   - The "2-minute rule" for questions
   - Flipped learning and active engagement
   - Deliberate practice and corrective feedback

2. **Learning Science Research**
   - Retrieval practice (testing effect)
   - Spaced repetition
   - Desirable difficulties
   - Metacognition
   - Growth mindset
   - Constructivism

3. **Peer Education Best Practices**
   - Socratic questioning
   - Scaffolding student thinking
   - Recognizing and addressing learned helplessness
   - Cultural responsiveness
   - Boundary-setting and self-care

## 📦 What's Included

### Four Card Decks (20 cards each):

1. **🎭 Real Scenarios** - Actual tutoring situations that challenge educators
   - The spiraling student who's been stuck for hours
   - The silent partner who won't engage
   - The overconfident expert who won't admit mistakes
   - The emotionally overwhelmed student in crisis

2. **🧠 Learning Principles** - Evidence-based pedagogy and cognitive science
   - The Testing Effect
   - Desirable Difficulties
   - The Curse of Knowledge
   - Metacognition
   - Growth vs. Fixed Mindset

3. **🪞 Deep Reflection** - Questions for self-awareness and growth
   - Your tutoring origin story
   - The student you avoid
   - Your limiting beliefs
   - The feedback you're afraid to hear

4. **⚡ Wild Cards** - Interactive challenges and exercises
   - The Socratic Speedrun
   - Terrible Tutor roleplay
   - The Empathy Experiment
   - Vulnerability dares

## 🎮 How to Play

### Setup
1. Open `index.html` in a web browser
2. Choose number of players (2-4 recommended)
3. Each player takes turns drawing cards

### Game Flow
1. **Draw a card** from any deck
2. **Read it aloud** to the group
3. **Start a 3-minute timer** for discussion
4. **Engage with the prompts** - think, discuss, debate
5. **Take notes** on insights and commitments
6. **Next player** draws a card

### Duration
- Quick session: 30-45 minutes (5-7 cards)
- Full session: 60-90 minutes (10-15 cards)
- Deep dive: 2+ hours (20+ cards)

## 🚀 Getting Started

### Option 1: Run Locally (Easiest)
```bash
# Clone or download this repo
git clone <repo-url>
cd peer-educator-cards

# Open in browser (no server needed!)
open index.html
# or just double-click index.html
```

### Option 2: Run on a Web Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve

# Then open: http://localhost:8000
```

### Option 3: Deploy Online
- Deploy to GitHub Pages, Netlify, or Vercel
- All files are static HTML/CSS/JavaScript
- No backend required!

## 📁 File Structure

```
peer-educator-cards/
├── index.html          # Main game interface
├── styles.css          # Visual styling
├── game.js            # Game logic and state management
├── cards-data.js      # All card content (80 cards total)
└── README.md          # This file
```

## ✨ Features

- **No installation required** - runs in any modern browser
- **Fully offline** - no internet needed after initial load
- **Mobile responsive** - works on phones and tablets
- **Note-taking system** - capture insights during play
- **Download notes** - export reflections as text file
- **Timer system** - structured 3-minute discussions
- **Session stats** - track cards explored and notes taken
- **Randomized draws** - never see the same card twice in a session

## 🎨 Customization

### Adding Your Own Cards

Edit `cards-data.js` and add cards to any deck:

```javascript
scenario: [
    {
        title: "Your Scenario Title",
        difficulty: "⭐⭐⭐",
        content: `Describe the situation here.
        
        Use multiple paragraphs for readability.`,
        prompts: [
            "Discussion question 1?",
            "Discussion question 2?",
            "Discussion question 3?"
        ]
    },
    // ... more cards
]
```

### Changing Visual Style

Edit `styles.css` to customize:
- Colors (CSS variables at top of file)
- Fonts
- Card layouts
- Button styles

### Modifying Game Rules

Edit `game.js` to change:
- Timer duration (default: 3 minutes)
- Number of players allowed
- How cards are selected/randomized

## 🧪 Use Cases

### Training Contexts
- **Peer tutor training programs** at universities
- **SI Leader development** (Supplemental Instruction)
- **Writing center tutor onboarding**
- **Graduate TA orientation**
- **Learning assistant programs**
- **Peer mentorship training**

### Workshop Formats
- **Icebreaker** - Start with Wild Cards to build community
- **Skill-building** - Focus on Scenarios and Principles
- **Reflection retreat** - Deep dive into Reflection deck
- **Ongoing PD** - 30-minute weekly sessions

### Facilitation Tips
1. **Set norms** - Create psychological safety before starting
2. **Model vulnerability** - Facilitator goes first on hard questions
3. **Honor silence** - Not everything needs to be answered immediately
4. **Capture themes** - Whiteboard recurring insights
5. **Close with gratitude** - End by appreciating each other's presence

## 🔬 Research Connections

This game implements research on effective professional development:

- **Active learning** over passive lecture (Freeman et al., 2014)
- **Peer learning** and communities of practice (Wenger, 1998)
- **Reflective practice** for teacher development (Schön, 1983)
- **Scenario-based learning** for skill transfer (Ericsson, 2008)
- **Metacognitive awareness** in teaching (Tanner, 2012)

## 📚 Recommended Reading

For facilitators and players who want to go deeper:

1. **Teaching & Learning**
   - *Small Teaching* by James Lang
   - *How Learning Works* by Ambrose et al.
   - *Make It Stick* by Brown, Roediger & McDaniel

2. **Peer Education**
   - *Training Peer Tutors* by McDonald & Gadberry
   - *The Learning Paradigm College* by Tagg

3. **Critical Pedagogy**
   - *Pedagogy of the Oppressed* by Paulo Freire
   - *For White Folks Who Teach in the Hood* by Christopher Emdin
   - *Punished by Rewards* by Alfie Kohn

4. **Jeff Anderson's Work**
   - Course syllabi at Foothill College
   - YouTube: @JeffAndersonMath
   - Blog: jeffandersonmath.wordpress.com

## 🤝 Contributing

Want to improve this game?

1. **Add cards** - Submit new scenarios, principles, or reflections
2. **Fix bugs** - Report issues or submit fixes
3. **Improve accessibility** - Suggest or implement a11y improvements
4. **Translate** - Help make this available in other languages
5. **Share stories** - How did you use this? What happened?

## 📝 License

This project is open source and available for educational use.

If you use this in your training program, I'd love to hear about it!

## 🙏 Acknowledgments

- **Jeff Anderson** - For 10+ years of pedagogical mentorship and the philosophical foundation
- **Foothill College** - For pioneering ungrading and meta-learning approaches
- **Peer educators everywhere** - Who do the hard, beautiful work of helping others learn

---

**"Give a person a fish, they eat for a day. Teach a person to fish and they eat for a lifetime."**

Built with care for the educators who care about learning.
