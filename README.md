# CK Technologies

A modern web application built with Next.js, React, and TypeScript, featuring a robust backend powered by Prisma and PostgreSQL.

## 🚀 Features

- **Modern Stack**: Built with Next.js 16.2.9 and React 19.2.4
- **TypeScript**: Fully typed codebase for enhanced development experience
- **Database**: PostgreSQL integration with Prisma ORM
- **Styling**: Tailwind CSS 4 for responsive design
- **Development**: ESLint for code quality and TSX support

## 📋 Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| Next.js | 16.2.9 | React framework |
| React | 19.2.4 | UI library |
| TypeScript | 5.x | Type safety |
| Prisma | 7.8.0 | ORM & database |
| PostgreSQL | - | Database |
| Tailwind CSS | 4.x | Styling |
| ESLint | 9.x | Code linting |

## 📊 Project Structure

- **TypeScript**: 89.4%
- **JavaScript**: 5.9%
- **CSS**: 4.7%

## 🛠️ Getting Started

### Prerequisites

- Node.js (16+ recommended)
- npm or yarn
- PostgreSQL database

### Installation

1. Clone the repository:
```bash
git clone https://github.com/chimputu/ck_technologies.git
cd ck_technologies/ck-app
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

4. Generate Prisma client:
```bash
npm run postinstall
```

### Development

Run the development server:
```bash
npm run dev
```

The app will be available at [http://localhost:3000](http://localhost:3000)

### Build & Deploy

Build for production:
```bash
npm run build
```

Start production server:
```bash
npm start
```

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |
| `npm run postinstall` | Generate Prisma client |

## 🗄️ Database

This project uses Prisma ORM with PostgreSQL. Ensure your database connection is configured in `.env.local`:

```env
DATABASE_URL="postgresql://user:password@localhost:5432/ck_technologies"
```

## 🎨 Styling

The project uses Tailwind CSS 4 for styling. Configure your Tailwind settings in `tailwind.config.ts`.

## 📦 Dependencies

### Core Dependencies
- `next`: React framework
- `react` & `react-dom`: UI library
- `@prisma/client`: Database client
- `@prisma/adapter-pg`: PostgreSQL adapter
- `pg`: PostgreSQL driver

### Development Dependencies
- `typescript`: Type checking
- `tailwindcss`: Utility-first CSS
- `eslint` & `eslint-config-next`: Code quality
- `tsx`: TypeScript executor

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the terms you specify.

## 👤 Author

**chimputu**
- GitHub: [@chimputu](https://github.com/chimputu)

---

**Last Updated**: June 21, 2026

For more information or questions, please open an issue on GitHub.
