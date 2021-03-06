# Contributing

I like pull requests from everyone. By participating in this project, you
agree to follow the code of conduct below

[code of conduct]: https://github.com/1technophile/OpenMQTTGateway/blob/master/CODE_OF_CONDUCT.md

Fork, then clone the repo

Make your modification,
* If you want to add a new gateway, name it ZgatewayXXX, XXX replaced by your gateway communication type, can be more than three letters
* If you want to add a new sensor, name it ZsensorYYY, YYY replaced by your sensor type, can be more than three letters
* If you want to add a new actuator, name it ZactuatorZZZ, ZZZ replaced by your actuator type, can be more than three letters

Review your code, compile it for Arduino Uno and ESP8266

Test it localy on your hardware config

Emit a pull request

Verify the travis CI compilation results

Request for review

I may suggest some changes or improvements or alternatives.

Some things that will increase the chance that your pull request is accepted:
* Comment your code
* Ask eventually for design guidelines
* Write a [good commit message][commit].

[commit]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
