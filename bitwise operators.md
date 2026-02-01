## Bitwise Operators :
> &,/,^,~,<<,>> are the available operators.
> Except ~ rest all others operators are binary.
> ### & : Bitwise AND 
> ### / : Bitwise OR
> ### ^ : Bitwise XOR
> ### ~ : Bitwise NOT
> ### >> : Left Shift
> ### << : Right Shift

int a,b,result;
|    a    |    b    |   a&b   |   a/b   |   a^b   |   ~a    |    ~b   |
|---------|---------|---------|---------|---------|---------|---------|
|    0    |    0    |    0    |    0    |    0    |    1    |    1    |
|    1    |    0    |    0    |    1    |    1    |    0    |    1    |
|    0    |    1    |    0    |    1    |    1    |    1    |    0    |
|    1    |    1    |    1    |    1    |    0    |    0    |    0    |
|---------|---------|---------|---------|---------|---------|---------|

### ~ :
#### int a=5;
#### b=~a; // b=-(a+1);
#### b=-6;

### << : It shifts the variable positions towards left.
*Eg:* a=10;
c = a<<2; a  = 10  
|  8  |  4  |  2  |  1  |   
|-----|-----|-----|-----|
|  1  |  0  |  1  |  0  |    // binary conversion

c = a<< 2
| 32  | 16  |  8  |  4  |  2  |  1  |
|-----|-----|-----|-----|-----|-----|
|  1  |  0  |  1  |  0  |  0  |  0  |   c = 40;
### in simple format its a*(2^2);

### >> : It shifts the variable positions towards right.
*Eg:* a=10;
c = a>>2;
### in simple format it is a/(2^2);
