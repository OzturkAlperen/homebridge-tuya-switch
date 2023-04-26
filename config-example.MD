## Configurations
The configuration parameters to enable your devices would need to be added to `platforms` section of the Homebridge configuration file.
```json5
{
    ...
    "platforms": [
        ...
        {
            "platform": "TuyaLan",
            "devices": [
                {
                    "name": "SwitchExample",
                    "type": "Switch",
                    "manufacturer": "ManufacturerExample",
                    "model": "ModelExample",
                    "id": "00000000000000000000",
                    "key": "0000000000000000",
                    "switchCount": 0
                }
            ]
        }
    ]
    ...
}
```
#### Parameters
* `name` (required) is anything you'd like to use to identify this device. You can always change the name from within the Home app.
* `type` (required) should be "Switch".
* `manufacturer` and `model` are anything you like; the purpose of them is to help you identify the device.
* `id` (required) and `key` (required) are parameters for your device.
* `ip` needs to be added **_only_** if you face discovery issues.
* `switchCount` (required) is the number of channels on your switch.
