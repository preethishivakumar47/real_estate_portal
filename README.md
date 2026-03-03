# Real Estate Project - Frontend

A modern real estate web application built with React, TypeScript, and Vite.

## Features

- **Property Listings**: Browse and view detailed property information
- **Authentication**: Secure user authentication and authorization
- **Property Management**: Add and manage properties
- **Property Map**: Interactive map view for property locations
- **Messaging**: Communication system between users
- **Dashboard**: User dashboard for personalized content
- **Responsive Design**: Fully responsive UI with Tailwind CSS

## Project Structure

```
src/
├── components/      # Reusable React components
│   ├── AuthModal.tsx
│   ├── AuthRequiredModal.tsx
│   ├── Header.tsx
│   ├── PropertyCard.tsx
│   ├── PropertyDetailModal.tsx
│   ├── PropertyMap.tsx
│   └── PropertyMapSelector.tsx
├── pages/          # Page components
│   ├── About.tsx
│   ├── AddProperty.tsx
│   ├── Contact.tsx
│   ├── Dashboard.tsx
│   ├── Home.tsx
│   ├── Messages.tsx
│   └── Properties.tsx
├── services/       # API services
│   ├── messageService.js
│   └── propertyService.js
├── context/        # React context for state management
│   └── AuthContext.tsx
├── data/           # Mock or static data
│   ├── enquiries.ts
│   └── properties.ts
├── config/         # Configuration files
│   └── api.js
└── types/          # TypeScript type definitions
    └── index.ts
```

## Tech Stack

- **Frontend Framework**: Angular
- **Language**: TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **CSS Processing**: PostCSS
- **Linting**: ESLint

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## Available Scripts

- `npm run dev` - Start development server at http://localhost:5173
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint to check code quality

## Configuration Files

- `vite.config.ts` - Vite configuration
- `tsconfig.json` - TypeScript configuration
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
- `eslint.config.js` - ESLint configuration

## Environment Variables

Create a `.env` file in the root directory for environment-specific configuration. Update `src/config/api.js` with your API endpoints.

## Contributing

1. Follow the existing code structure and naming conventions
2. Use TypeScript for new components
3. Run `npm run lint` before committing
4. Create pull requests for review

## License

This project is proprietary. All rights reserved.

## Support

For issues or questions, please contact:

- **Name**: PREETHI S
- **Role**: Frontend Development
- **Email**: preethiaradhya1547@gmail.com" 
