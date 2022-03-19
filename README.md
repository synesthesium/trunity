# Trunity
Trunity is a script to port Unity games for Windows to Linux automagically.
# What you'll need
- A Windows **Unity** game with a **Unity** version ≥ **2019.4.16f1**, builds < **2019.4.16f1** may work but are untested*
- Python 3.7+ is what the script is made for, you should at least have a Python 3.x version
- You're expected to have the **GNU Coreutils****
- You also need **xhost** to avoid an **XCB** crash at game boot
- It's a given, but the host should be on Linux. This script will not function on Windows.

<sup>* Nothing below **2019.1.1** will work due to an incompatibility in the build ID detection</sup>  
<sup>** The **Coreutils** are included with any modern Linux distro</sup>
# Why use this?
Turns out, a significant amount of Unity games would work fine on Linux but don't have an official build.

This arose because I wanted to play ULTRAKILL on Linux and Wine was UNFATHOMABLY sloooow.  
I ended up having to port the game over by hand and since nothing beats a poweruser's laziness, I decided to create this.

**You're welcome.**
