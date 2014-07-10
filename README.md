migemogrep
==========

Search/grep against Japanese text using latin-1 text

Installation
------------

Please visit our releases page, and download the appropriate version/platform:

    https://github.com/peco/migemogrep/releases

Or, if you are on OS X and are using homebrew

    $ brew tap peco/peco
    $ brew install migemogrep

And finally, if you want the latest bleeding edge version:

    $ go get github.com/peco/migemogrep

Usage
-----

    $ cat file.txt
    親譲りの無鉄砲で小供の時から損ばかりしている。
    小学校に居る時分学校の二階から飛び降りて一週間ほど腰を抜かした事がある。
    なぜそんな無闇をしたと聞く人があるかも知れぬ。別段深い理由でもない。
    
    $ cat file.txt | migemogrep koshiwo
    小学校に居る時分学校の二階から飛び降りて一週間ほど腰を抜かした事がある。
    
    $ migemogrep riyuu file.txt
    なぜそんな無闇をしたと聞く人があるかも知れぬ。別段深い理由でもない。

