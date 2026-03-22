"# Agentic AI Course Landing Page

A professional, modern landing page for an AI & Agentic AI tools course built for YTL Courses platform. Features a sleek dark design with red accents, comprehensive course information, and interactive elements.

## 🎯 Features

### ✨ User Interface
- **Professional Dark Theme** - Inspired by ytlcourses.in design
- **YTL Courses Branding** - Consistent branding with logo integration
- **Responsive Design** - Fully mobile-optimized layout
- **Glass-morphism Effects** - Modern UI with backdrop blur effects
- **Smooth Animations** - Professional transitions and hover effects

### 📚 Course Information
- **8 Comprehensive Modules** covering:
  - n8n - Workflow Automation
  - Emergent AI - Agent Platform
  - Replit - Collaborative Development
  - LangGraph - Agent Orchestration
  - CrewAI - Multi-Agent Teams
  - Claude - Advanced AI Integration
  - GitHub Copilot - AI Code Assistant
  - AutoGen - Multi-Agent Framework

### 🎨 Interactive Elements
- **Live Countdown Timer** to May 20, 2026
- **Stats Section** showcasing platform credibility
- **FAQ Accordion** with common questions
- **Chatbot Interface** (mock - ready for Claude Sonnet integration)
- **Video Preview** placeholder
- **Instructor Bio** section

## 💰 Pricing
**₹499** for 8 hours of comprehensive content

## 🛠️ Tech Stack

### Frontend
- React 19
- Shadcn/UI Components
- Tailwind CSS
- Lucide React Icons
- React Router DOM

### Backend (Ready for Integration)
- FastAPI
- Python 3.x
- Motor (MongoDB async driver)

### Database
- MongoDB

### Planned Integrations
- Claude Sonnet (Anthropic) for AI chatbot
- Razorpay for payments

## 📁 Project Structure

```
/app
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/              # Shadcn components
│   │   │   ├── CountdownTimer.jsx
│   │   │   └── Chatbot.jsx
│   │   ├── CourseLanding.jsx    # Main landing page
│   │   ├── CourseLanding.css    # Styles
│   │   ├── mockData.js          # Course data
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── tailwind.config.js
├── backend/
│   ├── server.py                # FastAPI server
│   ├── requirements.txt
│   └── .env
└── memory/
    └── PRD.md                   # Product requirements
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and Yarn
- Python 3.9+
- MongoDB

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/devangdhyani/emergent-ai-.git
cd emergent-ai-
```

2. **Install Frontend Dependencies**
```bash
cd frontend
yarn install
```

3. **Install Backend Dependencies**
```bash
cd ../backend
pip install -r requirements.txt
```

4. **Set up Environment Variables**

Create `.env` files:

**frontend/.env**
```
REACT_APP_BACKEND_URL=http://localhost:8001
```

**backend/.env**
```
MONGO_URL=mongodb://localhost:27017
DB_NAME=agentic_ai_course
```

5. **Run the Application**

**Frontend:**
```bash
cd frontend
yarn start
```

**Backend:**
```bash
cd backend
uvicorn server:app --reload --host 0.0.0.0 --port 8001
```

Visit `http://localhost:3000` to view the landing page.

## 🎨 Design Highlights

### Color Scheme
- **Primary**: #ef4444 (Red) - CTAs and accents
- **Background**: #0a0a0a (Dark Black)
- **Surface**: rgba(26, 26, 26, 0.6) with blur
- **Text**: White with varying opacity

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: 900 weight, tight letter spacing
- **Body**: 400-600 weight, comfortable line height

### Components Used
- Shadcn/UI: Accordion, Button, Card, Dialog
- Custom: CountdownTimer, Chatbot
- Lucide Icons throughout

## 📋 Current Status

### ✅ Completed
- Frontend with all UI components
- Mock data structure
- Responsive design
- Stats section
- FAQ accordion
- Countdown timer
- Chatbot UI (mock responses)

### 🚧 Pending
- Claude Sonnet API integration
- Backend chat endpoints
- MongoDB chat history
- Enrollment system
- Payment integration (Razorpay)
- Real video preview

## 🔮 Future Enhancements

### Priority 1
- AI-powered chatbot with Claude Sonnet
- Enrollment form with payment gateway
- Email notifications

### Priority 2
- Student testimonials
- Course progress tracking
- Real-time enrollment counter
- Video preview integration

### Priority 3
- Social media sharing
- Referral system
- Newsletter subscription
- WhatsApp support integration

## 👨‍💻 Author

**Devang Dhyani**
- AI/ML Engineer
- Focused on agentic field and interactive tools

## 📄 License

This project is proprietary and belongs to YTL Courses.

## 🤝 Contributing

This is a private project for YTL Courses. For any questions or contributions, please contact the project owner.

## 📞 Support

For course inquiries: [ytlcourses.in](https://ytlcourses.in)

---

Built with ❤️ using Emergent AI Platform
"
