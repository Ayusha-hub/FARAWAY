# SignalX AI - Real-Time Safety Intelligence Platform

An AI-powered emergency and cyber safety platform built with Next.js 15, TypeScript, Tailwind CSS, and Firebase.

## 🚀 Features

### Day 1 Features
- **Real-Time Incident Reporting**: Report emergencies and safety incidents instantly
- **AI Risk Detection**: Advanced AI analyzes patterns to detect potential risks
- **Live Safety Map**: View real-time incidents and safety alerts in your area
- **Scam Detection**: Identify phishing attempts and scams with AI-powered detection
- **User Authentication**: Secure Firebase email/password authentication
- **Protected Dashboard**: Access control for authenticated users
- **Modern Dark UI**: Futuristic, responsive design with gradient effects

### Day 2 Features
- **Incident Management System**: Complete Firestore-based incident tracking
- **Live Incident Feed**: Real-time updates with Firestore listeners
- **Enhanced Dashboard**: Statistics cards with trends and live data
- **Report Incident Form**: Full-featured incident reporting with validation
- **Severity Classification**: Low, Medium, High severity levels with color coding
- **Category System**: Flood, Fire, Medical, Accident, Cyber Scam, Crime, Infrastructure
- **Toast Notifications**: Success/error feedback system
- **Reusable Components**: StatCard, IncidentCard, LoadingSpinner, EmptyState
- **Location Support**: GPS coordinates for incident reporting
- **Firestore Security Rules**: Proper data validation and access control

### Day 3 Features
- **Gemini AI Integration**: Google Gemini API for intelligent incident analysis
- **Automatic AI Processing**: AI analyzes incidents automatically after submission
- **AI Intelligence Dashboard**: Dedicated page for AI-generated insights
- **Threat Score Analysis**: 1-100 threat scoring with visual indicators
- **Emergency Level Classification**: Low, Moderate, High, Critical emergency levels
- **Safety Recommendations**: AI-generated safety advice for each incident
- **Fake Report Detection**: AI estimates probability of fake reports
- **AI Intelligence Cards**: Expandable cards with detailed AI analysis
- **Real-time AI Widgets**: Dashboard widgets showing high-risk AI alerts
- **Secure API Routes**: Server-side AI processing with input validation
- **Prompt Engineering**: Structured prompts for consistent AI outputs
- **Firestore AI Reports**: Separate collection for immutable AI analysis

### Day 4 Features
- **Interactive Live Map**: Fullscreen responsive map with dark theme using Mapbox GL JS
- **Real-Time Incident Markers**: Live incident markers with severity-based color coding
- **Animated Markers**: Pulsing effects for high-severity incidents
- **Incident Popup Cards**: Glassmorphism popups with AI analysis and safety advice
- **Threat Heatmap Visualization**: AI-powered heatmap overlay showing dangerous zones
- **Nearby Threat Detection**: Automatic detection of nearby incidents with distance calculation
- **Geolocation Support**: Browser geolocation to center map on user's location
- **Smart Filtering System**: Filter by severity, category, and time range
- **Live Alert Banner**: Floating banner showing critical incidents and emergency alerts
- **Responsive Intelligence Layout**: Mobile-first design with collapsible panels
- **Map Controls**: Zoom, center, and heatmap toggle controls
- **Threat Sidebar**: Advanced filtering sidebar with expandable sections
- **Mini Map Widget**: Dashboard preview widget with latest threats
- **Location-Based Queries**: Optimized Firestore indexes for geospatial queries
- **Distance Calculations**: Haversine formula for accurate distance measurements
- **Bearing Calculations**: Direction indicators for nearby threats

### Day 5 Features
- **Cyber Scam Intelligence**: Advanced scam detection and analysis
- **Gemini Vision Integration**: Image-based phishing detection using AI vision
- **QR Threat Analysis**: Scan and analyze QR codes for malicious content
- **Cyber Threat Dashboard**: Dedicated dashboard for cyber intelligence
- **Phishing Pattern Recognition**: AI-powered pattern matching for scam detection
- **URL Safety Analysis**: Real-time URL analysis and threat assessment
- **Image Forensics**: Extract and analyze images for malicious content
- **Cyber Incident Reporting**: Specialized reporting for cyber threats
- **Threat Intelligence Database**: Centralized database of known cyber threats
- **Real-time Cyber Alerts**: Instant notifications for new cyber threats
- **Secure Image Upload**: Safe image processing with validation
- **AI-Powered Analysis**: Gemini Vision for advanced image analysis
- **Threat Scoring**: 1-100 threat scoring for cyber incidents
- **Malicious Pattern Detection**: Identify common scam patterns
- **Emergency Cyber Response**: Quick response to cyber emergencies

### Day 6 Features
- **Real-Time Notification System**: Live notification center with toast alerts
- **Emergency SOS System**: One-click emergency alert with location attachment
- **SOS Emergency Types**: Medical, accident, fire, crime, natural disaster, cyber emergency
- **Emergency Broadcast System**: Admin/system-wide emergency broadcasts
- **Broadcast Types**: Flood warning, cyber attack, severe weather, city emergency, terror threat
- **Intelligent Alert Prioritization**: AI-powered priority scoring and urgency levels
- **Nearby Emergency Detection**: Automatic detection of incidents near user location
- **Live Activity Feed**: Real-time intelligence activity panel
- **Threat Radar Live**: Animated radar visualization of nearby threats
- **Emergency Timeline**: Chronological event tracking and escalation flow
- **Emergency Operations Center**: Dashboard transformed into live command center
- **Notification Center Page**: Dedicated page for managing all notifications
- **Alert Toast Component**: Real-time toast notifications with severity styling
- **NotificationCenter Component**: Full notification management with filters
- **EmergencyBanner Component**: Floating emergency broadcast banners
- **ActivityFeed Component**: Live activity feed with real-time updates
- **ThreatRadarLive Component**: Canvas-based radar visualization
- **EmergencyTimeline Component**: Timeline view of emergency events
- **Demo Simulation Mode**: Generate mock emergencies for hackathon presentations
- **Mobile SOS Button**: Floating SOS button for mobile devices
- **Firestore Notification Rules**: Secure rules for notifications, SOS alerts, broadcasts
- **Real-time Subscriptions**: Efficient Firestore listeners for live updates
- **Notification Batching**: Optimized notification delivery
- **SOS Cooldown Protection**: Prevent SOS spam with cooldown timer
- **Emergency Response Tracking**: Track SOS status and responders

### Day 7 Features
- **Loading Skeleton Components**: Professional loading states for all UI elements
- **Smooth Page Transitions**: Framer Motion animations for seamless navigation
- **Command Palette (CMD+K)**: Global keyboard shortcut launcher for quick navigation
- **Analytics Dashboard**: Comprehensive analytics page with Recharts visualizations
- **Incident Trends Chart**: 7-day incident trend analysis with area charts
- **Severity Distribution**: Pie chart visualization of incident severity
- **Category Distribution**: Bar chart showing incident categories
- **Status Distribution**: Pie chart for incident status breakdown
- **Hourly Activity Pattern**: Line chart showing hourly incident frequency
- **Demo Simulation Panel**: Professional demo controls for hackathon presentations
- **Full Sequence Demo**: Automated incident → SOS → broadcast sequence
- **Simulation Speed Control**: Adjustable demo simulation timing
- **SEO Metadata**: Complete OpenGraph and Twitter card metadata
- **Enhanced Sidebar Navigation**: Added Analytics and Notifications links
- **Production-Ready Analytics**: Real-time data visualization for hackathon demos
- **Professional Loading States**: Skeleton loaders for cards, charts, lists, maps
- **Animation Components**: FadeIn, SlideIn, ScaleIn, StaggerChildren utilities
- **Command Palette Navigation**: Quick access to all dashboard pages
- **Demo Mode Integration**: Seamless demo simulation in dashboard
- **Analytics Integration**: Full analytics page with live data
- **Performance Optimizations**: Recharts for efficient chart rendering
- **Keyboard Shortcuts**: CMD+K for command palette, ESC to close
- **Search Functionality**: Built-in search in command palette
- **Navigation Shortcuts**: Quick actions for common tasks

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Authentication**: Firebase Auth
- **Database**: Firebase Firestore
- **AI**: Google Gemini API + Gemini Vision
- **Maps**: Mapbox GL JS + react-map-gl
- **Charts**: Recharts
- **Animations**: Framer Motion
- **Command Palette**: cmdk
- **Search**: Fuse.js
- **Icons**: Lucide React
- **Deployment**: Vercel-ready

## 📁 Project Structure

```
signalx-ai/
├── app/                      # Next.js App Router
│   ├── api/                 # API routes
│   │   └── ai/              # AI API endpoints
│   │       └── analyze/     # AI analysis endpoint
│   ├── dashboard/           # Protected dashboard pages
│   │   ├── analysis/        # AI intelligence page
│   │   ├── feed/            # Live incident feed
│   │   ├── live-map/        # Interactive live map (Day 4)
│   │   ├── notifications/   # Notification center (Day 6)
│   │   ├── layout.tsx       # Dashboard layout with auth guard
│   │   ├── page.tsx         # Enhanced dashboard with AI widgets
│   │   ├── report/          # Incident reporting form with AI
│   │   ├── scam/            # Scam detector (Day 3)
│   │   └── settings/        # Settings page
│   ├── login/               # Login page
│   ├── signup/              # Signup page
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout with providers
│   └── page.tsx             # Landing page
├── components/              # Reusable components
│   ├── AIAnalyzingLoader.tsx # AI analyzing animation
│   ├── AIIntelligenceCard.tsx # AI intelligence card
│   ├── AIWidget.tsx         # Dashboard AI widget
│   ├── Button.tsx           # Button component
│   ├── Card.tsx             # Card component
│   ├── DashboardLayout.tsx  # Dashboard layout wrapper
│   ├── DashboardSidebar.tsx # Dashboard sidebar
│   ├── DashboardTopbar.tsx  # Dashboard topbar
│   ├── EmptyState.tsx       # Empty state component
│   ├── Features.tsx         # Features section
│   ├── Footer.tsx           # Footer component
│   ├── Hero.tsx             # Hero section
│   ├── IncidentCard.tsx     # Incident card component
│   ├── IncidentFeed.tsx     # Live incident feed
│   ├── LoadingSpinner.tsx   # Loading spinner
│   ├── Navbar.tsx           # Navigation bar
│   ├── StatCard.tsx         # Statistics card
│   ├── Toast.tsx            # Toast notifications
│   ├── AlertToast.tsx       # Real-time alert toasts (Day 6)
│   ├── NotificationCenter.tsx # Notification center (Day 6)
│   ├── SOSButton.tsx        # Emergency SOS button (Day 6)
│   ├── EmergencyBanner.tsx   # Emergency broadcast banner (Day 6)
│   ├── ActivityFeed.tsx     # Live activity feed (Day 6)
│   ├── ThreatRadarLive.tsx  # Animated threat radar (Day 6)
│   └── EmergencyTimeline.tsx # Emergency timeline (Day 6)
│   └── map/                 # Map components (Day 4)
│       ├── AlertBanner.tsx  # Live alert banner
│       ├── IncidentMarker.tsx # Animated incident markers
│       ├── IncidentPopup.tsx # Glassmorphism popup cards
│       ├── LiveMap.tsx      # Main live map component
│       ├── MapControls.tsx  # Map control buttons
│       ├── MiniMapWidget.tsx # Dashboard mini map
│       ├── NearbyThreatsWidget.tsx # Nearby threats widget
│       ├── ThreatHeatmap.tsx # AI threat heatmap
│       └── ThreatSidebar.tsx # Filter sidebar
├── context/                 # React contexts
│   ├── AuthContext.tsx      # Authentication context
│   └── ToastContext.tsx     # Toast notification context
├── firebase/                # Firebase configuration
│   └── firebase.ts          # Firebase initialization
├── firestore.indexes.json   # Firestore indexes for location queries
├── firestore.rules          # Firestore security rules
├── hooks/                   # Custom React hooks
│   ├── useSOS.ts           # SOS emergency hook (Day 6)
│   └── useDemoMode.ts      # Demo simulation hook (Day 6)
├── lib/                     # Utility functions
│   ├── ai.ts                # Gemini AI service
│   ├── ai-reports.ts        # AI reports Firestore operations
│   ├── firebase.ts          # Firebase utilities
│   ├── incidents.ts         # Incident operations
│   ├── map.ts              # Map utilities (Day 4)
│   └── notifications.ts    # Notification service (Day 6)
└── types/                   # TypeScript types
    └── index.ts             # Type definitions
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- A Firebase project (create one at https://console.firebase.google.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd signalx-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Firebase**

   a. Go to [Firebase Console](https://console.firebase.google.com/)
   
   b. Create a new project or use an existing one
   
   c. Enable Authentication:
      - Go to Authentication → Sign-in method
      - Enable Email/Password sign-in
   
   d. Enable Firestore:
      - Go to Firestore Database
      - Create database (choose production mode or test mode)
   
   e. Set Firestore Security Rules:
      - Go to Firestore Database → Rules
      - Copy the rules from `firestore.rules` file in the project root
      - Publish the rules
   
   f. Get your Firebase configuration:
      - Go to Project Settings → General → Your apps
      - Copy the config values

   g. Set up Gemini AI:
      - Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
      - Create a new API key
      - Copy the API key

   h. Set up Mapbox:
      - Go to [Mapbox Account](https://account.mapbox.com/)
      - Sign up or log in
      - Create a new access token
      - Copy the access token

4. **Configure environment variables**

   Create a `.env.local` file in the root directory:
   
   ```bash
   cp .env.local.example .env.local
   ```
   
   Then fill in your Firebase credentials, Gemini API key, and Mapbox token:
   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
   GEMINI_API_KEY=your_gemini_api_key
   NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_access_token
   ```

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📱 Available Pages

### Public Pages
- **/** - Landing page with hero and features
- **/login** - User login page
- **/signup** - User registration page

### Protected Dashboard Pages (Requires Authentication)
- **/dashboard** - Main dashboard with statistics and live feed
- **/dashboard/report** - Report new incidents
- **/dashboard/feed** - Live incident feed
- **/dashboard/analysis** - AI-powered analysis (Day 3)
- **/dashboard/scam** - Scam detection (Day 3)
- **/dashboard/settings** - User settings

## 🔐 Authentication

The app uses Firebase Authentication with email/password:

- **Signup**: Users can create an account with email and password (min 6 characters)
- **Login**: Existing users can sign in with their credentials
- **Session Persistence**: Auth state persists across page refreshes
- **Protected Routes**: Dashboard is only accessible to authenticated users

## 📊 Incident System

The incident management system is built on Firebase Firestore with real-time updates:

### Incident Schema
- **title**: Incident title (required)
- **description**: Detailed description (required, min 10 characters)
- **category**: Incident type (flood, fire, medical, accident, cyber_scam, crime, infrastructure)
- **severity**: Risk level (low, medium, high)
- **latitude/longitude**: Optional GPS coordinates
- **createdBy**: User ID who created the incident
- **createdAt**: Timestamp
- **status**: Incident status (open, investigating, resolved, closed)

### Features
- **Real-time Updates**: Live feed using Firestore listeners
- **Severity Color Coding**: Green (low), Yellow (medium), Red (high)
- **Category Icons**: Emoji icons for quick identification
- **Location Support**: GPS coordinates for mapping
- **Form Validation**: Client-side validation before submission
- **Toast Notifications**: Success/error feedback

## 🤖 AI Intelligence System

The AI-powered intelligence system uses Google Gemini API to automatically analyze incidents:

### AI Analysis Features
- **Automatic Processing**: AI analyzes incidents immediately after submission
- **Threat Scoring**: 1-100 threat score with visual indicators
- **Emergency Classification**: Low, Moderate, High, Critical levels
- **Safety Recommendations**: AI-generated actionable advice
- **Fake Report Detection**: Estimates probability of false reports
- **Structured Output**: Consistent JSON format for reliable parsing

### AI Response Schema
```json
{
  "category": "flood",
  "severity": "high",
  "threatScore": 87,
  "emergencyLevel": "Critical",
  "summary": "Heavy flooding detected near residential road.",
  "safetyAdvice": "Avoid nearby roads and move to higher ground.",
  "fakeReportProbability": "Low",
  "recommendedAction": "Notify nearby users immediately."
}
```

### Security
- Server-side API routes for secure AI calls
- Input sanitization and validation
- Rate limiting considerations
- Immutable AI reports in Firestore

## 🗺️ Live Safety Intelligence Map

The interactive live map provides real-time visualization of safety incidents with AI-powered threat analysis.

### Map Features
- **Real-Time Markers**: Live incident markers with severity-based color coding (green/yellow/red)
- **Animated Effects**: Pulsing animations for high-severity incidents
- **Interactive Popups**: Glassmorphism popup cards with AI analysis and safety advice
- **Threat Heatmap**: AI-powered heatmap overlay showing dangerous zones
- **Nearby Threats**: Automatic detection of incidents within user's radius
- **Geolocation**: Browser geolocation to center map on user's position
- **Smart Filters**: Filter incidents by severity, category, and time range
- **Live Alerts**: Floating banner showing critical incidents and emergency warnings
- **Responsive Design**: Mobile-first layout with collapsible panels and bottom sheets

### Map Controls
- **Zoom In/Out**: Adjust map zoom level
- **Center on User**: Quickly center map on your current location
- **Toggle Heatmap**: Show/hide threat heatmap overlay
- **Reset View**: Return to default map position

### Marker Colors
- **Green**: Low severity incidents
- **Yellow**: Medium severity incidents
- **Red**: High severity incidents (with pulsing animation)

### Distance Calculations
- Uses Haversine formula for accurate distance measurements
- Displays distance in meters (for <1km) or kilometers
- Calculates bearing direction (N, NE, E, SE, S, SW, W, NW)

### Firestore Indexes
The project includes optimized Firestore indexes for location-based queries and notifications:
- `incidents` collection indexed by `createdAt` and `severity`
- `incidents` collection indexed by `latitude`, `longitude`, and `createdAt`
- `incidents` collection indexed by `createdBy` and `createdAt`
- `ai_reports` collection indexed by `incidentId` and `threatScore`
- `ai_reports` collection indexed by `createdAt` and `threatScore`
- `notifications` collection indexed by `userId` and `createdAt`
- `notifications` collection indexed by `userId`, `read`, and `createdAt`
- `sos_alerts` collection indexed by `createdAt`
- `emergency_broadcasts` collection indexed by `active` and `createdAt`
- `activities` collection indexed by `createdAt`

Deploy these indexes using the Firebase CLI:
```bash
firebase deploy --only firestore:indexes
```

## 🎨 Design Features

- **Dark Mode Only**: Optimized for dark theme with futuristic aesthetics
- **Gradient Effects**: Beautiful gradient backgrounds and text
- **Glow Effects**: Subtle glow effects on cards and buttons
- **Responsive Design**: Mobile-first approach with responsive layouts
- **Smooth Animations**: Transitions and hover effects for better UX
- **Modern Typography**: Clean, readable fonts

## 🚀 Deployment

### Vercel Deployment

1. **Push your code to GitHub**

2. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Add environment variables in Vercel dashboard
   - Click "Deploy"

3. **Configure Environment Variables in Vercel**
   - Go to your project settings → Environment Variables
   - Add all the Firebase config variables from your `.env.local` file

### Manual Deployment

```bash
# Build the application
npm run build

# Start the production server
npm start
```

## 🔧 Configuration Files

- `next.config.mjs` - Next.js configuration
- `tailwind.config.ts` - Tailwind CSS configuration
- `tsconfig.json` - TypeScript configuration
- `.eslintrc.json` - ESLint configuration
- `postcss.config.mjs` - PostCSS configuration

## 📝 Environment Variables

| Variable | Description |
|----------|-------------|
| `NEXT_PUBLIC_FIREBASE_API_KEY` | Firebase API key |
| `NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN` | Firebase auth domain |
| `NEXT_PUBLIC_FIREBASE_PROJECT_ID` | Firebase project ID |
| `NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET` | Firebase storage bucket |
| `NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID` | Firebase messaging sender ID |
| `NEXT_PUBLIC_FIREBASE_APP_ID` | Firebase app ID |
| `GEMINI_API_KEY` | Google Gemini API key for AI analysis |
| `NEXT_PUBLIC_MAPBOX_TOKEN` | Mapbox access token for live map |

## 🎯 Future Enhancements

- [ ] Push notifications for alerts
- [ ] Advanced scam detection with AI
- [ ] User profile management
- [ ] Incident history and reports
- [ ] Community features
- [ ] Mobile app (React Native)
- [ ] Multi-language support
- [ ] Offline mode support
- [ ] Real-time collaboration features

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support, please open an issue in the GitHub repository.

