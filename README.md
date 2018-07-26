## Restart

### What is it?
Main idea is create a subprocess to run the real job. the main process monitor it, restart it if err happen, or kill it after a while.

And you can add more logic to contol the subprocess.

### Why we need this?
we all know write a nevery stoped program is almost impossiple. if we can promiss our program(like a spider) can work for a wheal, then we restart it if it crash, that will make us happy.

### I want more, do it in bussiness project
while, syou can use something else like `supervisor`, but i just want a simple `main` bin file.

### Add feature your self. like ...... 
You can write a Runxxx function, i like to merge your RP.
enjoy!
