# AI Tools Platform

A modern web platform for discovering and exploring AI tools, built with Next.js and Strapi CMS.

## Project Structure

```
ai-tools-platform/
├── frontend/          # Next.js frontend application
│   ├── src/
│   │   ├── app/      # Next.js app directory
│   │   │   ├── components/  # React components
│   │   │   ├── lib/        # Utility functions and helpers
│   │   │   └── styles/     # Global styles and CSS
│   │   └── ...
│   ├── package.json
│   └── ...
└── backend/           # Strapi CMS
    ├── config/       # Strapi configuration
    ├── src/          # Strapi source files
    └── ...
```

## Getting Started

### Frontend (Next.js)

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env.local` file with the following variables:
   ```
   NEXT_PUBLIC_STRAPI_API_URL=http://localhost:1337
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

### Backend (Strapi)

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with the following variables:
   ```
   HOST=0.0.0.0
   PORT=1337
   APP_KEYS=your-app-keys
   API_TOKEN_SALT=your-api-token-salt
   ADMIN_JWT_SECRET=your-admin-jwt-secret
   JWT_SECRET=your-jwt-secret
   ```

4. Start the Strapi server:
   ```bash
   npm run develop
   ```

## Development

- Frontend runs on: http://localhost:3000
- Backend runs on: http://localhost:1337

## Technologies Used

- **Frontend**:
  - Next.js 15
  - React 19
  - Tailwind CSS
  - shadcn/ui components

- **Backend**:
  - Strapi CMS
  - Node.js
  - PostgreSQL

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Submit a pull request

## License

MIT 