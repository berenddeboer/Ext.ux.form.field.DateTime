Introduction
============

An Ext.ux.DateTimeField control has been floating around on the Sencha
forums. There were some patches to make it work for 5.1.

See here: http://www.sencha.com/forum/showthread.php?137242-Ext.ux.DateTimeField-DateTimePicker-for-ext4-also-DateTimeMenu-TimePickerField

What works
==========

I got the latest version, renamed the class to be more like the
current Ext 5.1 schema, and fixed an error when trying to select the
time control.

Obsolete code was also removed.

What does not work
==================

The time control spinners do not get focus when you click in the
corresponding input field. Pressing tab does focus the controls though.
