#Algodetial

The player finally decides to run at x + x_delta when he sees the curve to x

The odds
0.99 / [1 - (x + x_delta)]

Conditional probability
[1- (x+x_delta)] / [1- x]
=
(1-x-x_delta)/(1-x)
=
1- x_delta/(1- x)

Conditions for EV value
=
Probability * conditional probability
=
0.99/[1- (x+x_delta)] * [1-x_delta/(1-x)]
=

EV value = conditional EV value * the probability that the player sees x
=
0.99 / [1 - (x + x_delta)] * [1 - x_delta/(1 - x)] * (1 - x)
=
0.99/(1-x-x_delta) * (1-x-x_delta)
=
0.99
