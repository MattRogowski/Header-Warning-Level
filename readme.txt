Name: Header Warning Level
Description: Shows a user's warning level in the welcomeblock.
Website: https://github.com/MattRogowski/Header-Warning-Level
Author: Matt Rogowski
Authorsite: https://matt.rogow.ski
Version: 1.8.1
Compatibility: 1.8.x
Files: 1
Templates added: 1
Template changes: 1
Settings added: 4 (1 group)

To Install:
Upload ./inc/plugins/headerwarnlevel.php to ./inc/plugins/
Go to ACP > Plugins > Activate
Go to ACP > Configuration > Header Warning Level Settings > Configure settings > Save.

Information:
This plugin will add a note to the welcomeblock, reminding people of their warning level.

You can turn the message off completely, and there's a setting to turn it off for users who have 0% warning. There's also a setting for a cut-off level.

The warning level % will be in the same colours as the warning % as it shows in the postbit in threads, and on the profile pages. The % also links to ./usercp.php as this is where the warning information is shown by default.

Change Log:
09/05/09 - v0.1 -> Initial 'beta' release.
09/05/09 - v0.1 -> v0.2 -> 2 settings added. Deactivate, reupload ./inc/plugins/headerwarnlevel.php, activate, configure settings.
10/05/09 - v0.2 -> v1.0 -> 1 setting added. Deactivate, reupload ./inc/plugins/headerwarnlevel.php, activate, configure settings.
01/09/10 - v1.0 -> v1.6 -> General cleanup. 1.6 compatible only.
25/08/14 - v1.6 -> v1.8 -> MyBB 1.8 compatible. To upgrade, deactivate, reupload ./inc/plugins/headerwarnlevel.php, activate.
08/01/17 - v1.8.0 -> v1.8.1 -> Templates now cached. Code refactor. Dropped compatibility with MyBB 1.6. To upgrade, reupload ./inc/plugins/headerwarnlevel.php.

Copyright 2017 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.