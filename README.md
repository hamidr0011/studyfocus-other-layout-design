# StudyFocus 

A study tracking and productivity application designed to help students and learners organize their subjects, manage tasks, track study sessions, and visualize their progress over time.

---

## What is StudyFocus?

StudyFocus is a web-based study companion that helps you:

- **Stay organized** - Create subjects and categorize your study materials
- **Track progress** - Monitor daily study goals and weekly performance
- **Manage tasks** - Keep track of assignments, readings, and projects
- **Build habits** - Maintain study streaks and develop consistent routines
- **Analyze patterns** - Visualize your study time and identify focus areas

---

## Getting Started

### Running the Application

1. **Open the file directly in your browser:**
   Simply double-click `studyfocus.html` or right-click → Open with browser

2. **Or run a local server (optional):**
   ```bash
   python -m http.server 8080
   ```
   Then visit `http://localhost:8080/studyfocus.html`

No installation required. All data is stored locally in your browser.

---

## 📱 Features

### Focus Timer
Track your study sessions with an easy-to-use timer. Select a subject, start the timer, and focus on your work. The timer tracks your session duration and adds it to your daily progress automatically.

### Subject Management
Create subjects for each course or topic you're studying. Assign color tags to quickly identify different subjects. Add tasks to each subject to keep your work organized.

### Task Tracking
Manage your to-do list with tasks that can be marked as:
- **To Do** - Tasks you haven't started
- **In Progress** - Tasks you're currently working on
- **Done** - Completed tasks

Filter tasks by subject, status, or priority to stay organized.

### Daily Goals
Set a daily study target in minutes. Track your progress throughout the day with a visual progress bar. Adjust your goal anytime based on your schedule.

### Study Streak
Build consistent study habits with the streak tracker. The app tracks how many consecutive days you've studied and displays a visual streak calendar.

### Analytics & Insights
View detailed analytics about your study patterns:
- Total hours studied this week
- Most studied subject
- Tasks completed
- Weekly study time breakdown by subject
- Session history with dates and durations

---

##  Data Storage

StudyFocus stores all your data locally in your browser using localStorage. This means:

- No account required
- Works offline
-  Privacy-friendly (data never leaves your device)
-  Clear browser data will erase your progress

**To backup your data:** Export your browser's localStorage or use browser sync features.

---

## System Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Minimum 768px width recommended for desktop use
- Mobile-friendly responsive design

---

## Project Files

| File | Description |
|------|-------------|
| `studyfocus.html` | Main application file (single-file app) |
| `README.md` | This documentation file |

---

## Use Cases

**For Students:**
- Track study time for each course
- Manage assignment deadlines
- Build consistent study habits
- Prepare for exams with focused sessions

**For Professionals:**
- Track continuing education hours
- Manage certification study materials
- Balance multiple learning topics

**For Self-Learners:**
- Organize online course materials
- Track progress on tutorials and books
- Maintain learning streaks

---

## How to Use

### Creating a Subject
1. Click the "+" button in the Subjects page
2. Enter a name (e.g., "Mathematics")
3. Select a color tag
4. Click Add Subject

### Adding Tasks
1. Navigate to a subject or the Tasks page
2. Click the "+" button
3. Enter task title
4. Set priority (High, Medium, Low)
5. Set estimated time
6. Click Add Task

### Starting a Study Session
1. Go to the Dashboard
2. Select a subject from the dropdown
3. Click Start
4. Focus on your study material
5. Click Stop when finished

### Tracking Progress
- View your daily progress on the Dashboard
- Check weekly stats in Analytics
- Monitor your streak in the sidebar
- Review session history to see patterns

---

## Usability & Accessibility

StudyFocus follows established usability principles to ensure a great experience for all users:

### Core Principles Applied

| Principle | How It's Implemented |
|-----------|---------------------|
| **Visibility of System Status** | Timer shows clear status (ready, running, paused) with visual indicators and color coding |
| **User Control & Freedom** | Undo button for accidental deletions, confirmation before stopping timer, cancel options on all actions |
| **Error Prevention** | Confirmation dialogs for destructive actions, form validation with helpful messages, disabled states for invalid actions |
| **Recognition over Recall** | Clear icons, visible options, empty states with action buttons, consistent navigation |
| **Flexibility & Efficiency** | Keyboard shortcuts for power users, filters for quick task finding, default values to speed up input |
| **Aesthetic & Minimal Design** | Clean interface, progressive disclosure of advanced options, purposeful animations |
| **Help Users Recover** | Detailed error messages with recovery suggestions, undo functionality, auto-save protection |

### Accessibility Features

- **Keyboard Navigation** - Full app control without mouse (Tab, Enter, Escape, Space)
- **Screen Reader Support** - ARIA labels, status announcements, semantic HTML
- **High Contrast** - All text meets WCAG AA standards (4.5:1 contrast ratio minimum)
- **Reduced Motion** - Respects system preference for minimal animations
- **Focus Indicators** - Clear visual focus states for keyboard users

---

## Troubleshooting

**Data lost after clearing browser?**
Data is stored locally. Clearing browser data will remove your progress. Consider using browser sync or avoid clearing site data.

**Timer not working?**
Ensure JavaScript is enabled in your browser settings.

**Display looks wrong?**
Try refreshing the page or updating your browser to the latest version.

---

## License

MIT License - Feel free to use, modify, and distribute.

---

**Built for focused learning.**
