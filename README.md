## Install

### [TextMate Version 2.0 Alpha](http://blog.macromates.com/2011/locating-bundles/)

    mkdir -p ~/Library/Application\ Support/Avian/Bundles
    cd !$
    git clone git://github.com/trey/trey-frontend-tmbundle.git "Trey - Frontend.tmbundle"

### TextMate Version 1.x

    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/trey/trey-frontend-tmbundle.git "Trey - Frontend.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

(Original instructions stolen from the [GitHub Bundle](http://github.com/drnic/github-tmbundle/tree/master).)

[More information about creating a Git repository for TextMate Bundles.](http://solutions.trey.cc/2008/06/23/textmate-bundle-on-github/)