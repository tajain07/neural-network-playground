# Padding

![Padding_andrew_ng](https://github.com/tajain07/neural-network-playground/blob/master/padding_1.png?raw=true)

Input Pixel = (n * n) |  (6 * 6)

Filter/Kernel = ( f * f) | (3*3)

**Output Pixel = (n-f+1 * n-f+1) | (4*4)**

### Why padding?

* Shrinking ouput
* throw away info from edges ( edge pixel is considered less compared to pixel in center)



# Valid and Same convolutions

![padding_andrew_ng_2](https://github.com/tajain07/neural-network-playground/blob/master/padding_2.png?raw=true)


* **Valid** : no padding
  >n * n (conv.) f* f --> n-f+1 * n-f+1

  >6 * 6 (conv.) 3 * 3 --> 4 * 4
            
* **Same** : Pad so that output size is ***same*** as the input size.
  > n+2p-f+1 = n --> p = (f-1)/2
  Input = 6 * 6 
  Filter = 3 * 3  | 5 * 5
  Padding = f-1/2 = 3-1/2 = 1  | (5-1)/2 = 2
  
  **f is usually odd** 
    > if f is even - then assymetric padding, 
    i.e. pad more on left than on right
    > odd f has central position  
