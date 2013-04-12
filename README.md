org.eclipse.jface.text
======================

Modified plugin for auto completion in eclipse

Version
=======

org.eclipse.jface.text_3.8.2.v20121126-164145

Description
===========

This plugin is taken from eclipse 4.2 and is modified a little to improve auto completion user experiences.

Generally, it enables <kbd>Tab</kbd> key to down select word candidates, as well as <kbd>Shift</kbd> + <kbd>Tab</kbd> to perform up selection. Also it disables some annoying auto completion behaviors.

It is recommended that the user set 'Window->Preferences, Java->Editor->Content Assist, Content Assist->Auto Activation->Auto Activation triggers for java' to ' .abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ_'

Compile Requirements
============

- eclipse 4.2
- eclipse plug-in development environment

Usage
=====

- Compile this project and export it as 'deployable plug-ins and fragments'
- Put the exported org.eclipse.jface.text_3.8.2.v20121126-164145.jar into plugins directory, which is located in your eclipse installation directory.
- Restart eclipse
