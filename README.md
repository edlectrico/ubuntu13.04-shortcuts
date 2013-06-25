ubuntu13.04-shortcuts
=====================

A simple tutorial of how to add custom shortcuts to any applications to your desktop and to Unity dock.

1. Install gnome-panel

sudo apt-get install --no-install-recommends gnome-panel

2. Type the following command to create a new shortcut under /usr/share/

sudo gnome-desktop-item-edit /usr/share/applications/ --create-new

3. If you want to add the shortcut to the Unity dock, just go to the Dash (Windows keyboard key) and type the application name. 
From the dash result drag your application and drop it in Unity.
