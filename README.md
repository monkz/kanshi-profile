# kanshi-profile
Creates Profiles for kanshi for swaywm

## Dependencies:
* jq

## Usage
1. Set your display settings (f.e. via wdisplays)
2. Check if everythig is to your liking
   ```
   kanshi-profile current
   ```
3. Save it to your kanshi config
   ```
   kanshi-profile current example >> ~/.config/kanshi/config
   ```
4. Reload kanshi daemon
   ```
   kanshictl reload
