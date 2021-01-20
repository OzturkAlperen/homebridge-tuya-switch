<span align="center">

<a href="https://github.com/Alperen-Ozturk/homebridge-tuya-switch/blob/master/assets/homebridge-tuya-switch.artwork.png?raw=true"><img alt="homebridge-verified" src="https://github.com/Alperen-Ozturk/homebridge-tuya-switch/blob/master/assets/homebridge-tuya-switch.artwork.png?raw=true" width="600px"></a>

# Homebridge-Tuya-Switch

<a href="https://www.npmjs.com/package/homebridge-tuya-switch"><img title="npm version" src="https://badgen.net/npm/v/homebridge-tuya-switch" ></a>

</span>


homebridge-tuya-switch is a homebridge plugin that lets you control your Tuya based switch devices with HomeKit. 


## Installation 
To use this plugin, follow the steps below:

1) Install [Homebridge](https://github.com/homebridge/homebridge), if you haven't already.

2) Install this plugin. You may need to prefix this command with ```sudo``` if you run into any issues.

```npm i -g homebridge-tuya-switch```

3) Add your device's parameters to your ```config.json``` file, then reload Homebridge.

You can check out the [configuration example](https://github.com/Alperen-Ozturk/homebridge-tuya-switch/config-example.MD) for parameters you should set.

**To get ID and Key** Watch [this](https://www.youtube.com/watch?v=oq0JL_wicKg) video. 


## Issues

If you spot any errors with the plugin, or have a question, feel free to open an issue.


## Contribution guide

Any help is welcome! 

If you would like to make refinments to this plugin, add new device support, or anything else feel free to make a fork, and submit a PR detailing the changes you made, and why. 

## Note

This repository is created because there is no support for switch type accessories on iRayanKhan's homebridge-tuya repository. Once he merges my commits or adds support for switch type accessories himself, you should go and use his plugin. This plugin supports ONLY switch type accessories.


## Credits

CodeTheWeb - Original repo

iRayanKhan - homebridge-tuya repo

mxdanger   - Plugin branding 

Amoo-Miki  - Plugin core

Oznu       - config.schema, and various enhancements in V2.0.0
