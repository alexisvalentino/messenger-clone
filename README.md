# Real-Time Messenger Clone

A full-featured real-time messaging application built with modern web technologies. This project implements a WhatsApp-like messenger with real-time updates, group chats, and file sharing capabilities.

![Messenger Clone](https://i.imgur.com/your-screenshot-url.png)

## 🌟 Features

- 💬 Real-time messaging using Pusher
- 🔔 Message notifications and alerts
- 🎨 Modern UI with Tailwind CSS
- 📱 Fully responsive design
- 🔐 Multiple authentication methods:
  - Email/Password
  - Google OAuth
  - GitHub OAuth
- 📤 File and image sharing via Cloudinary
- 👥 Group chat functionality
- ✅ Message read receipts
- 🟢 Online/offline user status
- 📎 File attachments support
- 👤 User profile customization

## 🛠️ Tech Stack

- **Frontend:**
  - Next.js 13 (App Router)
  - React 18
  - TypeScript
  - Tailwind CSS
  - Headless UI

- **Backend:**
  - Next.js API Routes
  - Prisma ORM
  - MongoDB
  - NextAuth.js

- **Real-time:**
  - Pusher
  - WebSockets

- **Storage:**
  - Cloudinary (for file uploads)
  - MongoDB (for data)

## 🚀 Getting Started

### Prerequisites

- Node.js 14.x or later
- MongoDB database
- Pusher account
- Cloudinary account
- Google OAuth credentials (optional)
- GitHub OAuth credentials (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/messenger-clone.git
cd messenger-clone
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory with the following variables:
```env
DATABASE_URL="your_mongodb_connection_string"
NEXTAUTH_SECRET="your_nextauth_secret"

NEXT_PUBLIC_PUSHER_APP_KEY="your_pusher_app_key"
PUSHER_APP_ID="your_pusher_app_id"
PUSHER_SECRET="your_pusher_secret"

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="your_cloudinary_cloud_name"

# Optional: OAuth credentials
GITHUB_ID="your_github_client_id"
GITHUB_SECRET="your_github_client_secret"

GOOGLE_CLIENT_ID="your_google_client_id"
GOOGLE_CLIENT_SECRET="your_google_client_secret"
```

4. Set up the database:
```bash
npx prisma db push
```

5. Run the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Real-time features powered by [Pusher](https://pusher.com/)
- File storage by [Cloudinary](https://cloudinary.com/)
