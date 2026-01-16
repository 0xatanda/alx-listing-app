# Alx Listing App

The ALX listing App project amin to scaffold and lay the fundational structure for a modern Airbnb clone. This initial milestone focuses on setting up a well-organized and scalable codebase using Nextjs, Typescript, TailwindCSS, and ESLint. By establishing a clean folder structure, reusable componenets, and adhering to best practices, the project ensures a solid starting point for building a dynamic, responsive, and user-friendly property listing page

## 🎯 Project Goals

- Create a responsive and modern property listing interface

- Implement resuable UI components for scalability

- Establish a maintainable project structure with Typescript

- Build a foundation for future features like search, filtering, and booking

## 🏗️ Project Structure

```
alx-listing-app/
|
├── components/           # Reusable React components
|   |
│   └── common/          # Common UI components (Card, Button, etc.)
|
├── constants/           # Application constants and configuration
|
├── interfaces/          # TypeScript type definitions
|
├── pages/              # Next.js pages (Pages Router)
|
├── public/             # Static assets
|   |
│   └── assets/         # Images, icons, and other media files
|
├── styles/             # Global styles and Tailwind CSS
|
└── README.md           # Project documentation

```


## Key Directories
- ``` Components/ ``` : Contains reusable React components that can be used across the application.

- ``` interfaces/ ``` : Stores reuseable data, configuration settings, and UI text.

- ``` public/assets/ ``` : Houses all static assets like images, svgs and icons used throughout the app.

## Getting Started

### Prerequisties

- Nodejs (latest version)

- npm or yarn

### Installations

- Clone the repository:

``` git clone github.com/0xatanda/alx-listing-app ```

``` cd alx-listing-app ```

-  Install dependencies:

``` npm install ```


- Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Available Scripts

- ```npm run dev ```- Start the development server

- ```npm run build ```- Build the application for production

- ```npm run start``` - Start the production server

- ```npm run lint``` - Run ESLint for code quality checks


## Technologies Used

- Next.js - React framework for production

- TypeScript - Type-safe JavaScript

- Tailwind CSS - Utility-first CSS framework

- ESLint - Code linting and quality assurance


## 📦 Key Components

### Card Component

A reusable card component for displaying property information with support for images, ratings, and custom content.

### Button Component

A flexible button component with multiple variants (primary, secondary, outline, ghost) and sizes.

## 🔧 Configuration

The project is configured with:

- Pages Router (not App Router) for routing

- Tailwind CSS for styling with custom configuration

- TypeScript for type safety

- ESLint for code quality

## 📝 Development Notes
- All components are built with TypeScript for better type safety

- Tailwind CSS is configured to scan pages/ and components/ directories

- The project follows Next.js best practices for file organization

- Reusable components are placed in components/common/ for easy access

## 🤝 Contributing

- Fork the repository

- Create a feature branch

- Make your changes

- Run tests and linting

- Submit a pull request

## 📄 License

This project is part of the ALX curriculum and is for educational purposes.