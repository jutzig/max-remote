---
layout: page
title: MAX! Remote FAQ
description: Frequently asked questions
---

* TOC
{:toc}

## Can I use MAX! Remote for adjusting my heating while I am not at home?

Yes, you can. But a direct connection to the Cube is required so you need to configure a VPN tunnel in your router and activate the tunnel in your phone. Port Forwarding is also possible but strongly discouraged because it will essentially allow everybody to access your MAX! Cube from a remote location.

How to set up VPN depends on your router model. Here is an example for Fritz!Box [VPN](https://en.avm.de/service/knowledge-base/dok/FRITZ-Box-7590-AX/1060_Setting-up-a-VPN-to-the-FRITZ-Box-in-Android/) 

## Why is the current temperature not shown?

If a room does not contain a wall thermostat the current temperature is retrieved from the
heating thermostats. Unfortunately this method is not as reliable as using a wall thermostat.
The heating thermostats will only send the temperature when the valve position changes, or the mode
 is changed (e.g. `AUTO`, `MANUAL`,...). So the cube might not know the current temperature in a room if the heating valve has not moved in a while and then the App cannot display the temperature either.

## I get an error when I try to change the temperature in a room, what is the problem?

Unfortunately the cube seems to have some stability issues. If you see the message 
`The MAX! Cube did not confirm the new setting in time` every time you try to change the
temperature in a room then your Cube is probably stuck. The best way to fix this, is to
reboot the Cube from the App, or - if that does not work - 
to disconnect the Cube from power, re-connect it and wait a few minutes. 
Once the Cube is re-initialized, the App should be able to change the temperature again. 

If this problem happens very often for you, it might be a good idea to perform to power off the cube once a day. An easy way to do this is, is an outlet with timer for example. 

## Is Aexa Supported?

Alexa is running actions on the server side. The server however cannot access your local cube,
there direct support for Alexa is not possible.

You can still control your Cube with Alexa by using MAX! Remotes Tasker plugin.
By combining Tasker with AutoVoice, you can define voice commands for your cube that will then
be executed by the Tasker Plugin.

## How do heating profiles work?

Heating Profiles are a way to quickly switch between several heating programs. This is useful if you have for example different work shifts or want to use different settings when you are on holiday.

To create a heating profile, first program the cube to a heating program of your liking. Once that is done, press refresh in the app and select `Heating Profiles`. You can now store the current program under a name of your choosing. The same screen is used to delete or activate existing heating profiled.

_Hint_: the currently active heating profile is highlighted in blue

## I activated a heating profile, but the rooms are not set to the right temperature, what can I do?

The MAX! system does not always seem to apply the correct target temperature after changing the weekly program. If you are facing this problem, the easiest fix is usually to press the `Auto` button in the App to set all rooms to the temperature defined in the program.

## MAX! Remote fails to load the room information, what can I do?

The first thing you should check is that you entered the correct IP address to access the cube. 
You can switch back to the respective screen by opening the menu und tapping on your cube connection (upper left, near the icon).
Next select `Manage cubes...`.

Additionally you should check that the wireless network is activated on your phone and that the cube is properly connected in the network. If everything is in order you also need to ensure that all other applications that access the Cube directly are terminated because the Cube allows only one connection at a time.

## Will there be a Windows or iOS version?

Sorry, no.

## What is the meaning of the Duty Cycle?

By law the Cube cannot send on its radio frequency for more than one minute per hour.
The duty cycle shows how many percent of that quota has already been used.
If the cycle reaches 100% the cube will have to wait an hour before it can send new commands.
