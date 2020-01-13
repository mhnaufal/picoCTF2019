# Bases
General - 100 points

## Description
What does this **bDNhcm5fdGgzX3IwcDM1** mean? I think it has something to do with bases.

## Solution
This problem deal with base of a text. There are several common base which is base64 and base32.
And for this problem it is base64. You can use online decoder or try the following command.

```
echo "bDNhcm5fdGgzX3IwcDM1" | base64 -d
```

**echo** is like *print* in programming language.
**|** it's called [pipe](https://www.geeksforgeeks.org/piping-in-unix-or-linux/) used for passing through result of a command into the other command 
**base64** base64 encode/decode in linux.
**-d** stands for *decode*

Flag : `picoCTF{l3arn_th3_r0p35}`

