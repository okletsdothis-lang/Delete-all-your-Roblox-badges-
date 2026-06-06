#Delete all your Roblox badges
A lightweight Python script for Google Colab that automates the removal of badges from your Roblox inventory. This tool is useful for cleaning up badge clutter or resetting your profile's badge list.

#🚀 Features
Automated Deletion: Fetches and deletes all badges associated with your account.
Rate Limit Handling: Automatically waits and retries if Roblox applies rate limits.
CSRF Protection: Handles Roblox's security tokens automatically.
Platform Support: Includes instructions for obtaining tokens on both Desktop and iOS (Orion Browser).
#🛠️ How to Use
Open the .ipynb file in Google Colab.
Follow the instructions in the notebook to retrieve your .ROBLOSECURITY cookie.
Paste your cookie into the configuration variable in the code cell.
Run the cell and wait for the "Inventory cleared!" message.
#⚠️ Security Warning
NEVER share your .ROBLOSECURITY cookie with anyone. It is a sensitive token that gives full access to your Roblox account. This script is intended for personal use only. Use it at your own risk.

#📝 Requirements
A Google account (to run on Colab).
