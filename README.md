# palenight-dots
my gentoo linux palenight dotfiles

# installation

**NOTES:**
- $$ means the absolute path to this repo on your local machine, e.g. /home/username/palenight-dots. 
- ~ means the absolute path to your home directory, e.g. /home/username
- when going through each file, make sure that all file locations and dependencies are correct
- USING RELATIVE PATHS MAY CAUSE ISSUES WHEN SYMLINKING!!
- these dots are no where near complete. if you have a bugfix/have improved on something, please do create a PR!

### kitty terminal
`ln -s $$/kitty/kitty.conf ~/.config/kitty/kitty.conf`

### zsh
`ln -s $$/zsh/zshrc ~/.zshrc`
`ln -s $$/zsh/starship/starship.toml ~/.config/starship.toml`

### kde plasma
install the quarter tiling kwin add-on.

(incomplete) colour scheme provided in this folder. i based it off a onedark scheme i found, so some of the colours may be from onedark.

my "round corners" kde global theme fork is included. it is themed with palenight colours.

my kde shortcuts are also provided in case you are interested.

### portage
this step is only useful if you use gentoo linux. my portage settings are provided.

### wallpaper
wallpaper is provided.

# todo (once i get my pc back from repairs)
- nvim config 
- zathura config
- ncmpcpp
- lots of other things :DDD
**as you can tell, this repo is kind of a mess. just wanted to release my current dots before i send my laptop in for repairs and it (probably) gets wiped. 
