# Changelog

All notable changes to `LERN` will be documented in this file.

### 3.0.1
- Fixed Pushover sounds

### 3.0.0
- When enabled in the config file you can now collect:
    - user_id - The id of the currently logged in user.
    - method - Then method of the request: GET, POST, DELETE, PUT, etc...
    - url - The full URL of the request.
    - data - The input data of the request, if any.

*__Reason for Major release: 3.0.0 introduces a new migration file and structure changes that could cause issues for 2.x users__*

### 2.3.0
- Added support for [Twilio](https://www.twilio.com/) an SMS messaging service.

### 2.2.2
- Fixed config for Plivo

### 2.2.1
- Changed dependancy from `tylercd100/monolog-plivo` to `tylercd100/monolog-sms` which is the same package with a different name

### 2.2.0
- Added support for [Plivo](https://www.plivo.com/) an SMS messaging service.

### 2.1.3
- Scutinizer Code Coverage
- Fixed Docblocks
- Added more Unit Tests (60% -> 94% Coverage)
- Changed dev dependencies

### 2.1.2
- Improved config file with env functions and comments. 
- Fixed some handlers by increasing the log level from ERROR to CRITICAL

### 2.1.1
- Fixed HipChat by making it use api v2

### 2.1.0
- Added Hipchat, Flowdock and Fleephook support

### 2.0.0
- Added a `LERN` facade
- Monolog\Logger Support
    - With the ability to use custom Logger and Handler instances
- Custom table name for migration (see the new config file)

### 1.1.0
- Added Slack

### 1.0.0
- Initial release and connected with packagist
