# 🚀 Artifical Intelligence / Machine Learning Roadmap +  Quest Tracker

> A comprehensive, gamified progress tracking system for aspiring ML Engineers preparing for MAANG (Meta, Amazon, Apple, Netflix, Google) internships and full-time positions.

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/SangamDeveLoper)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Live Demo](#live-demo)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Learning Paths](#learning-paths)
- [How It Works](#how-it-works)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Overview

**MAANG Internship Quest Tracker** is a beautifully designed, fully client-side web application that helps aspiring ML Engineers systematically prepare for technical interviews at top tech companies. Built by Sangam, this tracker provides structured learning paths across three critical domains:

- **Data Structures & Algorithms (DSA)**: 10 comprehensive levels covering arrays, strings, trees, graphs, and more
- **Machine Learning Engineering**: 9 core domains from fundamentals to deployment
- **ML System Design**: 10 essential topics for building production-ready ML systems

### Key Highlights

- ✨ **Beautiful UI**: Modern, dark-themed interface with gradient animations
- 🎮 **Gamified Experience**: Progress tracking with visual rewards and achievements
- ⏱️ **Customizable Timer**: Set your own learning pace with flexible countdown timers
- 💾 **Local Data Persistence**: All progress saved locally using SQL.js and localStorage
- 👤 **Multi-User Support**: Create accounts and track individual progress
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🔒 **Privacy-First**: No server required, all data stays on your device

## ✨ Features

### Authentication System
- **User Registration**: Create personalized accounts with username/password
- **Secure Login**: Client-side authentication with encrypted storage
- **Session Management**: Persistent login across browser sessions
- **User Profiles**: Track individual progress per user

### Progress Tracking
- **Task Checkboxes**: Mark individual topics as complete
- **Visual Progress Bars**: Real-time percentage tracking for each domain
- **Circular Progress Rings**: Beautiful animated progress indicators on portal cards
- **Overall Statistics**: Combined progress across all three learning paths

### Timer System
- **Customizable Countdown**: Set your target completion date (1-3650 days)
- **Real-Time Updates**: Live countdown showing days, hours, minutes, seconds
- **Timer Reset**: Adjust your timeline when needed
- **Expiration Handling**: Graceful handling when timer expires

### Learning Portals

#### 🔴 DSA Portal (Data Structures & Algorithms)
10 comprehensive levels with categorized topics:
- **Level 1: Arrays** - Prefix Sum, Sliding Window, Two Pointers, Hashing, Kadane/DP, Sorting, Matrix, Greedy, Monotonic Stack, In-place Manipulation
- **Level 2: Strings** - Basic Manipulation, Two Pointers, Sliding Window, Hashing, Palindromes, Stack/Parentheses, DP, Trie, Encoding
- **Level 3: Linked Lists** - Basic Operations, Reversal Patterns, Fast & Slow Pointers, Merging, Intersection, Circular Lists, Design Patterns
- **Level 4: Stack & Queue** - Basic Operations, Monotonic Stack, Queue/Deque, Expression Parsing, Advanced Design
- **Level 5: Recursion & Backtracking** - Basic Recursion, Permutations, Matrix Backtracking, Decision Making, Advanced Patterns
- **Level 6: Binary Tree & BST** - Traversals, Properties, BST Operations, Path & Sum, Transformations, Advanced Patterns
- **Level 7: Graphs** - Basic Traversals, Shortest Path, Topological Sort, Union-Find, Advanced Patterns, Maze Problems
- **Level 8: Heap** - Basic Operations, Top K Patterns, Scheduling, Advanced Patterns
- **Level 9: Dynamic Programming** - 1D DP, 2D DP/Grid, Subset/Knapsack, State DP, Sequence/Interval, Miscellaneous
- **Level 10: Bit Manipulation & Math** - Basic Bit Operations, Bit Tricks, Math/Number Theory, Advanced Math

**Total Topics**: 300+ carefully curated problems

#### 🟢 ML Engineering Portal
9 core domains covering the complete ML engineering journey:
- **Programming & Software Engineering** - Python, DSA, Git, Unix, Best Practices
- **Mathematics & Statistics** - Linear Algebra, Calculus, Probability, Optimization
- **Data Handling & Preprocessing** - Cleaning, Feature Engineering, Dimensionality Reduction, Pipelines
- **Machine Learning Fundamentals** - Regression, Classification, Clustering, Ensemble Methods
- **Model Evaluation & Validation** - Bias-Variance, Cross-Validation, Metrics, Error Analysis
- **Deep Learning** - Neural Networks, CNNs, RNNs, Transformers, Transfer Learning
- **Frameworks & Tools** - PyTorch, TensorFlow, scikit-learn, pandas, numpy
- **Deployment / MLOps** - Docker, REST APIs, Model Serving, CI/CD, Cloud Platforms
- **Advanced / Optional** - Reinforcement Learning, GANs, AutoML, Explainability, Ethics

**Total Topics**: 50+ essential ML concepts

#### 🟣 ML System Design Portal
10 essential topics for production ML systems:
- **Core Foundations** - Programming, DSA, Networking, Databases
- **ML Fundamentals** - Supervised/Unsupervised Learning, Deep Learning, Metrics
- **ML Lifecycle** - Data Ingestion, Preprocessing, Training, Deployment, Monitoring
- **Model Deployment** - REST/gRPC APIs, Batch vs Real-time, Docker, Kubernetes
- **Feature Engineering & Storage** - Feature Stores, Data Versioning, Real-time Features
- **Scalability & Reliability** - Load Balancing, Caching, Distributed Training, High Availability
- **Monitoring & Observability** - Model Drift, A/B Testing, Metrics, Data Quality
- **Advanced Topics** - Real-time Streaming, Recommendation Systems, Large-scale NLP/CV
- **Cloud & MLOps** - AWS/GCP/Azure, CI/CD, Auto-retraining, Infrastructure as Code
- **System Design Practice** - Netflix, Amazon, Google, Instagram, Uber, LinkedIn, YouTube systems

**Total Topics**: 70+ system design concepts

### Reward System
- **Ultimate Reward**: Unlock special achievement when all portals reach 100%
- **Visual Celebration**: Animated modal with congratulatory message
- **Persistent State**: Reward claim status saved permanently
- **Motivational Design**: Beautiful golden gradient theme

### Home Dashboard
- **Overview Cards**: Quick view of main DSA and ML tasks
- **Portal Navigation**: Easy access to all three specialized portals
- **Progress Visualization**: Circular progress rings showing completion percentage
- **Countdown Timer**: Prominent display of time remaining
- **User Info**: Display current user with logout option

## 🎬 Live Demo

Open `index.html` in your browser to start using the application immediately!

## 📸 Screenshots

### Home Dashboard
Beautiful main interface with task overview, countdown timer, and portal cards

### DSA Portal
10 levels of comprehensive data structures and algorithms practice

### ML Engineering Portal
Structured learning path from fundamentals to advanced ML topics

### System Design Portal
Production-ready ML system design concepts and practice problems

## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or backend required!

### Quick Start

1. **Clone the Repository**
```bash
git clone https://github.com/SangamDeveLoper/MAANG-Internship-Quest-Tracker.git
cd MAANG-Internship-Quest-Tracker
```

2. **Open in Browser**
```bash
# Simply open index.html in your browser
# On Mac:
open index.html

# On Windows:
start index.html

# On Linux:
xdg-open index.html
```

3. **Start Tracking**
- Create an account with username and password
- Set your target completion date
- Start checking off topics as you learn!

### Alternative: Direct Download
1. Download the repository as ZIP
2. Extract to your desired location
3. Open `index.html` in any modern browser

## 💻 Usage

### First Time Setup

1. **Create Account**
   - Click "Sign Up" on the authentication modal
   - Enter username (min 3 characters)
   - Enter password (min 6 characters)
   - Click "Create Account"

2. **Set Timer**
   - Enter number of days for completion (1-3650)
   - Default is 365 days (1 year)
   - Click "Set Timer"

3. **Start Learning**
   - Navigate to any of the three portals
   - Check off topics as you complete them
   - Watch your progress grow!

### Using the Portals

#### DSA Portal
1. Navigate through 10 levels of increasing difficulty
2. Each level contains multiple categories
3. Check off problems as you solve them
4. Track category and level progress

#### ML Engineering Portal
1. Go through 9 core domains systematically
2. Each domain contains curated topics
3. Mark topics complete as you master them
4. Monitor overall ML progress

#### System Design Portal
1. Study 10 essential system design areas
2. Each section focuses on production concepts
3. Complete topics to build expertise
4. Track system design proficiency

### Managing Progress

**View Progress**
- Home dashboard shows overall completion
- Each portal displays its own progress
- Circular progress rings update in real-time
- Progress bars show percentage complete

**Edit Timer**
- Timer can be reset when expired
- Set new target dates as needed
- Timer continues counting down

**Switch Users**
- Logout from current account
- Login with different credentials
- Each user has independent progress

### Data Persistence

All your data is stored locally:
- **SQL.js Database**: Stores user accounts and progress
- **localStorage**: Backup storage for progress data
- **No Server Required**: Everything runs in browser
- **Privacy Protected**: Your data never leaves your device

## 📁 Project Structure

```
MAANG-Internship-Quest-Tracker/
│
├── index.html              # Main dashboard & home page
├── index2.html             # ML Engineering Portal
├── index3.html             # DSA Portal  
├── system-design.html      # ML System Design Portal
├── auth.html              # Legacy authentication page (redirects to index.html)
│
├── README.md              # Project documentation


Note: All CSS and JavaScript are embedded within HTML files for portability
```

### File Descriptions

**index.html** - Main Entry Point
- Authentication modal (login/signup)
- Timer setup and countdown
- Home dashboard with task overview
- Portal navigation cards with progress rings
- Ultimate reward section
- User management (logout)

**index2.html** - ML Engineering Portal
- 9 core ML domains
- 50+ curated topics
- Progress tracking per section
- User authentication check
- Real-time progress updates

**index3.html** - DSA Portal
- 10 levels of DSA mastery
- 300+ categorized problems
- Level and category progress
- Interactive checkboxes
- Sound effects on completion

**system-design.html** - System Design Portal
- 10 essential system design topics
- Production ML concepts
- Practice problem sets
- Architecture patterns
- Scalability and reliability focus

**auth.html** - Legacy Page
- Redirects to main index.html
- Kept for backward compatibility

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations
  - CSS Grid & Flexbox for layouts
  - CSS Variables for theming
  - Gradient animations
  - Backdrop filters for glassmorphism
  - Responsive design with media queries
- **JavaScript (ES6+)**: Client-side logic
  - Async/await for database operations
  - Event-driven architecture
  - LocalStorage API
  - Custom events for cross-page communication

### Data Storage
- **SQL.js (v1.8.0)**: SQLite compiled to WebAssembly
  - User authentication tables
  - Progress tracking tables
  - Foreign key relationships
  - Transactional consistency
- **localStorage**: Backup persistence layer
  - Progress data serialization
  - Cross-tab synchronization
  - User session management

### Libraries & CDN
- **sql.js**: SQLite in the browser via CDN
  ```
  https://cdnjs.cloudflare.com/ajax/libs/sql.js/1.8.0/sql-wasm.js
  ```

### Design System
- **Color Palette**:
  - Primary Red: `#ff4655`
  - Primary Green: `#53e88b`
  - Primary Purple: `#8b5cf6`
  - Background: `#0f1419`
  - Secondary: `#1a1f2e`
- **Typography**: Inter, System Fonts
- **Icons**: Custom SVG icons
- **Animations**: CSS keyframe animations

## 📚 Learning Paths

### Recommended Study Order

#### For Software Engineers → ML Engineers
1. **Start with DSA Portal** (Levels 1-5)
   - Build strong algorithmic foundation
   - Complete 150+ essential problems
2. **Begin ML Engineering Portal** (First 5 domains)
   - Learn ML fundamentals
   - Study mathematics and statistics
3. **Continue DSA Portal** (Levels 6-10)
   - Advanced data structures
   - Complex algorithms
4. **Complete ML Engineering Portal**
   - Deep learning and deployment
   - MLOps and advanced topics
5. **Finish with System Design Portal**
   - Production ML systems
   - Scalability patterns

#### For ML Practitioners → Software Engineers
1. **Start with ML Engineering Portal**
   - Formalize ML knowledge
   - Learn software engineering practices
2. **Begin DSA Portal** (Levels 1-3)
   - Core data structures
   - Basic algorithms
3. **Study System Design Portal**
   - ML system architecture
   - Production deployment
4. **Complete DSA Portal** (Levels 4-10)
   - Advanced topics
   - Interview preparation

### Time Estimates

**Aggressive Track**: 6 months (20+ hours/week)
- DSA: 2.5 months
- ML Engineering: 2 months
- System Design: 1.5 months

**Standard Track**: 12 months (10-15 hours/week)
- DSA: 5 months
- ML Engineering: 4 months
- System Design: 3 months

**Comfortable Track**: 18-24 months (5-10 hours/week)
- DSA: 8-10 months
- ML Engineering: 6-8 months
- System Design: 4-6 months

## 🔧 How It Works

### Database Schema

**users Table**
```sql
CREATE TABLE users (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  username TEXT UNIQUE NOT NULL,
  password TEXT NOT NULL,
  created_at INTEGER NOT NULL,
  timer_end INTEGER DEFAULT 0,
  custom_timer_days INTEGER DEFAULT 0
);
```

**progress Table**
```sql
CREATE TABLE progress (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  user_id INTEGER NOT NULL,
  task_id TEXT NOT NULL,
  completed INTEGER DEFAULT 0,
  FOREIGN KEY (user_id) REFERENCES users(id),
  UNIQUE(user_id, task_id)
);
```

### Data Flow

1. **User Authentication**
   - User credentials stored in SQL.js database
   - Session maintained in localStorage
   - Passwords stored (consider hashing for production)

2. **Progress Tracking**
   - Each checkbox maps to task_id in database
   - User actions trigger database updates
   - Changes synchronized across all pages

3. **Cross-Page Communication**
   - Custom events for progress updates
   - localStorage events for synchronization
   - Real-time updates without page refresh

4. **Data Persistence**
   - SQL.js database exported to array buffer
   - Buffer serialized to localStorage
   - Database reconstructed on page load

### Key JavaScript Functions

**Database Management**
- `initDatabase()`: Initialize SQL.js instance
- `createTables()`: Set up database schema
- `saveDatabase()`: Persist to localStorage

**User Management**
- `showMainApp()`: Display authenticated interface
- `loadUserProgress()`: Fetch user's completed tasks
- `saveTaskProgress()`: Update task completion status

**Progress Tracking**
- `updateProgress()`: Calculate and display progress
- `updateHomeTaskProgress()`: Sync home page tasks
- `updateCountdown()`: Timer countdown logic

## 🗺️ Roadmap

### Planned Features

- [ ] **Export Progress**: Download progress as JSON/CSV
- [ ] **Import Progress**: Restore from backup file
- [ ] **Dark/Light Theme Toggle**: User preference for themes
- [ ] **Study Streak Tracker**: Daily check-in system
- [ ] **Notes System**: Add personal notes to each topic
- [ ] **Resource Links**: Curated learning resources per topic
- [ ] **Practice Problem Integration**: Links to LeetCode, HackerRank
- [ ] **Pomodoro Timer**: Built-in study timer
- [ ] **Analytics Dashboard**: Detailed progress charts and insights
- [ ] **Mobile App**: React Native version
- [ ] **Collaboration Mode**: Share progress with study partners
- [ ] **Achievement Badges**: Unlock badges for milestones
- [ ] **Weekly Goals**: Set and track weekly objectives

### Future Enhancements

- **Backend Integration** (Optional)
  - Cloud sync across devices
  - Real-time collaboration
  - Progress sharing
- **AI Assistant**
  - Personalized study recommendations
  - Problem difficulty suggestions
  - Learning path optimization
- **Interview Simulator**
  - Mock interview questions
  - Video interview practice
  - Behavioral question prep
- **Company-Specific Tracks**
  - Google interview prep
  - Meta interview prep
  - Amazon interview prep

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Getting Started

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Make your changes
4. Test thoroughly
5. Commit your changes
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
6. Push to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
7. Open a Pull Request

### Contribution Guidelines

**Code Style**
- Use consistent indentation (2 spaces)
- Write descriptive variable names
- Comment complex logic
- Follow existing code patterns

**Adding New Topics**
- Research thoroughly
- Provide accurate descriptions
- Match existing difficulty levels
- Test checkbox functionality

**Bug Reports**
- Describe the issue clearly
- Include steps to reproduce
- Mention browser and OS
- Provide screenshots if applicable

**Feature Requests**
- Explain the use case
- Describe expected behavior
- Consider implementation complexity
- Discuss with maintainers first

### Areas for Contribution

- 📝 **Documentation**: Improve README, add guides
- 🐛 **Bug Fixes**: Find and fix issues
- ✨ **Features**: Implement new functionality
- 🎨 **Design**: UI/UX improvements
- 🌍 **Internationalization**: Add language support
- 📊 **Content**: Add more learning topics
- 🧪 **Testing**: Add test coverage

## 📄 License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2025 Sangam Developer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📞 Contact = +977 9762109738

**Project Creator**: Sangam Developer

- **GitHub**: [@SangamDeveLoper](https://github.com/SangamDeveLoper)
- **Project Repository**: [MAANG-Internship-Quest-Tracker](https://github.com/SangamDeveLoper/Artificial-Intelligence-Machine-Learning----Full-Roadmap)
- Email = gautamsangam500@gmail.com

### Support

If you encounter any issues or have questions:

1. **Check Documentation**: Review this README thoroughly
2. **Search Issues**: Look for similar problems in GitHub Issues
3. **Open New Issue**: Create detailed bug report or feature request
4. **Discussions**: Start a discussion for general questions

## 🙏 Acknowledgments

### Inspiration
- **NeetCode**: For comprehensive DSA problem sets
- **Take U Forward**: For structured DSA learning path
- **Cracking the Coding Interview**: By Gayle Laakmann McDowell
- **MAANG Interview Prep Communities**: For shared knowledge

### Technologies
- **SQL.js Team**: For amazing SQLite in browser
- **Modern Web Standards**: For powerful browser APIs
- **Open Source Community**: For continuous learning

### Learning Resources
- LeetCode, HackerRank, Codeforces for practice
- Coursera, edX for ML fundamentals
- System Design Primer for architecture concepts

## 📈 Project Stats

- **Total Learning Topics**: 420+
- **Portals**: 3 specialized tracks
- **Lines of Code**: ~3,500+
- **Development Time**: Built with passion
- **Users Helped**: Growing every day!

## 💡 Tips for Success

### Study Strategies

1. **Consistency Over Intensity**
   - Study daily, even if just 30 minutes
   - Review completed topics weekly
   - Take breaks to avoid burnout

2. **Active Learning**
   - Don't just read, implement
   - Explain concepts to others
   - Teach what you learn

3. **Spaced Repetition**
   - Review topics after 1 day, 1 week, 1 month
   - Use the timer to pace yourself
   - Revisit challenging topics

4. **Practice, Practice, Practice**
   - Solve variations of problems
   - Time yourself during practice
   - Simulate interview conditions

5. **Build Projects**
   - Apply ML concepts to real problems
   - Deploy projects to production
   - Share your work on GitHub

### Interview Preparation

- **Mock Interviews**: Practice with peers
- **System Design**: Draw diagrams, explain tradeoffs
- **Behavioral Questions**: Prepare STAR stories
- **Company Research**: Understand company tech stacks
- **Stay Updated**: Follow ML/tech blogs and papers

---

<div align="center">

**🎯 Your MAANG Journey Starts Here! 🚀**

Made with ❤️ by Sangam Developer

⭐ **Star this repository if you find it helpful!** ⭐



**Happy Learning! 📚 Good Luck with Your Interviews! 🍀**

</div>
