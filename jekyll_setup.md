## Install jekyll

```bash
sudo apt install ruby-full build-essential zlib1g-dev
```

## Add environment varible to your ~/.bashrc

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## finally install jekyll and bundler
```bash
gem install jekyll bundler
```
## in repo director force to create required files
```bash
jekyll new --skip-bundle --force .
```

## need to change Gemfile, comment jekyll and uncomment github-pages. Also update new version

## then run 
```bash
bundle install
git ```