# agile-tour-lille

Le site est actuellement configuré pour être sur `/agile-tour-lille`.

## Pour tester ses modifs en local

### Installation de Jekyll en local

https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

Si problème "nokogiri" sur Mac:

    bundle config build.nokogiri --use-system-libraries
    bundle install

### Lancement de Jekyll

    jekyll serve

## Workflow

Pour publier, pusher sur `master`. La branche `gh-pages` n'est plus utilisée, c'est `master` qui est publiée directement.

    git checkout master
    echo do something funny
    git commit -a -m "Added: Something funny"
    git push
