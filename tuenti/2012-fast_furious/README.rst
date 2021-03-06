20 fast 20 furious
==================

Description
-----------

Everybody loves to go karting with friends. We are opening our very own Tuenti
Karting Circuit and we need you to use your programming skills and help us
figure out how much gasoline we must buy each day.

We have exactly ``k`` karts and a few groups of people using the circuit all
day. We need to buy 1 liter of gasoline per kart used per race.

1. Before a race starts, groups are being seated one at a time until there are
   no more groups waiting or there are not enough karts for the next group.
2. Then the race starts, whether all the karts are being used or not.
3. When the race finishes they wait again in the same order until the day is
   over.

Every day we have exactly ``R`` races.

For example, imagine that we have ``k=6`` and ``R=3``, and there are five
groups of people with sizes: 1, 2, 4, 3, 1. The first time the race goes, the
first two groups [1, 2] will ride, leaving three empty karts (the group of 4
should wait, and the group of 3 cannot go ahead of them). Then they will go to
the back of the line, which is now 4, 3, 1, 1, 2. The second time, the circuit
will hold 4 people: [4], leaving 2 empty karts. Now the line is 3, 1, 1, 2, 4.
The third time, it will hold 5 people: [3, 1, 1]. Since we need exactly one
liter for each kart's ride, it is 12 liters of gasoline.


Input
-----

The first line gives the number of test cases ``N``. Each test case has two
lines. The first line contains three integers ``R``, ``k`` and ``G``. ``G`` is
the number of groups.  The second line is the list of sizes of the groups, so
this list has exactly ``G`` integers.


Output
------

The number of liters of gasoline for each test case
