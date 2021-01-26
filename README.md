# btbatw.org website

## Local build instructions

### Install dependencies

```bash
gem install jekyll bundler
bundle install
```

### Run development server

```bash
bundle exec jekyll serve
```

### Build files for publication

```bash
bundle exec jekyll build
```

### Add twitter bootstrap 4
Refer to [this](https://simpleit.rocks/how-to-add-bootstrap-4-to-jekyll-the-right-way/#fnref:safe-mode)

### Site structure reference
[Github on demand training](https://github.com/github/training-kit)







### For macOS Big Sur M1 Mac users:
Have to install rails first:
```bash
sudo gem install rails
```

And then install jekyll
```bash
sudo gem install jekyll bundler
```

And then do some tricks to make jekyll executable
```bash
sudo gem uninstall sassc
gem install sassc --user-install
gem install --user-install sassc -- --disable-march-tune-native

sudo arch -x86_64 gem install ffi
brew install gpg2
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
\curl -sSL https://get.rvm.io | bash -s stable --rails
rvm use 3
sudo gem install jekyll bundler

cd /Path/To/Your/Sites/
arch -x86_64 jekyll new <foldername> # Here I would suggest to use 'BTBA'
cd <foldername> # Here I would suggest to use 'BTBA'

bundle install
bundle add webrick
```

And then clone the BTBA site from this present git (https://github.com/oro160/BTBA.git)
to /Path/To/Your/Sites/<foldername> # Here I would suggest to use 'BTBA'

And then run the server
```bash
bundle exec jekyll serve
```

Then in your browser just go to http://127.0.0.1:4000/ and it really should be running
