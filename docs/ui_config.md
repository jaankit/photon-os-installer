# What is UI config

UI config file is a json format with following possible parameters:

**Note:** All top level keys must be optional.

### "download_screen" (depends on _"network_screen"_)
- Used to show a window where user can input a custom URL from
  which a file can be downloaded and placed in a custom location
  in the installed system.

  - _"title"_ (required)
    - A short title to identify this screen
  - _"intro"_ (required)
    - An brief 2 line intro of what URL you are requesting the
      user to input
  - _"destination"_ (required)
    - String: Path to where in the installed system you would
              like to see this file
