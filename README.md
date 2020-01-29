# Description

Displays download links and versions for latest BMLT Releases simply add [bmlt_versions] shortcode to your page.

# SHORTCODE
[bmlt_versions]

**Attributes:** root_server, wordpress, drupal, basic, crouton, bread, yap, tabbed_map, meeting_map, list_locations, upcoming_meetings, contacts
Adds ability to hide certain releases, default is to show all or 1.
                
Ex. [bmlt_versions drupal="0"] would not display drupal link.




# Installation

This section describes how to install the plugin and get it working.

1. Upload the entire BMLT Versions Plugin folder to the /wp-content/plugins/ directory
2. Activate the plugin through the Plugins menu in WordPress
3. Add the GitHub API Token to the BMLT Versions settings page WordPress Dashboard->Settings->BMLT Versions
4. Add [bmlt_versions] shortcode to your Wordpress page/post.


# Changelog

= 1.4.0 =

* Added CSS.
* Added Description

= 1.3.1 =

* Fix for BMLT Drupal download link.

= 1.3.0 =

* Added settings page for GitHub API Token.

= 1.2.2 =

* Cleanup.

= 1.2.1 =

* Added List Locations.
* Added Upcoming Meetings.
* Added Contacts.

= 1.2.0 =

* Rewrote to only use github api for versions.
* Added release date.

= 1.1.6 =

* Added BMLT Tabbed Map.
* Added BMLT Meeting Map.

= 1.1.5 =

* Added user-agent headers to get request to make github api happy.

= 1.1.4 =

* Changed bmlt basic to pull version from github api.

= 1.1.2 =

* Refractored some of the way versions are pulled.
* Added docker.

= 1.1.1 =

* Changed urls for moved repos.

= 1.1.0 =

* Added shortcode attributes to be able to only display certain links.
* Use github api for yap.

= 1.0.2 =

* Added Yap

= 1.0.1 =

* Added Bread

= 1.0.0 =

* Initial Release