# ST-API-ios-Shortcuts
Using iOS Shortcuts and Siri to Interact with Smartthings

Here are some iOS Shortcuts for interacting with SmartThings devices, rules and scenes.

There are four general Shortcuts (ending in _api) that provides the following functionality:
1. Execute a Rule (ST_Rule_API)
2. Execute a Scene (ST_Scene_API)
3. Get Device Status (ST_Device_Status_API)
4. Send Device JSON commands (ST_Device_CMD_API)

To use the general Shortcuts, you need to edit each one and add your personal access token (pat entry) to the dictionary and your location id (locid entry) for the ST_Rule_API

To control SmartThings devices/rules/scenes, create a duplicate of the corresponding test_xxxx Shortcut, rename the Shortcut and edit the Shortcut to add the appropriate id and for sending device commands, add the minimized JSON command, for example:
{"commands": [{"component": "main","capability": "switch","command":"on"}]}

Once you’ve created your Shortcuts, you can added them to your Home Screen or as widget for easy execution. 

Or use Siri to execute the Shortcut by saying “Hey Sir Shortcut yourShortName”. I found that Siri finds Shortcuts much better when you include “Shortcut” in the phrase.

Once downloaded, unzip the archive and tap each Shortcut to add it to the Shortcut app where you can can edit and run the Shortcut
