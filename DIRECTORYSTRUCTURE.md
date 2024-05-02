<h1 align = "center">Directory Structure</h1>

<div align = "justify">

. A high level directory overview is as follows:

```
├───config          : store all configuration files/functions
│
├───data            : responsible for all data handling, or contains raw data
│   └───processed   : contains processed data (like combined/normalized dataframes, tables, etc.)
├───docs            : responsible for all docs, reports and ppts
etc.)

│
├───logs            : repository to contain log files, can also be saved in `/path/to/directory`
│
├───examples        : contains boilerplate notebook for EDA and quick data understanding/explanations
│
├───output          : directory responsible for all output files, useful for code development
│   ├───images      : save output images
│   └───savedmodels : save trained model files
│
├───src             : source directory
│   ├───agents      : define agents for any rnn application
│   ├───engine      : provides a suit of machine learning analytic functions
│   └───models      : directory containing model definations
│
├───static          : other important/useful resources required in the project
│   ├───fonts       : store additional fonts, maybe used in documentations
│   ├───images      : store explanatory images, maybe used in documentations and/or ipynb/markdowns
│   └───logo        : setup a project logo, purely useful for front layer applications can be safely ignored
│
└───utilities       : utilities directory containing functions and/or submodules, check readme for more information
```

If some directories/files are missing is because don't apply to this case

</div>
