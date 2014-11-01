# ToS (Terms of Service)

Original work by [YoFuzzy3](http://www.spigotmc.org/resources/tos.100/).

### About

ToS allows to display a message forcing people to read and accept the rules. There are configuration options which can disallow certain actions (chatting, moving, breaking blocks, etc) unless player has read and accepted the terms of service (rules).

### Changes by Core Network:

1. Removed the requirement to read rules before accepting. Design your messages to make it apparent that they need to run another command.
2. ToS message will be also displayed on login. This allows to edit notification frequency to something sane like 15-30 minutes not default 10 seconds.
3. Mavenized the project so it can be built with Jenkins

Above changes allow to use the plugin as a one-off notification for all players logging into your server and allowing them to unsubscribe once they saw the message. If you want to be strict and actually use this to force acceptance of your ToS/rules, please use the [original version](http://www.spigotmc.org/resources/tos.100/) as our changes remove the strict nature of the plugin (we recommend disabling every event check as well).

Most recent of this plugin can be found at http://build.core-network.us:8080/job/ToS/

Full copyright and huge props belong to YoFuzzy3. :)
