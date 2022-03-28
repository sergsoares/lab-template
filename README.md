# Lab machine

Ansible scripts to initialize a Lab machine.

===

Install initial dependencies as ansible and galaxy roles
```
$ bash scripts/setup
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