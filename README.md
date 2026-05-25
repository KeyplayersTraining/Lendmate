# LendMate VA Training Portal

A comprehensive, web-based Learning Management System (LMS) built for **LendMate** — a Canadian Mortgage Virtual Assistant agency. This portal centralizes training modules, quizzes, CRM walkthroughs, SOPs, progress tracking, and certificate generation into a single interactive platform.

🔗 **Live Demo:** `https://<your-username>.github.io/<repo-name>/`

---

## Features

### Dashboard & Navigation
- Role-based login (Trainee, Trainer, Admin)
- Real-time progress overview with completion stats
- Recent modules, upcoming quizzes, and activity feed
- Responsive sidebar navigation with mobile support

### Training Modules (15 Modules)
- Categorized by: CRM Systems, Compliance, Client Management, Workflow
- Embedded lesson content with step-by-step walkthroughs
- Progress tracking per module with mark-complete functionality
- Difficulty levels, estimated durations, and lesson counts

### Quiz System
- Multiple choice, True/False, and scenario-based questions
- Real questions for Filogix, Finmo, Compliance, Down Payment, and Workflow modules
- Auto-scoring with configurable pass thresholds
- Score history and attempt tracking

### CRM Training Hub
- Step-by-step tutorials for 5 Canadian mortgage platforms:
  - Filogix Expert · Finmo · Blu · Velocity · Hurricane (Paradigm)
- Platform-specific tips and navigation guides

### Certificates
- Auto-generated on quiz pass with LendMate branding
- Unique reference IDs, date stamps, and print-ready layout
- Pink/purple gradient design with decorative elements

### Gamification & Engagement
- Leaderboard with XP-based rankings
- Achievement badges (First Steps, Quiz Master, Speed Learner, etc.)
- Bookmarks and personal notes per module
- Activity log and notification system

### Admin Panel
- User management and role assignment
- Module and quiz management
- System analytics and reporting dashboard

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (single-page application) |
| Styling | CSS3 with custom properties |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — DM Sans, DM Serif Display, DM Mono |
| Hosting | GitHub Pages (static) |

No build tools, frameworks, or dependencies required.

---

## Quick Start

### Local Preview
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `index.html` in any modern browser — that's it.

### Deploy to GitHub Pages
1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Your portal will be live at `https://<your-username>.github.io/<repo-name>/` within a few minutes

---

## Project Structure

```
├── index.html      # Complete SPA (all CSS, HTML, JS inline)
├── README.md       # This file
├── LICENSE          # MIT License
└── .nojekyll       # Ensures GitHub Pages serves files without Jekyll processing
```

---

## Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Pink | `#C855A0` | Primary accent, buttons, highlights |
| Purple | `#8B5CF6` | Secondary accent, gradients |
| Dark BG | `#1a1a2e` | Sidebar, dark surfaces |
| Card BG | `#ffffff` | Content cards, modules |

---

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

Built with 💜 for **LendMate** · [lendmate.ca](https://lendmate.ca)
