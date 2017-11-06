# audioAND

### _Feel free to comment and please commit here if you modify it!!!_
### or send an email to noizhardware@gmail.com

## This is an implementation of the logic operator AND in the audio domain
[Here a nice little video](https://youtu.be/du7YeRkbu44) where the audioAND is being used (it wasn't still an abstraction here)

3 audio signals are normalized to a 0-1 interval and each compared with a threshold, the boolean results are then fed in AND gates and used to generate a VCA with a simple AD envelope.

The 3 signals are fed into the VCA and sent out on the first 3 outlets.

**_INLETS:_**
- 3x audio~ inputs
- 3x threshold inputs (0-1 interval)
- VCA volume (0-10 recommended)
- AD envelope speed (millisec)

**_OUTPUTS:_**
- 3x audio~ out
- envelope / numeric (0-1)
- envelope~ (0-1)




The abstraction has 11 "a" in its name just to have all the inlets and outlets not too crammed. Also, 11 is a prime number.
You gotta love prime numbers.
Seriously.
