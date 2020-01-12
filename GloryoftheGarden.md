# Glory of the Garden
Forensic - 50 points 

## Description
This [garden](https://2019shell1.picoctf.com/static/86137520022d967547d5a2c99f4231f2/garden.jpg) contains more than it seems. You can also find the file in /problems/glory-of-the-garden_2_258af8e13bd7259207af0b0ee6fab645 on the shell server.

### Hint 
What is a hex editor?

## Solution

Given a .png picture and we need to find the flag within it. From the hint given we know that we need to see the hex of the given picture. 
However we only need to use `strings` command to find the flag. With addition [`grep`](https://www.google.com/search?safe=strict&client=firefox-b-d&ei=3JsaXrTvOI7b9QPclo7QCw&q=grep+command&oq=grep+&gs_l=psy-ab.3.1.0l2j0i10j0l4j0i10l2j0.1468834.1472260..1474692...1.0..0.732.2029.0j7j1j6-1......0....1..gws-wiz.......0i19j0i22i30i19j0i8i13i30i19j33i160j0i131j0i67.OH7Dsfdj8b0)

```
strings garden.png | grep pico
```
And we get the flag `picoCTF{more_than_m33ts_the_3y31e0af5C7}`
