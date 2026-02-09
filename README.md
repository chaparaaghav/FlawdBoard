# FlawdBoard Walkthrough

## Overview
FlawdBoard is a modern, AI-powered personal expense tracker dashboard. It combines sleek glassmorphism design with powerful financial analytics and an integrated AI assistant.

## Features

### 1. **Interactive Dashboard**
- **Visual Analytics**: Real-time donut, bar, and line charts powered by Chart.js.
- **Budget Tracking**: Set monthly budgets per category and track spending against them.
- **Transaction Management**: Add, view, filter, and delete transactions.
- **Overspending Alerts**: Automatic notifications when category budgets are exceeded.

### 2. **Account Management**
- **Flexible Accounts**: Add any bank, wallet, or cash account.
- **Edit/Delete**: Rename accounts (migrates old transactions!) or remove unused ones.
- **Dynamic**: All dropdowns and filters update automatically.

### 3. **AI Financial Assistant**
- **Context-Aware Chat**: The AI knows your current transactions and budgets.
- **Smart Analysis**: Ask questions like "How can I save more on food?" or "Analyze my spending trends."
- **Secure Integration**: Your OpenAI API key is stored locally in your browser.

### 4. **Modern UI/UX**
- **Glassmorphism Design**: Premium aesthetic with dark mode and vibrant colors.
- **Micro-Interactions**: Smooth animations, hover effects, and transitions.
- **Responsive**: Works beautifully on desktop and mobile.

### 5. **GitHub Integration**
- **Repository**: Published to [FlawdBoard](https://github.com/chaparaaghav/FlawdBoard)
- **Open Source**: MIT Licensed and ready for contributions.

### 6. **Custom Categories**
- **Manage**: Create, view, delete, and **Edit** custom categories.
- **Color Control**: Choose from 10 presets or enter a precise **Hex Code**.
- **Smart Editing**: Renaming a category automatically updates all your past transactions.
- **Dynamic**: Changes reflect instantly across budgets and transactions.
- **Persistent**: Categories are saved to browser storage.

### 7. **Income Tracking**
- **Dual Mode**: Easily toggle between Income and Expense transactions.
- **Visual Distinction**: Income categories are excluded from spending charts and budgets.
- **Net Balance**: Dashboard shows your true financial position (Income - Expenses).

### 8. **Robust Reliability**
- **Auto-Recovery**: Advanced error handling ensures your data loads safely on reload.
- **Dynamic Charts**: Adding new categories instantly updates chart labels and colors.

### 9. **UI Improvements**
- **Redesigned Summary Cards**: Replaced simple text cards with a premium design featuring:
  - **Icons**: Visual indicators for Balance, Income, and Expenses.
  - **Sparklines**: Mini-charts showing daily trends for the selected month to provide at-a-glance insights.
  - **Glassmorphism**: Enhanced visual depth and style consistent with the application theme.

## Usage

1. **Launch**: Open `http://localhost:8080/expense-tracker.html` in your browser.
2. **Add Data**: Use the "Add Transaction" button or "Budgets" button.
3. **Chat**: Click the floating chat button and enter your OpenAI API key to start analyzing.

## Project Structure
- `expense-tracker.html`: Single-file application containing all HTML, CSS, and JS.
- `README.md`: Project documentation.
- `.gitignore`: Git configuration.

---
*Built with ❤️ by Trifect Media*
