# Tips-Tricks
Some useful shortcuts 


Hi All,

Thought of sharing some useful shrotcut related to development (Eclipse,GitHub,gEdit etc...)

Git config
-----------------------------------------------------------------------------------------------------------------------------

[user]
	name = Vaibhav K
	email = vaibhav.kripala@gmail.com
[color]
	status = auto
	branch = auto
	diff = auto
[alias]
	st = status
	ci = commit
	co = checkout
	rb = rebase -i
	cpk = cherry-pick
	pull = pull --rebase
 	slog = log --oneline --decorate=short
	glog = log --graph --pretty=format:'%Cred%h%Creset %an: %s - %Creset %C(yellow)%d%Creset %Cgreen(%cr)%Creset' --abbrev-commit --date=relative
  assume   = update-index --assume-unchanged
  unassume = update-index --no-assume-unchanged
  assumed  = "!git ls-files -v | grep ^h | cut -c 3-"
[core]
	autocrlf = input 
	ignorecase = false
	filemode = false
	excludesfile = /home/vaibhav/.gitignore_global
	safecrlf = false
[branch]
	autosetuprebase = always
	autosetupmerge = true
[push]
	default = tracking
-------------------------------------------------------------------------------------------------------------------------------------

Vaibhav K
