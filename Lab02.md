## Lab 02

- Name: Saraswathi Nagendiran
- Email: nsaras.1981@gmail.com

## Part 2 Answers

1. Add a file for tracking:
touch Lab02.md
git add Lab02.md

2. Commit changes:
commit

3. Sync local commits with GitHub:
git push

## Part 3 Answers

1. `ssh` before configuring `config` file: ssh -i ceg2350-key.pem ubuntu@52.87.126.190
2. HostName: 52.87.126.190
3. User: ubuntu
4. IdentityFile: ceg2350-key.pem
5. `~/.ssh/config` contents:
Host aws
    HostName 52.87.126.190
    User ubuntu
    IdentityFile /home/sarasiva/ceg2350-key.pem

6. `ssh` after configuring `config` file: ssh aws
