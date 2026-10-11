# RecruitShield AI — Client Dashboard

RecruitShield AI is an intelligent candidate screening and recruitment fraud detection dashboard built with React 19, TypeScript, and Vite. It provides recruiters and hiring managers with autonomous candidate verification, real-time risk scoring, telemetry feeds, and interactive candidate pipeline management.

## Key Features

- Autonomous Candidate Intelligence: Real-time risk scoring, fraud signal classification, and candidate credentials analysis.
- Recruiter Interactive Dashboard: Pipeline filtering, candidate card inspector, verification audit logs, and instant Excel reporting export.
- Agent Telemetry Console: Live status monitoring of background forensic checks, verification latency, and anomaly alerts.
- Modern Glassmorphism UI: Custom dark-mode design system with responsive animations, fluid navigation, and data density.

## Tech Stack

- Frontend Framework: React 19 + TypeScript
- Build Tool: Vite
- Styling: Custom Vanilla CSS design system with CSS custom properties and glassmorphic elevation
- Icons & Visuals: Lucide React, Framer Motion

## Getting Started

### Prerequisites

- Node.js (version 18 or higher recommended)
- npm or yarn

### Installation

1. Install project dependencies:
   ```bash
   npm install
   ```

2. Configure environment variables (optional):
   Create a `.env` file in the root directory if pointing to a custom backend endpoint:
   ```env
   VITE_API_URL=http://localhost:8000
   ```

3. Launch the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## Project Structure

- `src/App.tsx`: Main dashboard application including pipeline state, candidate inspect drawer, AI chat interface, and telemetry monitor.
- `src/index.css`: Core design system, color tokens, layout utilities, and glassmorphic styling.
- `src/components/`: Modular interactive UI components including navigation and animated data visualizations.
- `index.html`: Web application entry point.
- `vercel.json`: Deployment routing configuration for single-page application routing.
