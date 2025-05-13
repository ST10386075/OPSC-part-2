# OPSC-part-2
# PocketPlanner

**PocketPlanner** is a smart and user-friendly budget management Android app designed to help users track income, manage expenses, set savings goals, and stay financially on track. Built using Kotlin and Android Studio, it features intuitive interfaces, a local RoomDB database for offline use, gamification features for motivation, and optional photo attachments for expense entries.

## 📱 Features

- 📥 **Income & Budget Tracking**  
  - Set your monthly income/budget.
  - See real-time updates on remaining budget after every entry.

- 💸 **Expense Management**
  - Add expense entries with amount, description, category, date, and time.
  - View all expenses in a scrollable list.
  - Categorized expenses (Groceries, Transport, Utilities, etc.)

- 📷 **Photo Attachments**  
  - Option to attach receipts or related photos to each expense entry.

- 🎯 **Savings Goals**
  - Set a monthly savings goal.
  - Receive alerts when you're nearing or exceeding your goal.

- 🏆 **Gamification**
  - Earn badges for milestones (e.g., staying under budget, logging daily entries).

- 🧠 **Intelligent Design**
  - Uses RoomDB for offline storage.
  - Color indicators for budget health (e.g., green = within budget, red = over budget).

## 📂 Structure

- `HomeFragment.kt`: Main screen for budget input, adding expenses, and viewing summary.
- `LoginDialogFragment.kt`: Optional login prompt shown on first use.
- `Expense.kt`: Data class to represent expense entries.
- `RoomDB`: Local database integration for storing expense records.
- `FragmentHomeBinding`: Handles all view bindings from the home fragment layout.

## 🛠️ Tech Stack

- **Kotlin** - Main development language
- **RoomDB** - Local persistent database
- **View Binding** - For efficient UI access
- **Material Components** - UI design and responsiveness
- **MVVM (recommended)** - Future architecture support

## 🧪 Validation & UX

- Input validation for empty fields, invalid numbers, and missing date/time.
- Date & Time Picker dialogs for easy entry.
- Spinners for quick category selection.
- Focus-based income/goal update handling.


Link - https://github.com/ST10386075/OPSC-part-2/edit/main/README.md
