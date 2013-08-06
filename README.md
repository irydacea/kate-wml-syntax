Wesnoth Markup Language Syntax Highlighting for Kate
====================================================

`wml.xml` is a syntax highlighting schema for the **Kate[a]** text editor
targeting the markup language used for configuration and scripting by the
**Battle for Wesnoth[b]** game engine. More specifically, this schema works
with any editor that makes use of the **KatePart[c]** editor component or
highlighting schema format.

[a]: http://kate-editor.org/
[b]: http://www.wesnoth.org/
[c]: http://kate-editor.org/about-katepart/

Contained in this directory is the development version of the schema. Changes
are sent and included upstream in Kate once deemed suitable for general usage.


Installing
----------

If you are using relative modern versions of Kate, you can obtain the latest
stable version through a few simple steps:

 * Open the preferences dialog by choosing Settings -> Configure Kate in the
   menu.
 * Proceed into Editor Component -> Open/Save -> Modes & Filetypes.
 * Click on Download Highlighting Files and choose the Wesnoth Markup Language
   schema, plus any dependencies that you might need to update or install
   (see below).

Alternatively, you may obtain the latest development version of `wml.xml` from
this repository and install it to `<application data>/katepart/syntax`, where
`<application data>` stands for one of KDE's preferred data directories
(such as `$HOME/.kde/share/apps`).

It should work out of the box when opening standard Wesnoth Markup Language
(`*.cfg` or `*.pbl`) files for the first time.


Dependencies
------------

`wml.xml` makes use of the following additional schemas included in Kate:

 * Alerts (`alerts.xml`)
 * Lua (`lua.xml`)
 * Pango (`pango.xml`)
