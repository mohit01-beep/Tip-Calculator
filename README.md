# Tip Calculator

A lightweight, single-page tip calculator that helps you split a bill and choose a tip amount. It is built with plain HTML, CSS, and JavaScript, with no dependencies or build step.

## Features

- Enter a bill amount and select a 10%, 15%, 18%, or 20% tip.
- Enter a custom tip percentage.
- Split the total across any number of people.
- See the tip, total, and per-person amount update as you change the inputs.
- View amounts formatted as US dollars.

## Use

Open `index.html` in a web browser. No installation or server is required.

The bill defaults to `$50`, the tip to `15%`, and the number of people to `2`. Selecting a preset tip clears the custom tip. Entering a custom tip overrides the selected preset.

## Calculation

- Tip = bill amount x tip percentage
- Total = bill amount + tip
- Per person = total / number of people

The calculator displays a validation message for negative bill or tip amounts, invalid numeric values, or fewer than one person.