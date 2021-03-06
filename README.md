# Jimat-Senang-Kira
The rounding mechanism only applies to the total amount of a bill and not on individual items. Under this exercise, the total amount of a bill inclusive of tax, which ends in 1, 2, 6 and 7 sen will be rounded downwards to the nearest multiple of 5 sen while the total bill which ends in 3, 4, 8 and 9 sen will be rounded upwards.

### Note
* Tested and compiled successfully on Ubuntu 16.04
* Replace line 25 with ```system("cls");``` on Windows platform.
* To compile and run on Linux platform, use this line of command

     ```g++ main.cpp -std=c++11 -o jimat && ./jimat```

### Usage
```void JSK(std::string stringTotalBill)```

Main function that takes a parameter of string(user's input), the function will then compare the last index of the string in order to decide whether to :
1) Round up or round down
2) To which multiple of 5 sen
3) Do nothing

### Table taken directly from https://github.com/comradesharf/Jimat-dan-SENang-Kira
<table>
  <tr align="center">
    <td rowspan="2">Bill end in sen</td>
    <td rowspan="2">Round off to the nearest 5 sen</td>
    <td colspan="2">Total</td>
  </tr>
  <tr align="center">
    <td>Total amount before rounding</td>
    <td>Total amount after rounding</td>
  </tr>
  <tr align="center">
    <td rowspan="2">1, 2</td>
    <td rowspan="2">Down</td>
    <td>82.01</td>
    <td>82.00</td>
  </tr>
  <tr align="center">
    <td>82.02</td>
    <td>82.00</td>
  </tr>
  <tr align="center">
    <td rowspan="2">3, 4</td>
    <td rowspan="2">Up</td>
    <td>82.03</td>
    <td>82.05</td>
  </tr>
  <tr align="center">
    <td>82.04</td>
    <td>82.05</td>
  </tr>
  <tr align="center">
    <td rowspan="2">6, 7</td>
    <td rowspan="2">Down</td>
    <td>82.06</td>
    <td>82.05</td>
  </tr>
  <tr align="center">
    <td>82.07</td>
    <td>82.05</td>
  </tr>
  <tr align="center">
    <td rowspan="2">8, 9</td>
    <td rowspan="2">Up</td>
    <td>82.08</td>
    <td>82.10</td>
  </tr>
  <tr align="center">
    <td>82.09</td>
    <td>82.10</td>
  </tr>
</table>

## Screenshot
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/1.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/2.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/3.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/4.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/5.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/6.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/7.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/8.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/9.png?raw=true)
![image](https://github.com/shinjiat/Jimat-Senang-Kira/blob/master/screenshots/10.png?raw=true)

