# CleanXcode

## 1. Reset Simulator content and settings

- Launch Simulator
- ***Device***
→ ***Erase All Content and Settings...***

## 2. Delete derived data

Delete content of: `~/Library/Developer/Xcode/DerivedData/`

In the terminal:
```zsh
rm -rf ~/Library/Developer/Xcode/DerivedData/*
```

You can create an alias, if you have ZSH w/ OhMyZsh you can type on your terminal: 

```zsh
echo "alias cleanXcode='rm -rf ~/Library/Developer/Xcode/DerivedData/*'" >> ~/.zshrc
```

Then delete the content of DeriveData folder by typing on the terminal :

```zsh
cleanXcode
``` 
