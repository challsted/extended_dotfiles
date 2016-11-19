# What this is for

Just a place for me to share my current non base utility "dot files" with everyone and a easy way to make sure I stay in sync acrosst multiple devices.  
These are for things such as [i3wm][i3wm_website], [BSPWM][bspwm_website], or [NeoMutt][neomutt_website], my plan is to seperate out base utilitys into my main [Dotfiles Repo][dotfiles_repo] and random other things into here.  
Feel free to take any or all of them, tweak them to your desire and distribute them!  

## Pre-Installation

Obviously, if you want to use any of the tools below, you will need to have it installed, any of its dependencies, as well as any extras I list and there dependencies.  
Before you can use any of the stuff here, you will need to have the following installed:  
* `git`

Now you will need to clone my repository, I suggest that you put it inside of a folder under your home directory,  
I personally use a folder called "git" but this is up to you, and optional.  
If you want to make a folder first you can do this:
* `mkdir -p ~/git && cd ~/git`

If you created the folder make sure you cd into it, then run the next command
* `git clone https://github.com/challsted/extended_dotfiles.git`

## NeoMutt Installation
**NeoMutt**

**Packages**
* `mutt`

**You will need to run this to use my config:**
* `ln -s ~/git/dotfiles/mutt ~/.mutt`
* `ln -s ~/git/dotfiles/MAIL/procmailrc ~/.procmailrc`
* `ln -s ~/git/dotfiles/MAIL/msmtprc.. ~/.msmtprc`
* `ln -s ~/git/dotfiles/MAIL/fetchmailrc ~/.fetchmailrc`

**Notes:**
* Please read the [README.md][NeoMuttREADME] file located inside of the mutt folder, this doc will eventually become my Mutt Wiki Page, but its easier to edit as I'm working on it via the readme for now.

##i3 Instalation
**COMMING SOON**

##BSPWM Instalation
**COMMING SOON**

## Contact the author

Professional  Twitter [@hackinginfo][tweet]  

[MUTT_WIKI]:       ../../wiki/Mutt
[i3_WIKI]:         ../../wiki/i3 

[i3wm_website]:    http://i3wm.org/
[bspwm_website]:   https://github.com/baskerville/bspwm
[neomutt_website]: https://github.com/neomutt/neomutt
[dotfiles_repo]:   https://github.com/challsted/dotfiles

[NeoMuttREADME]:   https://github.com/challsted/extended_dotfiles/blob/development/mutt/README.md

[tweet]:           https://twitter.com/MaSammchs
