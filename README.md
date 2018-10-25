# 42-reset-session

to reset session :
  Reset : `touch ~/.reset`
  Reset library : `touch ~/.reset_library`
  restart session

to get good version of brew
  mkdir homebrew && curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew
  alias brew="~/homebrew/bin/brew"
  
to install valgrind
  brew install valgrind
  alias valgrind="~/homebrew/Cellar/valgrind/3.13.0/bin/valgrind"
 
to install oh_my zsh
  sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
