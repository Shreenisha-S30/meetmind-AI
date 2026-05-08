# MeetMind AI - AI-Powered Meeting Productivity Platform

A modern web application that combines real-time video meetings with AI-powered analytics to reduce unnecessary meetings and improve team productivity.

## 🚀 Features

### Core Functionality

- **Smart Authentication** - Login/signup with Google OAuth integration (demo mode available)
- **Video Meeting System** - Real-time video/audio with screen sharing (WebRTC placeholder)
- **AI Meeting Analyzer** - Analyzes meeting importance before scheduling
- **Automatic MOM Generation** - AI-generated Minutes of Meeting after each session
- **Participant Analytics** - Track engagement, speaking time, and participation
- **Admin Dashboard** - Team-wide analytics and productivity insights
- **Dark Mode** - Full dark/light theme support
- **Email Automation** - Automated MOM delivery to participants

### Key Features

1. **Meeting Scheduling with AI**
   - Define meeting title, agenda, and keywords
   - AI analyzes importance and suggests async alternatives
   - Estimates productivity cost
   - Provides smart recommendations

2. **Real-Time Video Meetings**
   - Host/join meetings
   - Mute/unmute controls
   - Camera on/off
   - Screen sharing
   - Live transcription
   - Meeting recording
   - Participant tiles with speaking indicators

3. **AI-Powered MOM**
   - Executive summary
   - Key decisions
   - Action items with assignees and deadlines
   - Meeting highlights
   - Pending tasks
   - Email distribution to all participants

4. **Analytics & Insights**
   - Participant engagement scores
   - Speaking time distribution
   - Attendance tracking
   - Meeting efficiency calculator
   - Productivity cost estimation
   - Team-wide trends

5. **Admin Panel**
   - Employee participation overview
   - Meeting frequency analysis
   - Unnecessary meeting detection
   - Time savings metrics
   - Efficiency trends

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS v4
- **Charts**: Recharts
- **Icons**: Lucide React
- **Notifications**: Sonner
- **UI Components**: Radix UI
- **Package Manager**: pnpm

## 📦 Installation

```bash
# Install dependencies
pnpm install

# Development server is already running in Figma Make
```

## 🎯 How to Use

### 1. Login
- Click any login button or use "Continue with Google"
- Demo credentials work automatically

### 2. Dashboard
- View meeting statistics and trends
- Check upcoming and recent meetings
- See efficiency scores and time saved

### 3. Schedule a Meeting
- Click "Schedule Meeting" in the sidebar
- Fill in meeting details (title, agenda, keywords)
- Add required and optional attendees
- Click "Analyze Meeting Importance with AI"
- Review AI suggestions
- Schedule or convert to async document

### 4. Join a Meeting
- Go to "My Meetings"
- Click "Join Meeting" on upcoming meetings
- Use video controls (mic, camera, screen share, record)
- View live transcript
- Click "End Call" when done

### 5. View MOM
- After a meeting ends, view automatically generated MOM
- Download as PDF or email to participants
- Review action items and decisions

### 6. Analytics
- Click "Analytics" to see participant details
- View speaking time distribution
- Check engagement scores
- Monitor participation trends

### 7. Admin Dashboard
- View team-wide meeting statistics
- Identify unnecessary meetings
- Track employee engagement
- See productivity trends

## 🎨 Features Highlights

- **AI Importance Analyzer**: Uses keywords like "urgent", "update", "planning" to classify meetings
- **Async Suggestions**: Identifies meetings that could be emails or documents
- **Efficiency Score**: Calculates meeting productivity based on participation and outcomes
- **Smart Notifications**: Alerts when meetings could be avoided
- **Productivity Cost**: Calculates person-hours spent in meetings
- **Time Saved Tracking**: Monitors time saved by avoiding unnecessary meetings

## 🔮 Future Enhancements (Post-Hackathon)

- Real Supabase integration for authentication and data persistence
- Actual WebRTC implementation for video calls
- OpenAI/Gemini API integration for real AI analysis
- Email SMTP integration for automated MOM delivery
- Calendar integration (Google Calendar, Outlook)
- Slack/Teams integration
- Recording storage and playback
- Advanced analytics and ML models
- Mobile app

## 📝 Demo Data

The application uses realistic mock data for demonstration:
- Pre-populated meetings with participants
- Sample analytics and charts
- Simulated AI analysis results
- Mock MOM generation
- Demo user profiles

## 🎓 Hackathon Ready

This project is designed for demo purposes and includes:
- ✅ Modern, professional UI
- ✅ Full dark mode support
- ✅ Responsive design
- ✅ Smooth animations
- ✅ Realistic mock data
- ✅ AI-powered features (simulated)
- ✅ Complete user flow
- ✅ Analytics and charts
- ✅ Admin capabilities

## 🚀 Deployment

This project is built in Figma Make and can be easily deployed to Vercel:

1. Export the project
2. Push to GitHub
3. Connect to Vercel
4. Deploy

## 📄 License

Built for hackathon demonstration purposes.

---

**MeetMind AI** - Making meetings matter, one AI analysis at a time. 🚀
