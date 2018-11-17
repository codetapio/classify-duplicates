# Print list of duplicates

To run it from the CLI do:
```
node nice.js n=12345
```

![image](https://user-images.githubusercontent.com/1318985/48655258-a1ceec80-ea0c-11e8-9b9a-e7793384855a.png)

Run script with Object keys algorithm
```
node nice.js n=100000
Execution time is 0.0278 seconds
*************************************
Number of elements that repeat: 26457
```

Run script with filter ***indexOf*** and ***lastIndexOf***
```
node nice.js n=100000
Execution time is 5.4303 seconds
*************************************
Number of elements that repeat: 26389
```

Run script with filter algorithm
```
node nice.js n=100000
Execution time is 22.9527 seconds
*************************************
Number of elements that repeat: 26453
```