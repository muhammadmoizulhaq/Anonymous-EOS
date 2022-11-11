# Anonymous EOS
Edited version of the Epic Online Services plugin for Unreal Engine 5.0.3 that includes a way to login anonymously through device ID's.

## General Notes
- When opening the project in an IDE such as Rider or Visual Studio, the imported plugins might tell you there is an error in the ``*.Build.cs`` files of the plugins. You can ignore these.
- Because you will be logging in as an anonymous user, you will not be able to use a few of the services Epic Online provides. The following services can not be used:
  - Achievements
  - Stats
  - Leaderboards
  - Player data storage
  - Player ticketing
  - Title storage (not sure)
  - Player reports (not sure)
  - Player sanctions

## Installation

There are two ways to install the plugins:
- Clone this project into the Plugins folder of your project.
- Download the release zip and drag the folders in the zip into the Plugins folder.

After putting the plugins into the Plugins folder, you need to right click on the ``.uproject`` file and click on ``Regenerate Visual Studio project files``. After this is done you need to compile the project.

## Usage

To use the plugins included in this project, the following steps should be taken:
