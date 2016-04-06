# seanlano-apparmor
AppArmor profiles for a variety of Ubuntu software

## Intro
These are just some AppArmor profiles that I've created over time, usually when there wasn't one for a particular piece of software. In particular I wanted to confine some of the less trusted proprietary software I had to use, such as Spotify. 
I'm no AppArmor expert, but I'm keen on security development and I've been using Linux for years. 

## Beware
No warranty is given, use at your own risk. 

## Usage
You'll need to copy the relevant profile into the correct directory on your computer, usually `/etc/apparmor.d/` on Ubuntu systems. Then enable it using `aa-enforce /path/to/binary`, and finally reload AppArmor (or restart the machine). You'll want to keep an eye on the system log for messages coming from AppArmor, to make sure nothing is wrong with the profile. 

## Licence
All my code here is GNU AGPL v3. 
