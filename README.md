# Clock
A simple digital clock application built with Python's Tkinter library. Displays the current time and updates every second.
# Simple Digital Clock

A minimalist digital clock application built using Python's Tkinter GUI library. This application displays the current time (hours, minutes, seconds, and AM/PM) and updates every second, providing a real-time clock experience.

## Features

* **Real-time Display:** Shows the current time accurately.
* **Live Updates:** Time updates every second without manual refresh.
* **Simple Interface:** Clean and straightforward graphical user interface.
* **Customizable:** Easily modify font, size, and colors in the code.

## Screenshots

![image](https://github.com/user-attachments/assets/fef4d914-6ac0-434e-a39c-0fed8aec6274)


## How to Run

### Prerequisites

* Python 3.x installed on your system.

### Installation

1.  **Clone the repository (or download the `Clock.py` file):**
    ```bash
    git clone [https://github.com/YourUsername/Simple-Digital-Clock.git](https://github.com/YourUsername/Simple-Digital-Clock.git)
    cd Simple-Digital-Clock
    ```
    *(Replace `YourUsername` with your actual GitHub username)*

2.  **Run the script:**
    ```bash
    python Clock.py
    ```

## Customization

You can easily customize the appearance of the clock by modifying the `label` widget's properties in the `Clock.py` file:

```python
label = tk.Label(root, font=('calibri', 40, 'bold'), background='yellow', foreground='red')
