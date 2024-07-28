# Pomodoro Timer

A simple Pomodoro timer application built with Python and Tkinter. This application helps you manage your time more effectively by breaking work into intervals, traditionally 25 minutes in length, separated by short breaks.

## Features

- **Work and Break Intervals**: Customize your work sessions, short breaks, and long breaks.
- **Visual Countdown**: Watch the time tick away with a visual countdown.
- **Session Tracking**: Keep track of your completed work sessions with check marks.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/apiran/pomodoro-timer.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd pomodoro-timer
    ```

3. **Install the required dependencies:**

    Ensure you have Python installed.

## Usage

1. **Run the application:**

    ```bash
    python main.py
    ```

2. **Start the timer:**

    Click the "Start" button to begin the work interval. The timer will automatically switch between work, short break, and long break intervals.

3. **Reset the timer:**

    Click the "Reset" button to reset the timer and session count.

## Customization

You can customize the work, short break, and long break durations by modifying the following constants in `main.py`:

```python
WORK_MIN = 25       # Work interval duration in minutes
SHORT_BREAK_MIN = 5 # Short break duration in minutes
LONG_BREAK_MIN = 20 # Long break duration in minutes
```



## Customization Contributing
1. **Fork the repository.**
2. **Create a new branch for your feature or bugfix.**
3. **Make your changes and commit them.**
4. **Push your changes to your fork and submit a pull request.**

## Acknowledgements
Inspired by the Pomodoro Technique®.
Built with Tkinter for the GUI.
