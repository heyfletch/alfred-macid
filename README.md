alfred-macid
====================

Alfred workflow for the MacID app

NOTE: This is still completely configured for the Knock app as forked from @saschaeggi. I have not changed any code here yet.

After installing, edit the Alfred Workflow applescript and just replace:

```
on alfred_script(q)

  do shell script "open knock://lock"
end alfred_script

```

With 

```

on alfred_script(q)
  do shell script "open macid://lock"
end alfred_script

```

And it will work MacID to lock your Mac with Alfred. 

Download: https://github.com/saschaeggi/alfred-knocktounlock/raw/master/Knocktounlock%20App.alfredworkflow

# Version History

- 0.1 Inital Version
- 0.2 Use the offical API to lock the screen

# How to install

1. First download it from [here](https://github.com/saschaeggi/alfred-knocktounlock/raw/master/Knocktounlock%20App.alfredworkflow)

2. Double-click the file "Knocktounlock App.alfredworkflow"

# How to use

Fire up Alfred and type in "lock"
Or setup an Hotkey in the Alfred workflow (Alfred -> Workflows -> Knocktounlock App)

![Alt text](/howto/hotkey.png "Setup hotkey")
