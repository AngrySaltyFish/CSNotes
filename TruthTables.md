# Truth tables

## Logic Gates


### Not Gate

             |  Q
             | 
             |
             -
            | |
             -
            / \
           /   \
          /     \
         /       \
        /         \
       /           \
      /             \
      ---------------
             |
             |
             | A

This gate inverts the input.

|   A   |   Q   |
| ----- | ----- |
|   0   |   1   |
|   1   |   0   |

              -
bolean logic: A

### And Gate

           :.............`                    
     A     :             `..`                 
    .......:                ..                
           :                 ..               
           :                  :     Q
           :                  :.......
           :                  :
     B     :                 ..               
    .......:                ..                
           :             `..`                 
           :.............`           

This gate requires both inputs to be true to output true

|   A   |   B   |   Q   |
| ----- | ----- | ----- |
|   0   |   0   |   0   |
|   0   |   1   |   0   |
|   1   |   0   |   0   |
|   1   |   1   |   1   |

boolean logic: A . B


### Or Gate

    
          yo+++++++:.                      
     A     -h       .:+o/`                  
    :+++++++h+          .oo.                
            `d            `s+       Q  
             d`             :h++++++ 
     B       m`            `y/              
    .:::::::/h            /y.               
    `       h-         -oo-                 
           os``..-/++++:                    
           ////::-


Requires one input to be true for the output to be true

|   A   |   B   |   Q   |
| ----- | ----- | ----- |
|   0   |   0   |   0   |
|   0   |   1   |   1   |
|   1   |   0   |   1   |
|   1   |   1   |   1   |


