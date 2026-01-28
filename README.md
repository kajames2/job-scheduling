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
In your browser open the file: `instructions/instructions_base.html`

In addition to the above instructions, know that in the particular experiment you'll be doing, you will lose $0.72 each day.  This is the unavoidable fixed cost of keeping the business running.  It will always be $0.72/day, regardless of how many workers you have working.

# To run the experiment
```
cd software
otree devserver
```

1) navigate browser to: `localhost:8000`
2) click `inv_experiment`
3) click on the "Session-wide" link

# Final Score Evaluations

| Earnings | Evaluation | Note |
|----------|------------|------|
|   $24    |    Meh     | Average Chapman undergrad score (2nd attempt with same seed, 2 days apart) |
|   $38    |    Good    | |
|   $44    | Very Good  | Around the highest we saw among Chapman undergrads |
| $45.50   |   Kevin    | What I earned my first time on this seed |
| $48.22   | Also Kevin | What I earned playing right before uploading this.  I was out of practice, but also remembered some of the ebbs and flows of this random seed |
| $52--$54 |  ~Optimal  | My estimate to what optimal play would earn |
|   $74    | Cheating Max | Approximately the most you could earn if you knew what all random draws would be |
