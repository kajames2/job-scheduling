# Installation

When cloning, be sure to get the reveal.js submodule
```git clone --recurse-submodules```
or if already cloned
```git submodule update --init --recursive```

get python setup
```
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r software/requirements.txt
```

# Viewing the experiment instructions
In your browser open `instructions/instructions_base.html`

# To run the experiment
```
cd software
otree devserver
```

1) navigate to `localhost:8000`
2) click `inv_experiment`
3) click on one of the Session-wide links
