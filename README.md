# configs
## Personal config repository.

#### Firefox: 
  - mostly default privacy settings from ffprofile.com (9/12/22)
  - resistFingerprinting enabled (may cause additional captchas and harder time completing them) 
  - addons: 
      - HTTPS Everywhere: HTTPS encryption automatically on all sites if supported
      - Privacy Badger: Detects and blocks trackers
      - uBlock Origin: Adblocker and Anti-tracking (more advanced than privacy badger but takes more advanced config to get better use out of it)
      - Decentraleyes: Emulates CDN by intercepting requests, finding the required resource, and injecting it into the environment.
  - installation: 
      - If a new profile is needed run *firefox -no-remote -ProfileManager* and create it in the opened firefox window
      - Type *about:support* into the URL and open profile directory
      - Delete everything in the profile directory and unzip the profile.zip to the directory or unzip the enterprise_policy.zip to the unedited directory (keep existing files)
      - Start Firefox again. If you made a new profile, you can use it with *firefox -no-remote -P profilename* 
  - TODO:
      - Add youtube audio and youtube search engine extention to config file
      - Add @g @y @w url shortcuts for searching google, youtube, and wikipedia 
      - Figure out whats about the privacy settings blocks duo (owned by cisco)

#### Plasma KDE: 
  - Appearence Settings
    - put in /usr/*/* to add for all users
    - install icons locally at ~/.local/share/icons
    - install splash screens locally at ~/.local/share/plasma/look-and-feel
    
#### Terminal Emulator: 
  - Alacritty (see Alacritty folder for config file, cheat sheet, liked themes(cyberpunk-neon active))
