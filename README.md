# n1moe1n.github.io

## install jekyll 4 gibthub pages
### ubuntu
> https://jekyllrb.com/docs/installation/ubuntu/

```
sudo apt-get install ruby-full build-essential zlib1g-dev  

echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc 
echo 'export GEM_HOME="$HOME/gems"' >> ~/.zshrc 
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.zshrc 
source ~/.zshrc 

gem install jekyll bundler
```

### set up the page
> https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll

```
cd ~/git/github/n1moe1n.github.io
jekyll new docs
cd docs
bundle exec jekyll serve # test
```

