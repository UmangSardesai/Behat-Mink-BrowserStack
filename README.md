# Behat-Mink-BrowserStack
Run Behat + Mink tests on BrowserStack

## Steps to run 

1. Clone this repo:

  `https://github.com/UmangSardesai/Behat-Mink-BrowserStack.git`


2. Now install Behat, Mink, MinkExtension and their dependencies with composer:

  `curl http://getcomposer.org/installer | php`

  `php composer.phar install`

3. Add BrowserStack Username and Automate-key to `behat.yml`


4. Now to launch Behat, just run:

  `bin/behat`
