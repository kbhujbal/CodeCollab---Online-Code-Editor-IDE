# CodeCollab - Interactive Code Editor



<details>
  <summary>🖼️ View Screenshot</summary>
  
<div align="center">
  <img src="./public/CodeCollab Screenshot.png" alt="CodeCollab Screenshot" width="100%">
</div>
  
</details>

CodeCollab is a modern, real-time collaborative code editor that allows developers to write, share, and execute code in their browser. Built with Next.js, TypeScript, and powered by Convex for real-time collaboration.

## Features

### Development
- 🚀 Real-time code execution
- 🎨 Syntax highlighting
- 📝 Multiple language support
- 🌙 Dark mode support
- 💻 Monaco Editor integration

### Collaboration
- 👥 Real-time collaboration
- 💾 Auto-save functionality
- 📋 Code snippets sharing
- 🔒 Secure authentication with Clerk

### Pro Features
- ⚡ Advanced language support
- 🔄 Enhanced real-time features
- 🎯 Priority execution
- 💫 Premium themes

## Tech Stack

- **Frontend:**
  - Next.js 15.0
  - React
  - TypeScript
  - Tailwind CSS
  - Monaco Editor

- **Backend:**
  - Convex (Real-time Backend)
  - Clerk (Authentication)

- **Additional Tools:**
  - Framer Motion (Animations)
  - Zustand (State Management)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/code-collab.git
cd code-collab
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory with the following variables:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CONVEX_URL=your_convex_url
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Authentication

CodeCollab uses Clerk for authentication. To set up authentication:

1. Create an account at [clerk.dev](https://clerk.dev)
2. Create a new application
3. Copy your API keys to `.env.local`

## Real-time Backend

CodeCollab uses Convex for real-time functionality. To set up Convex:

1. Create an account at [convex.dev](https://convex.dev)
2. Install Convex CLI: `npm install -g convex`
3. Initialize Convex: `npx convex dev`

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue in the GitHub repository or contact me.

---

Built with ❤️ using Next.js, Convex, and Clerk.
