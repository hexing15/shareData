# Data Structure

The data is organized as follows:

- The first line contains four numbers, representing `$|P|$, $K$, $T$, $C$ respectively.
- The following $n$ lines represent the departure information for $n$ orders.
- Each of these lines contain four numbers, representing:
  - The $x$ coordinate of the departure point
  - The $y$ coordinate of the departure point
  - The capacity requirement of the order, $q_i$
  - The latest completion time of the order, $L_i$
- The remaining $n$ lines represent the arrival information for $n$ orders.
- Each of these lines again contain four numbers, representing:
  - The $x$ coordinate of the arrival point
  - The $y$ coordinate of the arrival point
  - The capacity requirement of the order (which is $-q_i$)
  - The latest completion time of the order, $L_i$