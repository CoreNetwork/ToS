# ToS (Terms of Service)

Original work by [YoFuzzy3](http://www.spigotmc.org/resources/tos.100/).

### About

ToS allows to display a message forcing people to read and accept the rules. There are configuration options which can disallow certain actions (chatting, moving, breaking blocks, etc) unless player has read and accepted the terms of service (rules).

### Changes by Core Network:

1. Added a config option to remove the requirement to read rules before accepting (`Options.RequireToReadRules`) – it’s off by default.
2. ToS message will be also displayed on login.
3. Edited default config messages and config values – disabled all event checks and set notification frequency to 15 minutes.
4. Mavenized the project so it can be built with Jenkins

Above changes allow to use the plugin as a one-off notification for all players logging into your server and allowing them to unsubscribe once they saw the message.

Most recent of this plugin can be found at http://build.core-network.us:8080/job/ToS/

Full copyright and huge props belong to YoFuzzy3. :)
