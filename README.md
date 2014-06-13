Binder
======

Linseed oil for software. Combines Syphon/Spout with basic show control.

Maybe this should be a Node-Webkit type thing? So you can use
web pages as a source, too.

Conceptually, we would like to run anything your OS can run and seamlessly switch between them.

Binder provides simple output destination for shared-texture sources and
a communication layer over TCP for enabling/disabling clients and sending
custom messages.

You can use the pre-built Binder program to simply switch between sources or link it
within your own project for custom control over how sources are combined.

## Initial Notes

### Structure

Binder
  - Displays final output.
  - Receives textures to display through texture sharing.
  - Sends commands to clients to foreground/background content.

Spout:
http://spout.zeal.co

Syphon:
http://syphon.v002.info

Look at Sliider:
https://github.com/vibber/Sliider

Probably use Node-Webkit:
https://github.com/rogerwang/node-webkit
