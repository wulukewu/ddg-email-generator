
# Temporary Email Generator

A simple Python script that generates temporary email addresses using the DuckDuckGo Email Protection API and copies to your clipboard. Bind the script to a keyboard shortcut for instant access when signing up for new accounts or services.

## Prerequisites

Create a `.env` file in the same directory as the script and add your DuckDuckGo API access token:

   ```
   DUCKDUCKGO_ACCESS_TOKEN=your_access_token_here
   ```

You can find this by going to https://duckduckgo.com/email/settings/autofill and inspecting the network requests when generating a new email address.


## Setting Up a Keyboard Shortcut

### Windows

1. Save the script as `generate_email.pyw`.
2. Create a shortcut to the script.
3. Right-click the shortcut, select Properties, and set your desired key combination in the "Shortcut key" field.

### macOS

1. Use Automator to create a Quick Action that runs the Python script.
2. In System Preferences > Keyboard > Shortcuts > Services, assign a keyboard shortcut to this Quick Action.

### Linux

The process varies depending on your desktop environment. Generally, you can add a custom keyboard shortcut in your system settings that runs the command:

```
python /path/to/this/repo/main.py
```
