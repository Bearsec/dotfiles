```
apt-get update;
apt-get -y install tmux git;
git clone https://github.com/Bearsec/dotfiles.git;
cp -f ./dotfiles/.bashrc /root/.bashrc;
cp -f ./dotfiles/.tmux.conf /root/.tmux.conf;
rm -rf ./dotfiles;
echo "Done!"
```
