# Frequently Asked Questions

: Last Updated: 8 June 2025

## How do I use this?

Our MVP product is a WordPress plugin, the FAIR Plugin. You can install it just like you would any other plugin.

You can download the latest version from the [FAIR Plugin releases page](https://github.com/fairpm/fair-plugin/releases).

## How do I add my plugin for distribution?

Right now, there is no way to add your plugins (or themes) for distribution. Our current sole distribution node is AspirePress, which is a mirror of WordPress.org's directory.

## How will this distribution work?

The [FAIR Protocol](https://github.com/fairpm/fair-protocol) is being refined, but it is based on AtProto (used by BlueSky). We recommend familiarizing yourself with the documentation.

## Will this DDoS WordPress.org?

No, the current (and future planned) process causes less traffic to WordPress.org than individual sites would do normally. 

Being a good net denizen was paramount to our process. Each distribution mirror (called a Node) downloads each package (a plugin, a theme, etc) one time per version. From then on, the installs and updates are processed by the Node. 

The plugin (be it FAIR or [AspireUpdate](https://github.com/aspirepress/AspireUpdate)) pulls data from the distribution Node first. In cases where a package is not available from the Node, then a direct call to the WordPress.org servers is used. It's important to note that each of those requests represents traffic that would be handled by WordPress.org with or without FAIR.

The [AspireSync](https://github.com/aspirepress/AspireSync) process is constantly being improved to reduce the load on WordPress.org.