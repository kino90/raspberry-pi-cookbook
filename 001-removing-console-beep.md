# 1. Removing console beep

You can shut the console beep, also called `errorbell`by editing the file `/etc/inputrc`. 

```
sudo nano /etc/inputrc
```

Find the `set bell-style` line and edit the value. 

## Values
Accepted values are `none`, `visible` and `audible`

- `none` - no errorbell
- `visible` - screen flashes, no sound
- `audible` - normal errorbell (beep)