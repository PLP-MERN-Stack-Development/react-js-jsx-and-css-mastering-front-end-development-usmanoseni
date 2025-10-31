# Task Manager Dashboard

A responsive React application built with Vite and Tailwind CSS that demonstrates modern front-end development practices including component architecture, state management, hooks usage, and API integration.

## 🚀 Live Demo

[View Live Demo](your-deployed-url-here) <!-- Replace with your actual deployed URL -->

## ✨ Features

- Responsive design for mobile, tablet, and desktop
- Dark/Light theme toggle
- Task management with CRUD operations
- API integration with JSONPlaceholder
- Custom reusable components
- Local storage persistence
- Search and filter functionality

## 🛠️ Tech Stack

- React + Vite
- Tailwind CSS
- React Router
- PropTypes
- Context API

## 📦 Installation

1. Clone the repository:

```bash
git clone [your-repo-url]
cd [repository-name]
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Build for production:

```bash
npm run build
```

## 🔧 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=your_api_url_here
```

## 📁 Project Structure

```
src/
├── components/
│   ├── Button/
│   ├── Card/
│   ├── Navbar/
│   ├── Footer/
│   ├── TaskManager/
│   ├── PostList/
│   └── ThemeContext/
├── pages/
├── hooks/
├── utils/
└── assets/
```

## 🎨 Component Usage

### Button Component

```jsx
<Button variant="primary" size="md">
  Click Me
</Button>
```

### Card Component

```jsx
<Card
  title="Card Title"
  content="Card content goes here"
  image="path/to/image"
/>
```

### TaskManager Component

```jsx
<TaskManager defaultTasks={[]} onTaskUpdate={(tasks) => console.log(tasks)} />
```

### PostList Component

```jsx
<PostList endpoint="/posts" itemsPerPage={10} />
```

### Theme Context Usage

```jsx
const { theme, toggleTheme } = useTheme();
```
