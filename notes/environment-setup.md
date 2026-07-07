cat > notes/environment-setup.md <<'EOF'
# Environment Setup - Week 1

## Git identity

git config --global user.name "NeuralWordsmith"
git config --global user.email "deepictd.de@gmail.com"
git config --global init.defaultBranch main
git config --global --list

Result:
user.name=NeuralWordsmith
user.email=deepictd.de@gmail.com
init.defaultbranch=main

## SSH authentication

ssh-keygen -t ed25519 -C "deepictd.de@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com

Result:
Hi NeuralWordsmith! You've successfully authenticated, but GitHub does not provide shell access.

## Repository setup

mkdir ml-career-operating-log
cd ml-career-operating-log
git init
mkdir weekly evidence notes
touch README.md
touch weekly/week-01.md
touch evidence/.gitkeep
touch notes/environment-setup.md

## Global Python gitignore

mkdir -p ~/.config/git
git config --global core.excludesfile ~/.config/git/ignore

Global ignore entries:
__pycache__/
*.py[cod]
.venv/
.env
.ipynb_checkpoints/
.pytest_cache/
.mypy_cache/
.ruff_cache/
.DS_Store

## Shell exercise

mkdir -p shell-practice/raw shell-practice/processed
echo "cloud git shell ml engineering" > shell-practice/raw/week1.txt
echo "temporary note" > shell-practice/raw/temp.txt
mv shell-practice/raw/week1.txt shell-practice/processed/week1.txt
grep -R "git" shell-practice
find shell-practice -name "*.txt"
rm shell-practice/raw/temp.txt
rm -r shell-practice

Result:
shell-practice/processed/week1.txt:cloud git shell ml engineering
shell-practice/processed/week1.txt
shell-practice/raw/temp.txt

## Mistakes / corrections

- No setup mistakes recorded yet.
EOF