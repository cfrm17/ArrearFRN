# Arrear FRN

A arrear forward rate agreement (FRA) is a forward contract in which the payoff payment date may not be the end of a forward period. It has been well known that a convexity adjustment must be considered in pricing a set-in-arrear forward rate agreement (FRA). It also becomes market convention to do so.

We use a very good approximation under the condition that the reset date of a floating index rate is very close to a payment date. In CAD, the reset date can be identical to the payment date. In other currencies, the reset date can be only two business days prior to the payment date. It must be noted that the reset date may not exceed the payment date and the payment date may not exceed the end date of the index forward period.

An FRA is a derivative of exchanging floating and fixed interests. An interest rate swap is a sequence of FRAs. Hence, it suffices to consider FRAs. Since it is straightforward to deal the fixed leg of a FRA, in this section if without further specification, a FRA just means a floating leg of the ordinary FRA.

Let τ be the length of an interest payment period. It should be noted that we do not specify an interest payment period but only specify the length of such a period. The reason is that it is the accrual period length which determines the interest payment amount. A vanilla FRA is a European derivative security, whose price process is denoted by cfra(t).

Comparing the coefficient in front of the curly bracket in (12) with the value of a regular FRA, we may see that the coefficient seems like the time-t price of the FRA if it is treated as a corresponding vanilla FRA. So, let us call this coefficient the vanilla price of the FRA. Clearly, when ˆt approaches t2, then σ -> 0, the FRA becomes the ordinary vanilla FRA and the vanilla price becomes the real price. 

A general FRA is a European forward rate derivative with a maturity which is not earlier than the beginning of the forward period. A vanilla FRA is the same type of security except its maturity is right at the end of the forward period. While, a set-in-arrear FRA is the one whose maturity is right at the beginning of the forward period. Generally, convexity adjustments are required for pricing these FRAs except vanilla FRAs. Under the assumption of single factor driving force, for a FRA whose maturity is before the end of the forward period, the convexity adjustment is positive while for a FRA whose maturity is after the end of the forward period, the convexity adjustment is negative.

References:

https://finpricing.com/lib/FiBond.html

https://derivatives.hcommons.org/fixed-income-instruments/
