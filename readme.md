Put the .github folder in your project and the workflows should show up in the actions tab of your repository.

For things like getting the unity license with the activation workflow, check out https://game.ci/ and follow the documentation.

You can edit things like the projectName in the workflow to fit your own project. Otherwise it will call the build just "myProjectName". The project name corresponds to what the game .exe will be called.
Check out the github actions docs for more info.