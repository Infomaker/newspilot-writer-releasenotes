# Release notes for Naviga Writer projects

This project is responsible for generating the site at https://infomaker.github.io/newspilot-writer-releasenotes

Pages will be added by jenkins in the `_project-releasenotes` directories.

These pages are added to the site in the `_config.yml` and `_config-dev.yml` configuration files, as collections.


## How to run locally

Jekyll is built in Ruby and requires bundle and jekyll to start a local environment.


    git clone git@github.com:Infomaker/newspilot-writer-releasenotes.git
    cd NPWriterDevelopers
    gem install jekyll bundler
    bundle install
    bundle exec jekyll serve --config _config-dev.yml

This local server should be at localhost:4000


## How to add additional projects

1. Start with creating a new directory using `_myproject-releasenotes` syntax. Add a `.gitkeep` file in the directory.
2. Edit `_config.yml` and `_config-dev.yml` files and add a collection named: `myproject-releasenotes`.
3. Edit the `index.md` file and iterate through the new collection `{% for note in site.myproject-releasenotes reversed %}`

Next thing is to edit the release note generation configurations in the [https://bitbucket.org/infomaker/writer-releasenotes-generator] project.

The last thing is to add the new project to the `jenkins` build in the project `generate-release-notes` project.
