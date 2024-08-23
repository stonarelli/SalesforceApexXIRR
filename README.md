# Salesforce Apex XIRR
XIRR (Extended Internal Rate of Return) is a financial metric used to calculate the annualized return of a series of cash flows that occur at irregular intervals. Unlike the regular Internal Rate of Return (IRR), which assumes that cash flows are received at regular intervals, XIRR accounts for cash flows that may be irregular in timing.

## Key Points About XIRR:
**Annualized Return:** XIRR provides the annualized rate of return, making it easier to compare with other investments.
**Irregular Cash Flows:** It can handle cash flows that are not evenly spaced in time, which is common in real-world investments.
**Use Cases:** XIRR is particularly useful for evaluating investments like private equity, venture capital, or any scenario where the timing of cash flows is unpredictable.

## Example:
Imagine you make an investment of $1,000 on January 1, 2022, receive $500 on June 30, 2022, and another $700 on December 31, 2022. The XIRR would tell you the annualized return rate that equates the net present value of these cash flows to zero.