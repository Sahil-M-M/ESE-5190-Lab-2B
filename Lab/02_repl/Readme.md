      Sahil Mahendra Mangaonkar
      LinkedIn: https://www.linkedin.com/in/sahil-m-39a2671b0
      Tested on:  HP Probook 650 G1 (15.6-inch, 2014), Window 10

### TODO:

Create a 'sequencer' that allows you to record BOOT button presses and play them on the Neopixel, and also play a sequence of read/write commands. You should be able to:
- record at a least a few seconds of button input to your RP2040 (in RAM)
- replay a recorded sequence on your NeoPixel
- loop a recording
- save a recording to your laptop (the Python Serial library is one way to do this)
- play a recording from your laptop
- record 'macros' (a sequence of console commands) based on keystrokes in your serial console
- hand-edit a list of register read/write commands on your laptop, and play them on the RP2040
- include multiple I/O sources in a recording, and remap among the following:
    - inputs: BOOT button, console commands, register read/write commands
    - outputs: neopixel color, neopixel brightness, data over serial, register read/write commands


## REPL Video

The following demonstration video shows reading from and writing to a register directly. Atomic-bit setting can also implemented.

https://user-images.githubusercontent.com/73771085/202280796-6efb041b-b64c-434b-af71-99299a92152d.mp4

Here, when the user gives input as "r" followed by the address of the register (for e.g. d00000004 for address 0xd00000004), the program fetches the value of that register.

When user gives input as "w" to select write to register operation. User will then have to input the address of the register (for e.g. d00000010 for address 0xd00000010) followed by the value to be written into the register.
