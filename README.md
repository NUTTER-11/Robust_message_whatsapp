Here's a README file for your script that uses `pyautogui`, `webbrowser`, `time`, and `pywhatkit` to automate WhatsApp messages:

---

# WhatsApp Automation Script

## Overview

This script automates sending messages on WhatsApp using Python. It includes two main functions:
1. `sendtimestampmsg()` - Sends a WhatsApp message at a specified time.
2. `spam100()` - Sends 100 repeated messages in a chat.

## Files

### `main.py`

This script automates WhatsApp messaging using the following libraries:

- `pyautogui`: For automating keyboard and mouse actions.
- `webbrowser`: For opening the WhatsApp Web page.
- `time`: For adding delays between actions.
- `pywhatkit`: For sending WhatsApp messages at a specified time.

#### Functions

**`sendtimestampmsg()`**

- Opens WhatsApp Web in the default web browser.
- Uses `pywhatkit` to send a WhatsApp message at a specified time.
- **Parameters**:
  - Phone number (replace `'enter_your_mobile_no'` with the recipient's number).
  - Message content (replace `'enter_your_name'` with the desired message content).
  - Time to send the message (currently set to 22:12).

**`spam100()`**

- Opens WhatsApp Web in the default web browser.
- Waits for 20 seconds to ensure WhatsApp Web is fully loaded.
- Uses `pyautogui` to repeatedly send the message "hi" 100 times.
- **Parameters**: None.

#### How to Run

1. Ensure you have the required libraries installed:
    ```bash
    pip install pyautogui pywhatkit
    ```

2. Run the script:
    ```bash
    python main.py
    ```

3. The script will perform the following actions:
    - Open WhatsApp Web in your default web browser.
    - For `sendtimestampmsg()`, send a message at the specified time (you may need to adjust the time settings as needed).
    - For `spam100()`, send 100 repeated "hi" messages after a 20-second delay.

#### Notes

- You must be logged into WhatsApp Web in your browser before running the script.
- Adjust the phone number, message content, and time settings in the `sendtimestampmsg()` function as needed.
- Ensure that the WhatsApp Web interface matches the expected layout for `pyautogui` to work correctly.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/) for automating GUI interactions.
- [PyWhatKit](https://pypi.org/project/pywhatkit/) for sending scheduled WhatsApp messages.
- [WebBrowser](https://docs.python.org/3/library/webbrowser.html) for opening web pages.

---

Feel free to adjust or expand the README as needed for your specific use case!
