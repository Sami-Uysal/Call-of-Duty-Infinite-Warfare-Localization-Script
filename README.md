# Call of Duty: Infinite Warfare Localization Script

This script allows you to export, import, and apply localization strings for Call of Duty: Infinite Warfare.
Based on https://github.com/yusuf202021/cod-iw-localization.

## Prerequisites

Before running this script, you need to install the required Python packages and ensure the game is running.

## Running the Script


1. **Open a Command Prompt (CMD) as an administrator:**
    - Click the Start menu.
    - Type `cmd`.
    - Right-click on Command Prompt and select "Run as administrator".


2. **Install the required Python packages:**
    - Navigate to the directory where `requirements.txt` is located.
    - Run the following command to install the required packages:


    ```bash
    pip install -r requirements.txt
    ```


3. **Ensure Call of Duty: Infinite Warfare is running.**


4. **Navigate to the directory where `main.py` is located:**
    - For example, if `main.py` is located in `C:\Scripts`, you would run:


    ```bash
    cd C:\Scripts
    ```

5. **Run the script with the appropriate parameter:**
    - To export localization strings to `localize.json`:


        ```bash
        python main.py -e
        ```


    - To import localization strings from `localize.json` and apply them to the game:


        ```bash
        python main.py -i
        ```


    - To apply previous changes stored in `changes.json` to the game:


        ```bash
        python main.py -a
        ```


## Notes

- Ensure that the game (Call of Duty: Infinite Warfare) is running when you execute the script.
- Running the script with administrator privileges is required to access and modify the game process memory.
- If you encounter any errors or need further assistance, please check the error messages printed in the command prompt and verify that all prerequisites are met.

---

Save this content into a file named `README.md` in the same directory as your script and `requirements.txt`. This will provide clear instructions for anyone needing to set up and run the script.
