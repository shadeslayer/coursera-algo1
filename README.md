## Setup for ZSH/BASH ##

You should add the following lines to your ~/.bashrc or ~/.zshrc :

    setup_coursera()
    {
      export CLASSPATH="YOUR/PATH/HERE"
      test -r $CLASSPATH/algs4/bin/config.sh && source $CLASSPATH/algs4/bin/config.sh
    }

## Assignments ##
You can put your assignments in the assgiments folder and they'll never be pushed 
