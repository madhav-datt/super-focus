# super-focus
For all the productivity freaks out there. This is a minimalistic command line productivity hack based on the [Pomodoro Technique](http://pomodorotechnique.com/).

## How it Works

`super-focus` has two modes. The first mode, for the more focused, is a timer with cycles consisting of a 20-minute work period followed by a 5-minute break period. It does not kill browser processes.

The second mode also is a timer with cycles consisting of a 20-minute work period followed by a 5-minute break period, but here it checks to see if a browser process (Chrome or Firefox) is running during the work period and kills it to help you stay focused and free from distractions on the internet. You will be able to reopen the browser during the 5-minute break period.

![Regular Timer Example](https://github.com/madhav-datt/super-focus/blob/master/Resources/Timer_Example.png)

* <a name="mode1">**Mode 1**</a>: `focus` - Cycles of 20-5 Minutes. Browser processes not killed.
* <a name="mode2">**Mode 2**</a>: `super-focus` - Cycles of 20-5 Minutes. Browser processes killed during the 20-minute work period.

## Installing super-focus

    $ wget -P ~/Downloads https://github.com/madhav-datt/super-focus/archive/super-focus-v2.0.zip
    $ unzip ~/Downloads/super-focus-v2.0.zip
    $ mv ~/Downloads/super-focus-super-focus-v2.0 ~/Downloads/super-focus
    $ chmod 755 super-focus/install
    $ sudo super-focus/install
    
The program uses `beep` for end-of-period notifications. The above commands will install `beep` also.
    
## How to Use super-focus

End of period notifications ----

### `focus` Timer

The `focus` timer is a [Mode 1](#mode1) type timer and can be run like this:

    $ focus [number of cycles]
    
Replace `[number of cycles]` with the number of cycles you want to run the timer for.

### `super-focus` Timer

The `super-focus` timer is a [Mode 2](#mode2) type timer and can be run like this:

    $ super-focus [number of cycles]
    
Replace `[number of cycles]` with the number of cycles you want to run the timer for.

At the end of each work/break period, a beep sound and a pop-up notification will let you know about the end of the period.

## Reporting Issues

Go ahead and open an issue, report a bug or ask for an additional feature [here](https://github.com/madhav-datt/super-focus/issues).
