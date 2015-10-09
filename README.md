# agile-tour-lille

Le site est actuellement configuré pour être sur `/agile-tour-lille`.

## Jekyll en local

    jekyll serve -b ''

## Workflow

Travailler sur `master` et lorsqu'une version est valide, la pusher sur `gh-pages`.

    git checkout master
    echo do something funny
    git commit -a -m "Added: Something funny"
    git push
    git checkout gh-pages
    git pull origin master
    git push
