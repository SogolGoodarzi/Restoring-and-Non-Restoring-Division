# Restoring-and-Non-Restoring-Division

In division operation, we divide a dividend called x by a divisor called d. So, we have a quotient called q and a remainder called w. So, we have:

![image](https://github.com/SogolGoodarzi/Restoring-and-Non-Restoring-Division/assets/125180530/f736eb5c-51b2-4c98-9f60-99ebf48a8256)

![image](https://github.com/SogolGoodarzi/Restoring-and-Non-Restoring-Division/assets/125180530/81e95ea3-64ad-435c-997a-7f9be1bcf378)

Assume that the dividend is 2n bits and the divisor, quotient, and remainder are n bits. 

For dividing two numbers there is two methods:

* Restoring Division
* Non-Restoring Division

### Restoring Division
The algorithm is as follows:

![image](https://github.com/SogolGoodarzi/Restoring-and-Non-Restoring-Division/assets/125180530/bff0c7fb-c873-4ebb-a354-fea5cc0e721d)

We can simplify the above algorithm so that it's functionality becomes faster. In this case we have:

![image](https://github.com/SogolGoodarzi/Restoring-and-Non-Restoring-Division/assets/125180530/5a28e7f1-e4a1-404f-955e-f8d4731e64e7)

### Non-Restoring Division
The algorithm is as follows:

![image](https://github.com/SogolGoodarzi/Restoring-and-Non-Restoring-Division/assets/125180530/cf511d13-ecba-49fd-92cd-ea1b7aa7e1f7)

You can find Verilog files and the datapath and controller files attached. 
