# Frontend Mentor - Results summary component

![Design preview for the Results summary component coding challenge](./preview.jpg)

## My process

### Built with

- HTML5 
- Tailwind
- Flexbox

# Results Summary Component Documentation

## 1. Project Overview
This component displays:
- A Result section showing score, grade message, and description.
- A Summary section listing individual skill scores (Reaction, Memory, Verbal, Visual).
- Styled with Tailwind CSS and custom CSS variables.
- Fully responsive, optimized for mobile and desktop.

## 2. HTML Structure Breakdown

### 2.1. `<head>` Section
Includes:
- Meta tags for character encoding and responsive design.
- Link to compiled Tailwind CSS.
- Google Font: Hanken Grotesk.

### 2.2. `<body>` Structure
Two main sections inside `<main>`:

```
<main>
  <section class="result">...</section>
  <aside class="summary">...</aside>
</main>
```

## 3. Section-by-Section Explanation

### 3.1. Result Section
Displays:
- Title: "Your Result"
- Score inside circle
- Assessment message: "Great"
- Description about score comparison

### 3.2. Summary Section
Shows category scores (Reaction, Memory, Verbal, Visual) with icons and colored backgrounds.

### 3.3. Continue Button
A full-width button with gradient hover effect.

## 4. Responsive Design Behavior

### Mobile
- Vertical layout
- Rounded bottom corners on result card

### Desktop
- Side-by-side layout
- Summary card gets rounded right edges

## 5. Custom Tailwind Tokens
Uses variables such as:
- `--space-l`
- `--bg-red`
- `--Dark-gray-blue`
- And others, defined in Tailwind or global CSS.

## 6. Component Flow Summary
1. Result card with score
2. Performance breakdown
3. Continue button

## 7. Overall Observations
- Clean UI
- Good use of Tailwind
- Easy to maintain and extend
