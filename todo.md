# Mental Wellness Companion Website - MVP Todo

## Overview
Creating a 5-page mental wellness website with React, Shadcn-UI, and Tailwind CSS.

## Files to Create/Modify:

### 1. Core Pages (4 main files)
- **src/pages/Index.tsx** - Welcome/Landing page with navigation buttons
- **src/pages/AIAssistant.tsx** - Interactive chatbot interface with assessment tools
- **src/pages/ResourcesHub.tsx** - Video and audio resources with multi-language support
- **src/pages/BookAppointment.tsx** - Confidential appointment booking with location filtering
- **src/pages/AdminDashboard.tsx** - Optional admin insights dashboard

### 2. Components (2 support files)
- **src/components/ChatBot.tsx** - AI chatbot component with predefined responses
- **src/components/Layout.tsx** - Common layout wrapper with navigation

### 3. Configuration
- **src/App.tsx** - Update routing for all pages
- **index.html** - Update title and meta tags for mental wellness theme

## Key Features to Implement:
1. **Landing Page**: Warm design, clear navigation buttons
2. **AI Assistant**: Simple chatbot with mental health screening questions (PHQ-9/GAD-7 style)
3. **Resources**: Embedded YouTube videos, audio players, language selector
4. **Booking**: Form with location-based counsellor suggestions
5. **Admin**: Basic dashboard with mock analytics

## Tech Approach:
- Use localStorage for session data (no backend required for MVP)
- Mock AI responses with predefined mental health guidance
- Embed sample YouTube wellness videos
- Simple form validation for appointments
- Responsive design with Tailwind CSS
- Warm, calming color scheme (blues, greens, soft tones)