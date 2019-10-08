# EuSigil
```
Written by Andy P. (Icy_Viking)
Eu Ver: 4.1.0 Beta 2
Sigil Ver: 0.9.0
Contact/Paypal: g_andy <at> live.com
	
(c) EuSigil 2019
```

### ABOUT
```
This is a wrapper of the Sigil library for the Euphoria programming language. It is a simple to use
multimedia library. It is good for making small games or prototyping. It has a small list of functions
and is easy to use. It is written in C and can be used with C++. This wrapper allows for it to be used
with the Euphoria programming language. Some examples are provided to help you get started with using
EuSigil.
```

### LICENSE

```
This software is provided as-is. There is no warranty for this software. You use this software at your
own risk. You may not hold the developer or Euphoria community responsible for any damages or mis-use
of this software. You may use this wrapper to write Euphoria programs using the EuSigil wrapper. You
can distribute software you make with this wrapper as you please. You may not claim you wrote the original
EuSigil wrapper. While not required an aknowledgement of the original author would be nice.

```

### LINKS
```
SIGIL: http://www.libsigil.com/ - Sigil Homepage
EUPHORIA: https://openeuphoria.org/index.wc - Euphoria Homepage
```

```
 Thanks for using EuSigil! 
```

### EXAMPLE

```
without type_check

include std/machine.e
include EuSigil.ew

slWindow(640,480,"Simple Window - Click 'X' or ESC to close",0)

while not slShouldClose()  do
  if slGetKey(SL_KEY_ESCAPE) = 1 then
  	 slClose()
  end if
	slRender()
end while

slClose()

```
