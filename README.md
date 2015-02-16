#LeaderboardC2

LeaderboardC2 is a self hosted Open Source PHP Leaderboard for [Construct2](https://www.scirra.com/construct2). Post, fetch and display high scores.

## Requirements

- PHP 5.4+
    - [pdo_sqlite](http://php.net/manual/es/ref.pdo-sqlite.php)


To determine your PHP version, create a new file with this PHP code: `<?php echo PHP_VERSION; // version.php`. This will print your version number to the screen.

## Install

### Backend

1. Insure that you have the required components.
2. Download LeaderboardC2 or cloning this Github repo.
3. Upload LeaderboardC2 through FTP/SFTP or whatever upload method you prefer to the public-facing directory of your site.
4. Ensure that the permissions for the `data` folder and `yourbase.sqlite` file are set to `0777`.

### Plugin installation

#### Manual 

1. Close Construct 2.
2. Checkout the 'master' branch from this repository.
3. Copy the contensts of the folder addon/files/leaderboard/ into CONSTRUCT_2_INSTALLATION_FOLDER\exporters\html5\plugins\leaderboard.

#### Automatic

Drag and drop the [leaderboard.c2addon](https://github.com/ohtejera/leaderboardC2/raw/master/addon/leaderboard.c2addon)
 in to the Construct2 window to install it.

## Plugin configuration

The plugin can be configured by selecting the object *Leaderboard*  from the *Object types* list inside Construct2.

![plugin](https://cloud.githubusercontent.com/assets/3797402/6205781/2e1612e8-b561-11e4-811d-af0b15383a17.jpg)

### Plugin Properties

+ *Leaderboard service URL* (The Leaderboard service URL)
+ *Game ID* (The game id. Should be equal to the SQLite file name without the .sqlite extension)
+ *Magic number* (The magic number. Should be equal to the 'magic_number' property in the config.ini file)
+ *Magic key* (The magic key. Should be equal to the 'magic_key' property in the config.ini file)
+ *Log requests* (Sends request URLs into console. For debugging purposes)

## Examples

### Live demo
http://htejera.ukelelestudio.com/leaderboardc2/demo/

### Construct2 project

This project comes with a .capx as a reference to know how to use it, you can download it from [here](https://github.com/ohtejera/leaderboardC2/raw/master/c2Example/Leaderboard.capx).

## Contribution Guidelines

Please submit issues to *ohtejera/leaderboardC2* and pull requests to *-dev branches.

![gauchoiwantyou2](https://cloud.githubusercontent.com/assets/3797402/6204483/3f8bddbe-b534-11e4-9966-fbc78e8d8161.gif)

## License

The MIT License (MIT)

Copyright (c) 2015 Henry Tejera

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


