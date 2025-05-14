# mono-modified
A modified version of the Mono theme for Publii

Download the theme here: [mono 0.3.1.0](https://github.com/bjazmoore/mono-modified/releases/tag/0.3.1.0)

This version allows the newsletter heading and description fields to be user modified in the theme settings.

In the official theme those two elements (newsletter and newsletterDesc) are defined in the mono.lang.json.

![mono-theme](https://github.com/user-attachments/assets/cc0cb910-756f-4939-92ec-6f88badf75ee)

Yes they can be changed there, but that makes it hard to use this theme for clients who will not know how to modify a json file should the theme be updated.

Please move these two fields to the config.json so that they are in the theme settings and modify the theme file partials/sidebar.hbs as needed. 

That is the only change in this theme.  
