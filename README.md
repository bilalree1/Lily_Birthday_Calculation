# Lilly's Washing Machine Savings Problem

A simple console application written in C# that helps determine whether Lilly can buy a washing machine with the money she saves and earns from selling toys over the years.

## Problem Description

Lilly receives money on her **even birthdays** (starting from age 2) and toys on her **odd birthdays**.  
- On even birthdays she gets **$10 more** than the previous even birthday (10, 20, 30, …), but her brother takes **$1** from that amount.  
- On odd birthdays she gets a **fixed amount** from selling the toys she received.  
- She wants to know if, by her birthday at age **N**, she has enough money to buy a washing machine of a given price.

This program calculates her total savings and compares it with the washing machine price.

## Features

- Takes 3 inputs from user:
  - Lilly's age (N)
  - Money received per toy sold (fixed amount on odd birthdays)
  - Price of the washing machine
- Calculates total money saved
- Tells whether she can buy the machine and shows:
  - Remaining money (if she can buy)
  - Shortfall amount (if she cannot buy)

## Sample Input / Output

**Input:**
