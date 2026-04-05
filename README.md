# CS-GY 6903

Applied Cryptography with Z Chen at NYU

## Project 4 - Understanding Cryptographic Hashes Through Experiments

**Group members:**
- Matthew Bentz (mb9661@nyu.edu)

~~- Darren Tahe (dt2607@nyu.edu)~~
~~- Srikanth Akella (ta2728@nyu.edu)~~
~~- Matthew Mobijohn (mm7655@nyu.edu)~~

## Project Outline

[Project-CrytoHash.pdf](Project-CrytoHash.pdf)

## Usage

Create local/remote git repo
```
# create locally
git init

# if your creds are split per repo/folder like mine
git config user.email "m@tthewbentz.dev"
git config user.name "Matthew Bentz"

# create first commit
git add . && git commit -m "initial commit"

# given you have GitHub CLI
gh repo create cs-gy-6903-project4 --public --source=. --remote-origin --push
```

Create a venv

`python -m venv .venv`

Activate python venv

`source .venv/bin/activate`

Deactivate python venv

`deactivate`

Install requirements

`pip install -r requirements.txt`

Convert ipynb to PDF

`jupyter nbconvert --to pdf proj4.ipynb`

Commit changes

`git add . && git commit -m "message" && git push`