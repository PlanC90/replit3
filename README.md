# MemeX Bot Management Dashboard

A modern web application for managing social media tasks and rewards through a Telegram bot.

## Features

- 📊 Real-time dashboard with analytics
- 👥 User profile management
- 🔗 Social media link tracking
- 💰 Reward system
- ⚙️ Admin controls
- 📥 Data export capabilities

## Live Demo

You can try the application at: [MemeX Bot Dashboard](https://planc90-deno-41.deno.dev)

## Running on Replit

1. Create a new Repl and select "Node.js" as the template
2. Import this GitHub repository into your Repl
3. Click on "Run" to start the development server

The application will automatically:
- Install dependencies
- Build the project
- Start the development server

## Development

To run the project locally:

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## Environment Setup

Create a `.env` file in the root directory with the following variables:

```env
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
```

## Project Structure

```
├── data/               # JSON data storage
├── public/            # Static assets
├── src/
│   ├── components/    # React components
│   ├── pages/         # Page components
│   ├── services/      # API services
│   └── types/         # TypeScript types
└── server.ts          # Deno server
```

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Deno

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
