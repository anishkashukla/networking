# Subnetting

The word subnet is short for sub network which means a smaller network within a larger one.

It is basically breaking down a large network into smaller networks or subnets. It is done to make the website more manageable.

Subnetting is basically done by changing the default subnet mask by borrowing some of the bits that were designated for host and using them to create subnets.

For ex :

Class B IP address : 173.16.0.0.

Class A IP Address : 255.255.0.0

In this, 255.255 is the network portion and 0.0 is the host portion.

If we want to break down this network into smaller ones, the formula is 2^n-2 where n is the number of bits we need to borrow from host portion of a subnet mask.

We need to make a custom subnet mask that is equal to atleast 3 subnet mask.

We need to make a custom subnet mask that is equal to atleast 3 subnets or larger.

We know the formula- 2^n-2.

In this, if we take n=2 then it is not going to work because we need atleast 3 subnets.

2X2=4-2=2

For n=3,

2X2x2-2=8-2=6

Therefore,

255 .255 .0 .0

11111111.11111111.00000000.00000000

In this, we will borrow 3 bits from host portion i.e. 000 of first 0.

After borrowing, we will get 1 in place of 0.

Therefore we get –

11111111.11111111.11100000.00000000

255 .255 .224 .0

It would give us 8 thousand hosts per subnet and now the network is broken down into 3 subnets.

Now, the computer is broken down into 3 subnets.

