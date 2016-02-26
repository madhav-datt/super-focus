# super-focus
For all the productivity freaks out there. This is a minimalistic command line productivity hack based on the [Pomodoro Technique](http://pomodorotechnique.com/).

## How it Works

`super-focus` has two modes. The first mode, for the more focused, is a timer with cycles consisting of a 20-minute work period followed by a 5-minute break period. It does not kill browser processes.

The second mode also is a timer with cycles consisting of a 20-minute work period followed by a 5-minute break period, but here it checks to see if a browser process (Chrome or Firefox) is running during the work period and kills it to help you stay focused and free from distractions on the internet. You will be able to reopen the browser during the 5-minute break period.

![Regular Timer Example](https://github.com/madhav-datt/super-focus/blob/master/Resources/Timer_Example.png)

* **Mode 1**: `focus` - Cycles of 20-5 Minutes. Browser processes not killed.
* **Mode 2**: `super-focus` - Cycles of 20-5 Minutes. Browser processes killed during the 20-minute work period.

## Installing super-focus

    $ wget -P ~/Downloads https://github.com/madhav-datt/super-focus/archive/super-focus-v2.0.zip
    $ unzip ~/Downloads/super-focus-v2.0.zip
    $ mv ~/Downloads/super-focus-super-focus-v2.0 ~/Downloads/super-focus
    $ chmod 755 super-focus/install
    $ sudo super-focus/install
    
## How to Use super-focus

### `focus` Timer

### `super-focus` Timer

## Reporting Issues

Go ahead and open an issue, report a bug or ask for an additional feature [here](https://github.com/madhav-datt/super-focus/issues).
