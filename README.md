Dehydrated package for Debian/Ubuntu
====================================

Adapted "Backports" package letsencrypt.sh

main script is taken from [https://github.com/lukas2511/dehydrated/]

Lazy admins please use repo:

    wget -O - http://v.s.cz/info@vitexsoftware.cz.gpg.key|sudo apt-key add -
    echo deb http://v.s.cz/ stable main > /etc/apt/sources.list.d/ease.list
    aptitude update
    aptitude install dehydrated


please feel free to use our  **dehydrated-apache2** package to configure your webserver.

    
There is also initial support for pound called **dehydrated-pound**
