https://www.learnopencv.com/install-dlib-on-macos/

Install Dlib on MacOS >= 10.11 & XCode >= 8

Step 1: Install OS libraries
brew cask install xquartz
brew install gtk+3 boost
brew install boost-python3

Step 2: Install Python 2 and/or Python 3
brew install python python3
brew link python
brew link python3
# check whether Python using homebrew install correctly
which python2   # it should output /usr/local/bin/python2
which python3  # it should output /usr/local/bin/python3
# check Python versions
python2 --version
python3 --version

Step 3: Install Python libraries
# Install virtual environment
pip install virtualenv virtualenvwrapper
echo "# Virtual Environment Wrapper"
echo "source /usr/local/bin/virtualenvwrapper.sh" >> ~/.bash_profile
source ~/.bash_profile
############ For Python 2 ############
# create virtual environment
mkvirtualenv facecourse-py2 -p python2
workon facecourse-py2
# now install python libraries within this virtual environment
pip install numpy scipy matplotlib scikit-image scikit-learn ipython
# quit virtual environment
deactivate
############ For Python 3 ############
# create virtual environment
mkvirtualenv facecourse-py3 -p python3
workon facecourse-py3
# now install python libraries within this virtual environment
pip install numpy scipy matplotlib scikit-image scikit-learn ipython
# quit virtual environment
deactivate

Step 4: Install Dlib
Step 4.1: Compile C++ library
brew install dlib
Step 4.2: Compile Python module
############ For Python 2 ############
workon facecourse-py2
############ For Python 3 ############
workon facecourse-py3
pip install dlib
deactivate
