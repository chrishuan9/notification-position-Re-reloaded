# notification-position-re-reloaded
Fork of the original Gnome Shell extension allowing customization of notification banner position and animation properties

## Installation

### Install from GNOME Extensions

<a href="https://extensions.gnome.org/extension/9419/live-lock-screen/">
  <img src="https://github.com/user-attachments/assets/d15de748-11b8-4a85-ad34-ec7786547b3c" width="250" alt="Install from GNOME Extensions">
</a>

> ⚠️ Due to the review process, the version on GNOME Extensions may lag behind the latest code in this repository.  
> For the newest features, it is recommended to install manually from this branch.  
> If you’d like to try the latest (possibly unstable) features, you can switch to the `experimental` branch.
  
### Manual

1. Clone the repository:

   ```bash
   git clone https://github.com/chrishuan9/notification-position-re-reloaded.git
   ```
2. Copy to your extensions folder:

   ```bash
   cp -r notification-position-re-reloaded ~/.local/share/gnome-shell/extensions/notification-position-re-reloaded@chrhuang
   ```
3. Log out and back in, then enable the extension:

   ```bash
   gnome-extensions enable notification-position-re-reloaded@chrhuang
   ```
4. Open the extension preferences and setup the position of the notification banner

## Requirements
* recompile schema if adding additional options: <br>
  ```glib-compile-schemas schemas```

## Acknowledgments
* Original Author of [notification-position-reloaded](https://github.com/marcinjakubowski/notification-position-reloaded)
* Icon kindly provided by Flaticon: <a href="https://www.flaticon.com/free-icons/subscribe" title="subscribe icons">Subscribe icons created by Freepik - Flaticon</a>
