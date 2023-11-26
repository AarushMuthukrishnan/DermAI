# DermAI

## Description
An AI Powered Chatbot for Skin Cancer.

## Table of Contents
- [Privacy](#privacy)
- [Copyright](#copyright)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Privacy
The default language for the app and the conversation below is English, unless a specific language name is mentioned in the conversation.

## Copyright
&copy; 2023 Aarush Muthukrishnan. All rights reserved.

## Setup
1. Clone the repository.
2. Install Node.js.
3. Go to Firebase and create a new project.
4. In Firebase, setup Google Authentication and make localhost:8080 an authorized domain.
5. Go to the Google Cloud Console and create an account with a free trial plan or billing account.
6. Choose the project that has the name as your Firebase project.
7. Go to DialogflowCX and choose your Google Cloud/Firebase project.
8. Create a new Dialogflow CX agent and publish it with the side panel option.
9. Follow the instructions on [index.html](https://github.com/AarushMuthukrishnan/DermAI/blob/main/www/index.html), [chat.html](#chat.html), and [account.html](#account.html) to add your Firebase/DialogflowCX credidentials.

## Usage
1. Ensure that all the setup steps above have been followed and all the files have the correct name and are in the same directory
2. Make sure the directory in your console matches the directory of your project
3. Run `npx http-server` to start the web server 
4. On your preferred browser, go to `localhost:8080` to view the web app

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
