# Environment Setup - Week 1  
  
## Git identity  
  
```bash  
git config --global user.name "NeuralWordsmith"  
git config --global user.email "deepictd.de@gmail.com"  
git config --global init.defaultBranch main  
git config --global --list
```

## SSH authentication

```
ssh-keygen -t ed25519 -C "deepictd.de@gmail.com"eval "$(ssh-agent -s)"ssh-add ~/.ssh/id_ed25519cat ~/.ssh/id_ed25519.pubssh -T git@github.com
```

Result:

```
Hi NeuralWordsmith! You've successfully authenticated, but GitHub does not provide shell access.
```

## Repository setup

```bash
mkdir ml-career-operating-log
cd ml-career-operating-log
git init
mkdir weekly evidence notes
touch README.md
touch weekly/week-01.md
touch evidence/.gitkeep
touch notes/environment-setup.md
```

## Shell exercise

```
mkdir -p shell-practice/raw shell-practice/processed
echo "cloud git shell ml engineering" > shell-practice/raw/week1.txt
echo "temporary note" > shell-practice/raw/temp.txt
mv shell-practice/raw/week1.txt shell-practice/processed/week1.txt
grep -R "git" shell-practice
find shell-practice -name "*.txt"
rm shell-practice/raw/temp.txt
rm -r shell-practice
```

## Mistakes / corrections

- None recorded yet.  
    EOF