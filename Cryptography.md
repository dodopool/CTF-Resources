# Cryptography 
## Finding Prime Factorization
The reason RSA Cipher is considered secure is because of the assumption that the problem of finding out the prime factors of a number $N$ is hard - there is no (known) polynomial time running algorithm that can factorize a given number $N$. 

However, if the number $N$ is small, we might be able to quickly recover its constituent prime factors. Below websites are helpful in performing this attack: 

 - [factordb.com](http://www.factordb.com/): An awesome site that can be used to quickly look up the prime factorization of a lot of numbers. 
 - [alpertron.com.ar](https://www.alpertron.com.ar/ECM.HTM): This site provides an excellent calculator that can be used to find out the prime factorization of a number. 
## Finding out Discrete Logarithm 
The security of the Diffie-Hellman key exchange protocol relies on the hardness of the discrete logarithm problem for certain fields. We don't know (yet) algorithms that, when given numbers: 

$p$ = Prime Number

$g$ = Generator (or Primitive Root) of the field $\mathbb{F_p}$

$A$ = $g^a \mod p$
 
can find out the integer $a$ quickly. However, one might be able to compute $a$ if the above parameters are chosen carelessly. Below website can be used to find out the discrete logarithm in such cases: 

 - [alperton.com.ar](https://www.alpertron.com.ar/DILOG.HTM): Useful for computing Discrete Logarithm.  



