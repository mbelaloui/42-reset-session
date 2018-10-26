# 42-reset-session

<h1>to reset session :</h1>
  <p>Reset : `touch ~/.reset`</p>
  <p>Reset library : `touch ~/.reset_library`</p>
  <p>restart session<p>

<h1>to get good version of brew:</h1>
  <p>curl -fsSL https://rawgit.com/kube/42homebrew/master/install.sh | zsh</p>
  <p>restart terminal<p></br>
 
<h1>to install valgrind</h1>
  <p>brew install valgrind</p>
  <p>restart terminal<p></br>
 
  <p>if it does not work, it might be necessary to add this line to the .zshrc</p>
  <p>alias valgrind='~/brew/Cellar/valgrind/....../bin/valgrind'. Fill the ...... with the version</p>
  <p>restart terminal<p></br>

<h1>clean up session</h1>
<p>alias clearbak='cd ~/Library/ && echo "\nBefore: " && du -sh ~/Library/ ; rm -rf *_bak_* ; echo "\nAfter: " ; du -sh ~/Library/ ;  cd -'</p>
