# Oasis
![346274774-d27be0f4-e8cd-443a-a067-f7fe3abdb6be](https://github.com/user-attachments/assets/e9c1fa5a-2d9f-4797-9679-b11ae284a28c)

Welcome to Oasis Terminal! This README will explain step by step the installation and usage of update_token.js and oasis_terminal.js scripts on Ubuntu system.

# Requirements

Before you start, make sure the following prerequisites are installed on your Ubuntu system:

Node.js
npm

If you do not have an Oasis.ai account, register from the link below:

[Oasis](https://r.oasis.ai/d63479081fe2ca10)

# Let's Run the Script
```
wget https://raw.githubusercontent.com/ruesandora/Rivalz/main/oasis.sh
```
Let's grant permissions and run it.
```
chmod +x oasis.sh
./oasis.sh
```
Let's create a screen:
```
screen -S oasis
```
Change to the oasis directory:
```
cd oasis
```
Run the following command to run the update_token.js script:\
```
node update_token.js
```
Follow the prompts to enter your email, password, and client name. The script will log in, get the extension token and create the database.js file with this token.

# Running Oasis Terminal
Make sure you are still in the oasis directory in the terminal.
Run the following command to start Oasis Terminal:
```
node oasis_terminal.js
```
Let's detach from the screen with CTRL A + D. You are now ready! I wish you happy points earning with Oasis Terminal!

[source](https://github.com/ruesandora/Rivalz/blob/main/OasisTerminal.md)



