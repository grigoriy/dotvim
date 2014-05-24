Installation:

	git clone git://github.com/grigoriy/dotvim.git ~/.vim

Create symlinks (for versions of vim where '.vim' is not in default runtimepath):
	
	ln -s ~/.vim/vimrc ~/.vimrc

Switch to the '~/.vim' directory and fetch submodules:

	cd ~/.vim
	git submodule init
	git submodule update

---------------------------------------------------------------------------------

For details:

http://www.vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen
