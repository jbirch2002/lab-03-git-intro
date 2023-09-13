This is lab 03...
It's about creating local and remote repositories, and saving new data to these repositories.

* show your remote url…
* add it to your README file and save it!
* commit your change…

origin  https://github.com/jbirch2002/lab-03-git-intro.git (fetch)
origin  https://github.com/jbirch2002/lab-03-git-intro.git (push)

* set your remote url to some url that does not exist (change the lab  number to 7, for example)
* push the change to your remote
* note the error!

git remote set-url origin https://github.com/jbirch2002/lab-07-wizard-fireball-lesson.git


remote: Repository not found.
fatal: repository 'https://github.com/jbirch2002/lab-07-wizard-fireball-lesson.git/' not found

* set your url appropriately
* attempt to push your change again

git remote set-url origin https://github.com/jbirch2002/lab-03-git-intro.git

$ git push origin master
Everything up-to-date
