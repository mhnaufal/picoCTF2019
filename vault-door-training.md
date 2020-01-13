# vault-door-training
Reverse Engineering - 50 points

## Description
Your mission is to enter Dr. Evil's laboratory and retrieve the blueprints for his Doomsday Project. The laboratory is protected by a series of locked vault doors. Each door is controlled by a computer and requires a password to open. Unfortunately, our undercover agents have not been able to obtain the secret passwords for the vault doors, but one of our junior agents obtained the source code for each vault's computer! You will need to read the source code for each level to figure out what the password is for that vault door. As a warmup, we have created a replica vault in our training facility. The source code for the training vault is here: [VaultDoorTraining.java](https://2019shell1.picoctf.com/static/4ca411ae55cbf37cfae55ee83477a0dc/VaultDoorTraining.java)

### Hint 
The password is revealed in the program's source code.

## Solution 
Based on the hint given, the flag is in the .java source code. We can open it using any text editor but two of the commonly used linux text editor are **vim** and **nano**.

```
vim VaultDoorTraining.java
```
or
```
nano VaultDoorTraining.java
```

Flag : `picoCTF{w4rm1ng_Up_w1tH_jAv4_87f51143e4b}`
