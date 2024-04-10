# Expanding Cards

## Overview

This project demonstrates expanding cards that show different images and titles when clicked.

## Features

- **Responsive Design**: The layout adjusts to fit different screen sizes, ensuring a seamless user experience.
- **Interactive Cards**: Clicking on a card expands it to show more details, while the others shrink.
- **Smooth Transitions**: The expansion and contraction of cards are animated for a visually pleasing effect.
- **Customizable Content**: The images and titles displayed on the cards can be easily customized.

## How It Works

The project is composed of three main parts: HTML, CSS, and JavaScript.

### JavaScript

The JavaScript adds interactivity to the cards. It listens for click events on the panels and toggles the `active` class accordingly. When a panel is clicked, it removes the `active` class from all panels and then adds it back to the clicked panel, causing it to expand and the others to shrink.
