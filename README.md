### activate the virtual env on windows

in the folder containing the script activate.bat (link)[https://stackoverflow.com/questions/17582778/how-to-execute-a-bat-file-from-cygwin-bash-that-uses-the-windows-find-command]
`chmod +x activate.bat`

# launch the back end
1. first, activate the venv

2. a. enter `flask run` from API folder

2. b. enter `npm run start-api` from root folder to start the api






The --no-debugger option that I added in the command also deserves a mention. Since this Flask backend is strictly an API server, we will never be serving complete pages, so having the browser-based debugger enabled serves no purpose, as it's just going to mess up the JSON responses that the API returns. You will see stack traces of your errors in the terminal.