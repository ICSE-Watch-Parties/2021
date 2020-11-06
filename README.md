# Watch Parties Website for ICSE 2021

Welcome to the repository of the website 😊

## Submit announcement for a watch party

If you plan to host a watch party at your group, please also add it to this website!  
This way we can show the world how many watch parties are happening and your program can inspire others 😄  
You don't need to accept any additional/external visitors to advertise your party here 🙂  

To add your announcement:
1. Fork this repository.
1. Duplicate the [announcement template](_watch_party_announcements/Template%20Continent/Example%20Country/template-city-organization.md) and give it a name describing your party.
1. Put it in the correct continent / country folder. Please add new ones if necessary! We use the folder structure to order the list of watch parties.
1. Fill your template with all the information you have. It does not have to be complete, even a simple "Intent to throw a watch party" is enough 🙃
1. Open a pull request back to the repository! If you want to add anything to your announcement (more detailed planning, note that no new attendees can register) send us another pull request!

We only do a rough checking of the PR to make sure they don't break the website's structure.  
The organizers of every watch party are responsible to ensure their watch party adheres to the [general watch party guidelines](https://icse-watch-parties.github.io/2021/watch-party-guidelines.html) and local regulations.

## Local development
To build the website locally you need ruby, bundler and jekyll.
You can check out the installation instructions on the [jekyll website](https://jekyllrb.com/docs/)

You can run the website locally with:
```
bundle exec jekyll serve --livereload --config _config.yml,_config_local.yml
```
