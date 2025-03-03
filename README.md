# Cuberto.com Homepage Animation Clone

This project is a recreation of specific animations and transitions from the Cuberto.com homepage, focusing on implementing modern, smooth animations using React, Tailwind CSS, and Framer Motion.

## Sections Implemented

1. **Animated Navbar** - With smooth transitions, mobile menu animations, and scroll effects
2. **Hero Section** - With parallax scrolling and animated text elements
3. **Services Section** - With staggered animations and hover effects
4. **Projects Section** - With scroll-triggered animations and hover effects
5. **Marquee Section** - With continuous scrolling animation for brand logos
6. **Contact Section** - With form animations and interactive elements
7. **Custom Cursor** - A custom cursor that changes size and color on interactive elements

## Technologies Used

- React.js
- TypeScript
- Tailwind CSS for styling
- Framer Motion for animations
- Custom hooks for scroll and viewport animations

## Challenges and Solutions

### Challenge 1: Implementing Smooth Parallax Effects
The parallax scrolling effect in the hero section required careful coordination between scroll position and element transformations. I solved this by using Framer Motion's `useScroll` and `useTransform` hooks to create smooth, performant parallax effects that respond to the user's scroll position.

### Challenge 2: Creating a Custom Cursor
Implementing a custom cursor that follows mouse movement and changes appearance when hovering over interactive elements was challenging. I created a solution using Framer Motion's animation capabilities and React's event handling to track mouse position and detect when the cursor is over interactive elements.

### Challenge 3: Responsive Animations
Ensuring animations work well across different screen sizes required careful planning. I implemented responsive design principles and conditional rendering to provide appropriate animations for different viewport sizes.

## Running the Project

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the development server with `npm run dev`
4. Open your browser to the local server URL

## Deployment

The project is ready to be deployed to platforms like Netlify.
