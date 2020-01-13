# practice-run-1
Binary Exploitation - 50 points

## Description
You're going to need to know how to run programs if you're going to get out of here. Navigate to /problems/practice-run-1_0_62b61488e896645ebff9b6c97d0e775e on the shell server and run this [program](https://2019shell1.picoctf.com/static/6eba3b66e7a2b786c6c9769711d85663/run_this) to receive a flag.

### Hint 
How do you execute a program in a command line?

## Solution 
After download the file you cant directly run it with `./file` command. First you have to change the permission to run the program using `chmod` (change mode) command.

```
chmod +x run_this
```
the +x mean:
* + : You want to **get permission**
* x : stands for **executable** (execute the program)
or if we put the together +x mean *I want to get permission to run/execute that program.* You can check another flags option in `man chmod` 

```
./run_this
```
`./` is linux command to run a program

`picoCTF{g3t_r3adY_2_r3v3r53}`
