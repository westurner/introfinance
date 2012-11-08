Introduction to Finance
^^^^^^^^^^^^^^^^^^^^^^^
____ _____ ? (THANK YOU!)

1.1
++++
Value Creation
===============
- Time
- Uncertainty

Syllabus
=========
- 2wks: time value of money
- 2wks: decision criteria
- 2wks: Bonds & Stocks
- 2wks: uncertainty & risk
- 1wk: sigma
- 1wk: exam

Philosophy
===========
- not as much the how, but the why
- collective exercise, but you do the work
- 5-10 hours a week

1.2
+++
Prerequisite Knowledge
=======================
- Economics
- Math/Statistics
- Accounting
- Excel/Calculator
- Curiosity, desire to learn

Foreward
=========
- Markets are not perfect
- Intertia: Frictions are small relative to the power of most good ideas
- Capital can flow (relatively) easily

- the "why" first, the "how" (calculator) later

1.3
+++
The Essence of Decision Making
===============================
- virtually every decision involves time and uncertainty
- important to understand impact of passage of time on a decision

Terminology
============
PV
    Present Value ($)
    PV = FV*(r + 1)**(-p)
FV
    Future Value ($). Initial Value + Accumulated Interest
    FV = P + r*P = (1+r)**p
n
    # Periods (or 't')
r
    Interest Rate (%) > 0 (assumption)

Importance of Timelines
========================
:: 
  0   1   2   3   ...
  PV              FV

Main Insight
=============
*A dollar today is worth more than a dollar tomorrow.*

Example
--------
Suppose a bank pays 10% interest rate per year. You are given two choices:

a. receive $100 today
b. receive $100 one year from now

Which would you prefer?
    today. reason: interest (greater FV: $100 * 1.10 > $100)

1.5
+++
Future Value
=============
What is future value of $100 two years from now?
Period: 1 year --> two periods

Example 1
----------
FV @ 2 years = $121
  $100 * 1.10 = 110
  $110 * 1.10 = $121
  $121 = $100 * 1.10^2

Example 2
----------
- Initial Value = $500
- Interest Rate = 7%/year
- What is the FV @ 10 years?

ans = 500*(1+0.07)**10; print(ans)
ans = 983.5756

Example 3
-----------
What are the future values of investing $100 at 10% versus 5% for 100
years?

ans10 = 100*((1+.10)**100)
ans5 = 100*((1+.05)**100)
answer = ans10-ans5
print(answer)
assert answer == 1364911.102

Present Value
==============

pv = fv*(rate + 1)**(-nper)

