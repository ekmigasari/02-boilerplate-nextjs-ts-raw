# Boilerplate NextJs (TypeScript)

This is a basic boilerplate setup for a Next.js project using pnpm as the package manager.

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your machine.

### Installing pnpm

If you don't have pnpm installed, you can install it using the following command:
`npm install -g pnpm`

### Boilerplate Installation

1. Open boilerplate package or clone (git clone)
2. Navigate to the project directory
3. Install dependencies using pnpm
   `pnpm install`
4. To run the development server
   `pnpm dev`
5. Install Pnpm
6. Setup NextJs

## NextJs Setup

### Initial setup

This initial setup provides a TypeScript-enabled Next.js project with ESLint, Tailwind CSS, organized within a src/ directory, utilizing App Router, and without default import aliases.

- TypeScript? Yes
- ESLint? Yes
- Tailwind CSS? Yes
- src/ directory? Yes
- Use App Router? Yes
- Default import alias (@/\*)? No

### Folder Structure

```
src/
|-- app/
| |-- page.tsx
| |-- layout.tsx
| |-- favicon.ico
| |-- api/
|-- components
|-- styles
| |-- globals.css
|--utils
|--lib
|--types
public
middleware.js
```

**Explanation:**

- `src/`: The root directory for the source code of your Next.js application.
- `app/`: This directory encapsulates application-specific files and components.
- `api/`: A directory for handling API routes. Next.js automatically turns files in this directory into API routes, allowing you to define server-side logic.
- `components/`: Contains React components that can be reused across multiple pages or sections of your application.
- `styles/`: Holds stylesheets for your application.
- `globals.css`: A global stylesheet that provides styles applied throughout your application. This can include global resets or styles that are not specific to any component.
- `utils/`: A directory for utility functions or modules that can be shared across your application.
- `lib/`: Commonly used for housing libraries, modules, or functions that are not specific to any particular feature but are shared across the application.
- `types/`: TypeScript type definitions reside here, providing a central location for defining custom types and interfaces used throughout your project.
- `public/`: The directory for static assets like images, files, or other resources that should be served as-is. Contents of this directory are accessible from the root of your application.
- `middleware.js`: This file appears to be a middleware script, likely handling server-side logic or middleware functionality. Ensure it's appropriately integrated into your Next.js application, depending on your specific requirements.

By following this organized structure, you establish a clear separation of concerns and facilitate maintainability as your Next.js TypeScript project evolves.

## ESLINT Setup

about eslint

### Config

How would you like to use ESLint?
To check syntax and find problems

What type of modules does your project use?
JavaScript modules (import/export)

Which framework does your project use? …
▸ React

Eslint v8.x

Where does your code run? browser and node

use javascript standar

https://standardjs.com/

## Prisma Setup

## Zod
