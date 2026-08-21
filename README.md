# Weatherly - Next.js Weather Dashboard

A modern weather dashboard built with Next.js 15, Tailwind CSS, and TypeScript. Features real-time weather data visualization, interactive charts, and a responsive UI component library.

<a href="https://weatherly-weatherforecast.netlify.app/" target="_blank">
  <img width="1345" height="631" alt="preview png" src="https://github.com/user-attachments/assets/bf1f82a6-f146-41ce-bb0b-500e8298da90" />
</a>
## Features

- Real-time weather conditions display
- 7-day forecast with interactive charts
- Responsive grid layout with draggable/resizable panels
- Theme switching (light/dark mode)
- Comprehensive UI component library
- Form validation with React Hook Form + Zod
- Animated transitions with Tailwind

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/weatherly.git
```

2. Install dependencies:
```bash
npm install
```

3. Create `.env.local` file:
```env
NEXT_PUBLIC_OPENWEATHER_API_KEY=your_api_key_here
```

4. Run development server:
```bash
npm run dev
```

## Configuration

### Required Environment Variables
- `NEXT_PUBLIC_OPENWEATHER_API_KEY`: Obtain from [OpenWeatherMap](https://openweathermap.org/api)

### Available Scripts
- `dev`: Start development server
- `build`: Create production build
- `start`: Start production server
- `lint`: Run ESLint checks

## Tech Stack

- **Framework**: Next.js 15
- **Styling**: Tailwind CSS + Animate
- **Charts**: Recharts
- **UI Components**: Radix UI + Shadcn
- **Forms**: React Hook Form + Zod
- **State Management**: Jotai
- **Icons**: Lucide React
