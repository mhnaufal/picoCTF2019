# Insp3ct0r
Web Explotation - 50 points

## Description
Kishor Balan tipped us off that the following code may need inspection: https://2019shell1.picoctf.com/problem/52962/ [link](https://2019shell1.picoctf.com/problem/52962/) or http://2019shell1.picoctf.com:52962

### Hint
* How do you inspect web code on a browser? 
* There's 3 parts

## Solution 
This is one of the fundamental in web exploitation which is inspect the element of a website. All you have to do is press `Ctrl + U` or `right click -> inspect element` in the relevant page. 
Remember there are 3 flags in this challenge
1. [link](view-source:https://2019shell1.picoctf.com/problem/52962/)
* *flag: picoCTF{tru3_d3*

2. [link](view-source:https://2019shell1.picoctf.com/problem/52962/mycss.css)
* *flag: t3ct1ve_0r_ju5t*

3. [link](view-source:https://2019shell1.picoctf.com/problem/52962/myjs.js)
* *flag: _lucky?39dd9e36}*

The second and third link get from click in the link in the first web.

Put them together and we get 
`picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?39dd9e36}`
