# Turn Undead Simulator

## Description
An interactive web-based simulator for calculating the success chance of the "Turn Undead" ability. This tool helps players understand how character stats, base level, and skill level affect the probability of successfully turning undead enemies. Built with React and Tailwind CSS for a modern, responsive interface.

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No installation or server required

### Installation
1. Clone or download the project
2. Open `index.html` in your web browser
3. Adjust the sliders to simulate different character stats and see the success chance change in real-time

## Features
- **Interactive Character Stats**: Adjust Base Level (1-175), INT (1-200), LUK (1-200), and Skill Level (1-10)
- **Real-time Calculation**: Uses the formula: `(SkillLv×20 + INT + LUK + BaseLv + (1 - HP%)×200) / 10`
- **Visual Graph**: Dynamic chart showing success chance vs. enemy HP percentage
- **Hover Tooltips**: Hover over the chart to see exact success rates at different HP levels
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **No External Dependencies**: All libraries loaded from CDNs

## Usage
1. Use the sliders in the left panel to input your character's stats
2. View the real-time success chance calculation in the chart
3. The chart shows how success chance increases as the target enemy's HP decreases
4. Maximum possible success chance is capped at 70%

## Technical Stack
- **React 18**: UI framework
- **Tailwind CSS**: Styling and responsive design
- **Babel**: JSX transpilation
- **SVG**: Interactive chart rendering

## License
This project is licensed under the MIT License.
