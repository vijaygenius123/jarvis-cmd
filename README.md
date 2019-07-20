# JARVIS

Is a CLI to make your life easier. It was started as a tool to manage working on multiple projects.Jarvis should help you easily open your work environment and start developing. You will no more need to remember where your project working directory is or open multuple terminals to fire up dependencies.
If You have an OpenProject as your project management tool then you should be able to list and update your tasks directly using the cli.

## Installing

You can install `jarvis` using `pip install jarvis-cmd`, after which you should be able to run `jarvis` from the `cmd` or `terminal` of your choice.

## Functionality

### Working

1. `jarvis configure` -> Setup up the OpenProject configuration. It will ask you two things

- Base URL Example -> https://www.openproject.org/
- API Key -> You can generate your apikey by
  - Open your OpenProject instance
  - Go to My account page
  - Click on click on the Access token link on the Side Nav
  - Generate the token from the API row

2. `jarvis tasks` -> List tasks that are not closed and assigned to you on OpenProject
3. `jarvis task <set-to> <id>` -> Update the WorkPackage with <id> on OpenProject to the status <set-to>. <set-to> can be one of the following values [work|close|hold|pass|fail|testing|done|new]

### In Progress

1. `jarvis create <project-name>` -> To create a project and store the steps to run it
2. `jarvis open <project-name>` -> To automatically run the steps specified when you created the project

### Thanks

If you like this project you can give a star on GitHub.

  <iframe src="https://ghbtns.com/github-btn.html?user=vijaygenius123&repo=/jarvis-cmd&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>
