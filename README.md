# sound-decoder
## How to use
### Installation
1. Clone the repository, to do that, make sure you have installed <a href="https://www.linode.com/docs/development/version-control/how-to-install-git-on-linux-mac-and-windows/">github</a> on your system (or use the online interface to download the source code). If you have installed git, to check if you really did, on your terminal write down:

    `git --version` 
    
    Should appear something like:
    
    > git version 2.20.1

2. Make sure you have installed <a href="https://pip.pypa.io/en/stable/installing/">pip</a> and <a href="https://realpython.com/installing-python/">python3</a>. To check, on your terminal write:

    `pip --version`
    
    Should appear something like:
    
    > pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)

3. In you terminal, surf to the `.../sound-decoder` directory that you've cloned and install the dependencies for this project. To do that, run the command:

    `pip install requirements.txt`
    
        Now you have all you need!
    
### Experimantation

1. Create a directory inside `experimentos` like ``exp1``, and inside it, an image you want to extract the vectors.

2. Now, in your terminal, you just need to get inside your `.../sound-decoder` directory and run:

    `python3 run.py`
    
    or if your default python is 3.X

    `python run.py`
    
        Have fun!
