# VK-chat-mini-observer


[![GitHub Follow](https://img.shields.io/github/followers/mykytashch?style=social)](https://github.com/mykytashch)
[![GitHub Stars](https://img.shields.io/github/stars/mykytashch/SynchroMessage)](https://github.com/mykytashch/SynchroMessage/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/mykytashch/SynchroMessage)](https://github.com/mykytashch/SynchroMessage/network)



VK chat mini-observer is a minimalist chat monitoring demo consisting of a Python server and a Chrome extension. The server, built with Flask, logs messages received from the extension via a '/store_response' POST request. The extension, using JavaScript, observes VK chat using MutationObserver, captures and sends new messages to the server using a Fetch API POST request.

Specifications:
1. Python Server:
   - Flask-based Python server.
   - Single '/store_response' route for logging messages.
   - Utilizes the logging module for storage.
   - All messages are displayed in the console

2. Chrome Extension:
   - JavaScript-based Chrome extension.
   - Uses Fetch API for server communication.
   - Observes VK chat with MutationObserver.
   - Sends captured messages to the server using POST request.

Key Facts:
- Both server and extension are concise, with 24 lines of code each.
- Extension script is only 50 characters long.
- Server uses Flask and logging modules.
- Extension employs Fetch API for server communication.
- VK chat observation relies on MutationObserver.

The demo repository includes necessary files and Docker configurations for easy setup. This minimalistic demo lays the groundwork for advanced chat monitoring and analysis systems.


## Author

VK chat mini-observer is developed by Mykyta Shcheholevatyi
