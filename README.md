Run composer with dependencies required by Symfony2 (php5-intl)

> docker run -i -t -v \`pwd\`:/srv numerique1/composer-symfony2 install

You can also create an alias 

> echo "alias composer='docker run -i -t -v `pwd`:/srv numerique1/composer-symfony2'" >> ~/.bashrc

Reload bashrc
> source ~/.bashrc

And use it 

> composer install
