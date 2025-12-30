# 🎓 Ultimate Study Hub - Student Edition

A comprehensive, feature-rich web application designed to be the ultimate study companion for students. This all-in-one study hub helps students organize their learning, track progress, manage time, and achieve academic goals.

## ✨ Features

### 📚 **Subject Management**
- Add and organize multiple subjects
- Track progress per subject with visual indicators
- Color-coded subject organization
- Quick subject switching

### 📝 **Study Topics & Tasks**
- Create and manage study topics
- Priority levels (High, Medium, Low)
- Mark topics as completed
- Filter by status (All, Pending, Done)
- Progress tracking with statistics

### 🎯 **Flashcards System**
- Interactive flip flashcards
- Difficulty levels (Easy, Hard)
- Visual feedback and animations
- Perfect for memorization and review

### 📖 **Study Notes**
- Rich text editor for taking notes
- Auto-save functionality
- Character and word count
- Persistent storage per subject

### 🔗 **Learning Resources**
- Save and organize helpful links
- Categorize resources by subject
- Quick access to study materials
- URL validation

### ⏰ **Pomodoro Timer**
- Customizable study intervals
- Start, pause, and reset controls
- Boost productivity with time management

### 📅 **Calendar & Events**
- Monthly calendar view
- Add exams, targets, and deadlines
- Visual event indicators
- Date-based organization

### 📊 **Analytics Dashboard**
- Study streak tracking
- Topic completion statistics
- Weekly goal setting
- Subject performance metrics
- Study session timer
- Progress visualization

### 🎯 **Goal Management**
- Set and track personal goals
- Achievement monitoring
- Motivational progress tracking

### 🧮 **GPA Calculator**
- Calculate and track GPA
- Grade management
- Academic performance insights

### 🌓 **Modern UI/UX**
- Dark/Light theme toggle
- Responsive design for all devices
- Smooth animations and transitions
- Bootstrap-based modern interface
- Mobile-friendly layout

### 💾 **Data Management**
- Export data in multiple formats (JSON, CSV, TXT, PDF)
- Import/backup functionality
- Local storage persistence
- Search functionality

### 🔗 **External Integration**
- Quick access to RTU results
- External resource linking
- GPA calculation tools

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/red326/study-helper-exam.git
   ```

2. Navigate to the project directory:
   ```bash
   cd study-helper-exam
   ```

3. Open the application:
   - Simply open `index.html` in your web browser
   - Or use a local server for better experience:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

4. Access the application at `http://localhost:8000`

## 📱 Usage

### For Students
1. **Add Subjects**: Start by adding your current subjects
2. **Create Topics**: Break down each subject into manageable study topics
3. **Set Goals**: Define your study goals and targets
4. **Track Progress**: Use the analytics dashboard to monitor your progress
5. **Study Smart**: Use flashcards, notes, and Pomodoro timer for effective learning

### For Teachers
- Use as a template for student study planning
- Track multiple subjects and topics
- Demonstrate effective study techniques

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5.3.0
- **Icons**: Font Awesome 6.4.0
- **PDF Generation**: jsPDF 2.5.1
- **Storage**: Local Storage API
- **Design**: Responsive CSS Grid & Flexbox

## 📂 Project Structure

```
study-helper-exam/
├── index.html          # Main application file
├── README.md           # Project documentation
└── .git/              # Git repository
```

## 🎨 Key Features in Detail

### Study Analytics
- **Study Streak**: Tracks consecutive study days
- **Weekly Goals**: Set and monitor weekly study hour targets
- **Subject Performance**: Visual breakdown of progress by subject
- **Session Tracking**: Real-time study session timer

### Time Management
- **Pomodoro Technique**: Built-in timer for focused study sessions
- **Calendar Integration**: Track exams, deadlines, and important dates
- **Goal Setting**: Short-term and long-term goal management

### Learning Tools
- **Flashcards**: Interactive cards for memorization
- **Note Taking**: Rich text editor with auto-save
- **Resource Management**: Organize links and study materials
- **Progress Tracking**: Visual indicators for motivation

## 🔧 Customization

### Adding New Features
The application is built with modular JavaScript functions. To add new features:

1. Add HTML elements in the appropriate sections
2. Create corresponding JavaScript functions
3. Update the local storage schema if needed
4. Add styling to match the existing design

### Theme Customization
Modify CSS variables in the `<style>` section:
```css
:root {
    --bg: #f8f9fa;           /* Background color */
    --text: #212529;         /* Text color */
    --card: #fff;            /* Card background */
    --border: #dee2e6;       /* Border color */
    --accent: #7c3aed;       /* Accent color */
}
```

## 📊 Data Storage

The application uses browser's Local Storage to persist data:
- Subjects and topics
- Flashcards and notes
- Study sessions and progress
- Calendar events
- User preferences

Data is automatically saved and can be exported in multiple formats for backup.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
- Follow existing code style and patterns
- Test features thoroughly
- Update documentation as needed
- Ensure responsive design compatibility


## 📞 Support

If you encounter any issues or have suggestions:
1. Check existing issues in the repository
2. Create a new issue with detailed description
3. Include browser and OS information for bug reports

## 🔮 Future Enhancements

- [ ] Cloud synchronization
- [ ] Mobile app version
- [ ] Collaborative study features
- [ ] AI-powered study recommendations
- [ ] Integration with learning platforms
- [ ] Advanced analytics and reporting
- [ ] Study group management
- [ ] Exam preparation modes

---

**Made with ❤️ for students everywhere**

*Empowering students to study smarter, not harder*
