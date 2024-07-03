# Call of Duty: Infinite Warfare Localization Script

This script allows you to export, import, and apply localization strings for Call of Duty: Infinite Warfare. Follow these steps to get started!

## Prerequisites

Before you begin, make sure you have the necessary Python packages installed and that the game is running.

## Running the Script

1. **Open Command Prompt (CMD) as an Administrator:**
    - Click the Start menu.
    - Type `cmd`.
    - Right-click on Command Prompt and select "Run as administrator".

2. **Install the Required Python Packages:**
    - Navigate to the directory where `requirements.txt` is located.
    - Run the following command to install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. **Ensure Call of Duty: Infinite Warfare is Running:**
    - Make sure the game is up and running before you proceed.

4. **Navigate to the Directory Containing `main.py`:**
    - For example, if `main.py` is located in `C:\Scripts`, navigate to that directory by running:

    ```bash
    cd C:\Scripts
    ```

5. **Run the Script with the Appropriate Parameter:**
    - To export localization strings to `localize.json`, use:

        ```bash
        python main.py -e
        ```

    - To import localization strings from `localize.json` and apply them to the game, use:

        ```bash
        python main.py -i
        ```

    - To apply previous changes stored in `changes.json` to the game, use:

        ```bash
        python main.py -a
        ```

## Notes

- **Ensure the Game is Running:** Make sure Call of Duty: Infinite Warfare is running when you execute the script.
- **Run with Administrator Privileges:** Running the script with administrator privileges is necessary to access and modify the game's memory.
- **Troubleshooting:** If you encounter any errors or need further assistance, check the error messages printed in the command prompt and ensure all prerequisites are met.

---

Happy gaming!
