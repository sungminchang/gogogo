# gogogo
experiments with golang


From https://github.com/codebudo:

You might want to add

    export GOROOT=/usr/local/go
    export GOPATH=$HOME/go 
    export GOBIN=$HOME/go/bin 

to your .bash_profile if you're experiencing problems with setting $GOPATH.

I added 

    export PATH=$GOPATH/bin:$PATH
    
between the second and third lines to my own .bash_profile.
