# Preliminary
## Aim of site
The aim of this website is to create an aggregator for flight booking for a user to check two different websites for prices at once.

## Technologies
- Python3
- Gitpod
- Django
- HTML5
- CSS3
# Main Section
## Procedure
pip3 install django
django-admin startproject flight_aggregator .

remove this pattern from File -> Preferences -> Settings -> Search bar -> search for "files.exclude" :
```**/.git```
ensure to remove from all 3 subtabs under search bar
### Fix .gitignore not showing in explorer
In Settings: Tick box under:
Explorer: Exclude Git Ignore
Controls whether entries in .gitignore should be parsed and excluded from the explorer. Similar to Files: Exclude

## Continue log
python3 manage.py runserver
python3 manage.py migrate
python3 manage.py createsuperuser
git status
git remote -v
# References
- This repository uses the following repository as a template: [Code-Institute-Org / gitpod-full-template](https://github.com/Code-Institute-Org/gitpod-full-template)
- This was an earlier attempt at making the website using VSCode Desktop instead of Gitpod [Coder731 / Portfolio-Project-5](https://github.com/Coder731/Portfolio-Project-5)