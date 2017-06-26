## ATtiny45 EverLED

Ted Yapo has this great [TritiLED project](https://hackaday.io/project/11864-tritiled), and I basically just ripped it off with whatever parts I had on hand.  While he aims at making a dim LED flashlight that will last for 10+ or even 25 years, I'm fine with two or so, as long as it runs whatever LEDs I've got on hand and an ATtiny24-45-85.  

The secret? Running the LED by putting it in flyback with an inductor.  This creates a (nearly) lossless store for the energy pulses that a) is fairly easy to make tiny and b) also doubles as a step-up voltage converter so it will run almost any LED or chain.

