
# Blog Site

A simple personal blog built with React. This project demonstrates how to create reusable React components, pass data using props, and render a list of blog posts dynamically.

## Project Overview

The blog displays:
- The blog name in the header.
- A blog logo and description in the About section.
- A list of articles, each displaying its title, publication date, and preview.

The blog content is stored in `src/data/blog.js` and passed to components through props.

## Component Structure

The application follows this component hierarchy:

```text
App
├── Header
├── About
└── ArticleList
    └── Article
```

### Components  

- **App:** The main component. Imports the blog data and renders the other components.
- **Header:** Displays the blog name using the `name` prop.
- **About:** Displays the blog logo and description using the `image` and `about` props.
- **ArticleList:** Receives the posts array and renders an Article component for each post.
- **Article:** Displays an individual article's title, date, and preview using props.

## Technologies Used

- React
- JavaScript
- JSX
- Vite
- Vitest
- React Testing Library

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Leonard371832/react-components-props-vite-lab.git
```

### 2. Navigate into the project directory

```bash
cd react-components-props-vite-lab
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL provided by Vite in your browser to view the blog.

## Running Tests

Run the test suite with:

```bash
npm test
```

The tests verify that the components render correctly, receive props, and display the expected content.

## Screenshot

The screenshot below shows the completed Blog Site application.

![Blog Site Screenshot](./images/blog-site.png)

## Learning Objectives

This project provided practice in:

- Creating reusable functional React components.
- Passing data between components using props.
- Rendering lists of components using JavaScript's `map()` method.
- Using unique keys when rendering lists.
- Applying default prop values.
- Testing React components using Vitest and React Testing Library.