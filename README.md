# README

# Framework of NN

## The content of Save and Load method

The autosave of the Framework will save a 'best.pt' file at './models', and the path should has the context including folder 'models' and folder 'models/autosave'
```
- father folder
    |- models
    |  |- autosave
    |  |  |- autosave_Gen1.pt
    |  |  |- autosave_Gen2.pt
    |  |  |- ...
    |  |
    |  |- best.pt
    |
    |- NN.py
```