# CI/CD with SourceLair, CodeShip and Heroku

Create a nice integration between SourceLair for developing, CodeShip Jet testing and Heroku for deployment.

You can find the complete tutorial at: https://www.sourcelair.com/blog/articles/119/ci-cd-codeship-heroku

## Getting started

The easiest way to get started is by visiting https://lair.io/stacks/django-postgres-ci-cd and starting a new SourceLair project with a single click.

This will do the following on your behalf:

1. create a new SourceLair Django 1.9 project
2. clone the code from this Git repository
3. install all the needed dependencies using `pip install -r requirements.txt`

## Following the tutorial

The repository contains different branches, used as checkpoints for following out the tutorial.
If you'd like to see the final example, just `git checkout -f step/final`

## Tips

- **open files** using QuickOpen (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> if you are on a Mac)
- **edit your files** using SourceLair's fully-featured editor
- **install pip dependencies** using the command palette (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> if you are on a Mac)
- **run commands** (e.g. `./manage.py migrate`) in SourceLair's Linux terminal
- in case you **need any help** contact SourceLair using the _envelope_ icon in the sidebar or send an email to [support@sourcelair.com](mailto:support@sourcelair.com)

## License

The code provided in this template is licensed under the MIT License. For more information check out the [LICENSE](LICENSE) file.
