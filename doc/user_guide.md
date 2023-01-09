# Overview

The shot clock system consists of:

- A controller, that the operator uses to run the clocks.
- A number of displays (usually 2, but up to 8), that show the time remaining and connect to the controller using either WiFi or a USB cable.
  An LED indicator illuminates to show when the timer is running.

All units can be powered either from normal USB battery packs, or from the mains using a DC power supply.

# Basic Usage

*This section describes how to use clocks that have already been set up and configured.
See the Setup section if your clocks have not been configured before.*

Plug in either a charged battery pack or 12V DC supply to the controller and wait for the LCD display to power on.

Once the controller is fully on, plug in either a charged battery pack or 12V DC supply to the two displays.
The displays will flash while they attempt to connect to the controller.
Once they have successfully connected, the flashing will stop.

It is possible to connect displays to the controller using a USB cable.
This will temporarily override any pre-configured WiFi connection, and is useful if experiencing connection issues.

The controller has 3 buttons:

- Load time 1
- Load time 2
- Clock start/stop

Times 1 and 2 are configurable. A typical setup would be:

- Time 1 = 25 seconds (normal shot clock duration)
- Time 2 = 1 minute (time out)

The controller starts up with time 1 loaded and the clock stopped.
When the game begins, press *Clock start/stop* to begin the timer. Press it again to pause and resume the countdown.
Reset the clock by pressing *Load time 1*.

A buzzer sounds when the clock runs down to zero.

# Setup

*This section describes how to pair displays with a controller, how to set times 1 and 2, and how to change the controller password.*

Follow the instructions in **Basic Usage** to power on the controller.
The controller will act like a WiFi router. Using a laptop or mobile phone, go to your WiFi settings and connect to
the network named KShot-Controller-*xxxx* where *xxxx* is a four digit number.
The default password is KShot-Pass-*xxxx* which can **and should** be changed.

Open a web browser and you will be taken to a configuration page.

## Connect a Display

1. Connect a display to the controller using a USB cable.
2. Click the *Setup display wireless connection* button.
   The displays will each show a number between 1 and 8, and the same numbers will be listed in the configuration screen.
3. For each display, click the *Connect wirelessly* button to set up the WiFi connection.
4. Click done when all the displays have been connected wirelessly.

## Update Times

1. Click the *Change* button next to either of the 2 times to enter a new value between 1 and 99.
2. Click *Update* to store this new value.

## Change the Controller Password

**Changing the password will require reconnecting the displays.**
TODO: Is that actually true?

1. Click the *Change Password* button and enter a new password.
2. Click the Confirm button.
3. Press and hold the *Load time 1* and *Load time 2* buttons on the controller for 3 seconds.
   The LCD display will ask if you want to accept the new password.
4. Hold the *Clock start/stop* button for 3 seconds to accept, and the controller will return to normal operation.
   If you don't want to accept the new password, instead press either *Load time* button or wait for 10 seconds.


# Advanced Usage

## Getting Timer Logs

1. Connect a laptop or mobile phone to the controller by following the instructions in *Setup*.
2. Scroll down to the *Get Timer Logs* section which will list recent logs. Either:

  - Click the *download* button next to a log to download it to the connected device, or
  - Insert a USB stick into the controller and click the *copy to USB* button next to the log.

Once the logs take up more than a permitted amount of storage, the oldest logs will be automatically deleted.

## Resetting the Password

If you have lost the controller password you can reset it to the default described in *Setup*.

1. Hold the *Load time 1* and *Load time 2* buttons for 3 seconds.
   The LCD display on the controller will ask if you want to reset the password.
2. Hold the *Clock start/stop* button for 3 seconds.
   The password will be reset and the controller will return to normal operation.
   If you don't want to reset the password, instead press either *Load time* button or wait for 10 seconds.
