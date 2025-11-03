<p align="center">
  <img src="/docs/img/banner.png" alt="Music Doodad Banner" width="80%">
</p


_A clean and simple digital music player separate from our mobile devices but just as quick as it would be from your phone. Well, that’s the idea anyway._

# **The Approach**
I’m going to try and make this as flexible and customisable as possible. I’m going to attempt to do this by using a Raspberry Pi Compute Module 4 (CM4), and a custom PCB board (carrier board). By doing this, I will be able to cleanly connect all the components together in the cleanest way possible.

# **The Components**
This is idealistic, and I may not be able to achieve all these goals; however, better to shoot for the stars and land on the moon!

- Touchscreen video output
- Scrollwheel (Orientation not decided)
- Physical buttons for quick control of media
- AUX out (For use in cars)
- USB-C port for power

# **Audio**
The audio is a key part of this device; its multi-format output methods will allow for flexibility. I will utilise Spotify’s API to create a player that allows for seamless control of ecosystems already created, such as being used on a desk alongside a computer or being used independently in a car. Not including built-in speakers reduces the size and cost, especially where realistically they might not even be used.

# **Interface**
I plan on creating my own interface utilising a kiosk-style system where a Linux OS will boot into a web wrapper interface. This allows for the use of pre-existing systems such as the Spotify API. I hope to make the set up as seamless as possible, potentially utilising QR code capabilities, making the user log in on their phone on the same network.  

The flexibility of using a module like the CM4 means that I can be as creative as I like and run with this idea.
