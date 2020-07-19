# BigInteger-C++-


Hello folks, we all must have been facing issues while dealing with operations on very large numbers, though some programming languages like  python,Java provide built int libraries to use big integers, but thats not the case with C++.

I use typedef vector<int> BigInt; to make one BigInteger

I use only with positive numbers.

In my code have the functioninitialize one BigInt :


BigInt a = Integer(string);

BigInt a = Integer(char[]);

BigInt a = Integer(int);

BigInt a = Integer(long long);


I have function print one BigInt :

Print(BigInt);

I have iostream BigInt : NEW

cin >> BigInt;

cout << BigInt;


I have operators on BigInt : have NEW

BigInt + BigInt   (the value return is BigInt)

BigInt + int      (the value return is BigInt)

++BigInt          (the value of BigInt set to BigInt+1 and the value return is BigInt)

BigInt += BigInt  (no return value)

BigInt += int     (no return value)

BigInt - BigInt   (the value return is BigInt, that is positive numbers)

BigInt - int      (the value return is BigInt)

--BigInt          (the value of BigInt set to BigInt-1 and the value return is BigInt)

BigInt -= BigInt  (no return value)

BigInt -= int     (no return value)


BigInt * BigInt   (the value return is BigInt)

BigInt * int      (the value return is BigInt)

BigInt *= BigInt  (no return value)

BigInt *= int     (no return value)


BigInt / BigInt   (the value return is BigInt)     (need optimal)

BigInt / int      (the value return is BigInt)     (NEW - quickly)

BigInt /= BigInt  (no return value)

BigInt /= int     (no return value)


BigInt % BigInt   (the value return is BigInt)

BigInt % int      (the value return is int, that is in [0..int-1])

BigInt %= BigInt  (no return value)

BigInt %= int     (no return value)


NEW : Compare 

         BigInt - BigInt
         
         BigInt - int
         

> , < , == , >= , <=  (the value return is bool) 


I have functions on BigInt :

max(BigInt, BigInt) (the value return is BigInt)

min(BigInt, BigInt) (the value return is BigInt)


gcd(BigInt, BigInt) (the value return is BigInt)

lcm(BigInt, BigInt) (the value return is BigInt)


sqrt(BigInt)        (the value return is BigInt)  

log(int, BigInt)    (the value return is int, log(int, BigInt) is small)
