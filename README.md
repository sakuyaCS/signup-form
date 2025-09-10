# Sign-Up Form

A responsive sign-up form built as part of The Odin Project's Intermediate HTML & CSS course.

## About

This project recreates a sign-up form design with a sidebar and functional form validation. I built it to practice CSS layout techniques, form handling, and responsive design principles.

## Live Preview
https://sakuyacs.github.io/signup-form/

## What I Learned

- **CSS Flexbox**: Used flexbox for the main layout and form grid
- **Form Validation**: Implemented client-side validation with visual feedback
- **CSS Positioning**: Absolute positioning for overlay elements
- **Custom Fonts**: Loading and using web fonts with @font-face
- **Responsive Design**: Making layouts work on different screen sizes

## Features

- Two-column layout with image sidebar and form content
- Real-time password validation with color feedback
- Custom styling for form inputs and buttons

## Technologies Used

- HTML5
- CSS3
- Custom web fonts

## Key Challenges

- Getting the overlay to position correctly over the background image
- Making the form section span full width while keeping content centered
- Implementing proper form validation states with CSS pseudo-selectors
- Organizing CSS in a maintainable way

## Code Highlights

The form uses flexbox for responsive layout:
```css
.input-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
}

.input-group {
    flex: 1 1 45%;
}
```

Password validation provides visual feedback:
```css
input[type="password"]:invalid:not(:focus):not(:placeholder-shown) {
    border: 2px solid red;
    background-color: #ffe6e6;
}
```

## Acknowledgments

- Design and project requirements from [The Odin Project](https://www.theodinproject.com/)
- Background photo by [Mohammadreza Charkhgard](https://unsplash.com/@mrcharkhgard) on [Unsplash](https://unsplash.com)
