# Gophish
For setting up the tools I did the setup in kali environment.

- sudo apt update
- wget https://github.com/gophish/gophish/releases/download/v0.12.1/gophish-v0.12.1-linux-64bit.zip
- unzip gophish-v0.12.1-linux-64bit.zip

It unzipped the file and it gave me a executable file gophish, which was on readme only, so i had to change it to a executable file.
- chmod +x gophish
  
Then run the executable file.
- sudo ./gophish

# NGROK
- wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
- unzip ngrok-stable-linux-amd64.zip
- chmod +x ngrok
- ngrok http 80

Ngrok is a tool that creates a secure tunnel from your local machine to the internet. Essentially, it exposes a local server (running on your computer) so that it can be accessed via a public URL.

This way my Phishing landing page can be accessed by users who are not in my network.
