# Lab machine

Ansible scripts to initialize a Lab machine.

===

Prepara the environment with dependecies
```
bash scripts/setup
```


Single script to install in a new instance.
```
git clone https://github.com/sergsoares/lab-template;cd lab-template;sudo bash scripts/run-all
```

Then it is possible run 3 Modes (essential, gui, cli)
```
Install all ansible modules available
$ bash scripts/run-all

Install all only essential modules available
$ bash scripts/run-essential

Install all only CLI modules available
$ bash scripts/run-cli

Install all only  GUI modules available
$ bash scripts/run-gui


```

===

## Todo

- Fix "ansible-galaxy install -r requirements.yml" usage
- Retry for binary downloads
- Fix Chrome Version
- Added Chromium

