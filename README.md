# HourglassTimer
This is a single-file, highly interactive Hourglass Timer web application built entirely using modern HTML, CSS, and JavaScript. It functions completely offline without any external dependencies or frameworks, combining sleek retro-inspired aesthetics with modern productivity features.
🌟 Key Features
Smooth Hourglass Animation: Features an interactive visual hourglass with a dynamic central stream that animates while the timer is running. The top and bottom sand levels adjust fluidly based on the exact percentage of remaining time.

Intuitive Pause & Resume: Built with robust state management, the timer seamlessly pauses at the exact millisecond and resumes without any time jumps or resets.

Input Clamping (Max 99 Mins): Includes strict boundaries on the numeric input fields, automatically constraining minutes between 0 and 99 and seconds between 0 and 59 to prevent invalid values.

Persistent History System (LocalStorage): Automatically logs the last 20 completed sessions with accurate durations and timestamps. The data remains securely stored even if the browser is refreshed or closed.

Quick Preset Buttons: Offers one-click buttons for common productivity intervals (e.g., Pomodoro 25m, 5m breaks, 10m, 30m) for swift deployment.

Hardware-Level Audio Alert: Uses the browser’s native Web Audio API to generate a crisp electronic beep when the time is up, ensuring an audible alert without needing to download external .mp3 files.

Responsive Dark Mode UI: Designed with a clean, battery-saving dark interface that automatically adapts to both desktop monitors and mobile screens.
