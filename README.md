Git-tips
========

Some git tips

1 git auto completion skill

* cd bash/
* cp git-completion.bash ∼/.git-completion.bash
* add this command into ~/.bashrc

source ~/.git-completion.bash

* source .bashrc

Then you can git co<click two tab button>, which will list the commands started with co.
Example:

* $ git co<tab><tab> 
	commit config
	

2 alias

* $ git config --global alias.co checkout 
* $ git config --global alias.br branch
* $ git config --global alias.ci commit
* $ git config --global alias.st status		
* $ git config --global alias.unstage 'reset HEAD --'
* $ git config --global alias.last 'log -1 HEAD'

3 gitk

* Download the official git package for Mac from http://git-scm.com/download/mac
* alias gitk='/usr/local/bin/gitk'

You can put this line in the ~/.bash_profile

* $ git config --global alias.visual "!gitk"