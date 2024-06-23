# Habit Tracker

## Overview

Habit Tracker is a desktop application designed to help users manage and track their habits effectively. The application allows users to set up daily or weekly habits, monitor their progress, and view detailed statistics about their performance.

## Features

- **Add Habits**: Create new habits with a description, frequency (daily or weekly), and duration.
- **Track Progress**: Mark habits as completed and track your streaks.
- **View Statistics**: See detailed information about your habits, including streak records, amount completed, and missed counts.
- **Import Habits**: Import habits from a predefined format.
- **Missed Habits**: View a list of missed habits from the last month.

## Installation

1. Download the zip file and use a `main.exe` file from the repository.
2. Run the executable to start the application.

## Usage

1. **Adding a Habit**:
   - Enter the habit description.
   - Set the duration (in days).
   - Choose the frequency (daily or weekly).
   - Click the "Add Habit" button.

2. **Marking a Habit as Completed**:
   - Select a habit from the list.
   - Click the "Mark as Completed" button.

3. **Viewing Habit Details**:
   - Select a habit from the list to view detailed statistics in the panel below.

4. **Importing a Habit**:
   - Click the "Import habit" button and fill in the details in the import window.

5. **Viewing Missed Habits**:
   - Click the "Misses of last month" button to see a list of habits missed in the previous month.

## File Structure

- `main.py`: The main application code (for reference).
- `main.exe`: Executable file to run the application.
- `tests.py`: Unit tests for the application.
- `tasks.json`: Stores the list of habits.
- `missed.json`: Stores the list of missed habits.
