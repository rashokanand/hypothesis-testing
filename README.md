# Hypothesis Testing Reflections
This testing is used to test whether the sample statistic that we obtained shows evidence that the our null hypothesis is not true, and it can be rejected. Without this contradictory evidence, the null hypothesis is assumed to be true. This sets up the understanding that the null hypothesis is the status quo, the standard assumption. 
The null hypothesis and alternate can be better understood by the judicial example. The statement 'All are innocent until proven guilty', perfectly sums up the null hypothesis. Initially everyone are assumed to be innocent. This is the null hypothesis. The alternative is that the person is guilty. Now we need to acquire enough evidence to show that the null is not true, and reject it in favour of the alternate hypothesis showing that the accused is guilty.

## Errors in hypothesis testing:
### Type 1
The accused is in realitiy innocent, but the jury convicts him.
Null is actually true, but incorrectly the null is rejected in favour of the alternate.

### Type 2
The accused is in reality guilty of the crime, but the jury acquits him.
Null is in reality not true, but due to not enough evidence, we fail to reject the null. 

Type 1 is the worst form of error. It is also known as 'False positive'
Type 2 error is also known as 'False Negative'

Normally since the Type 1 error is the worst form of error in hypothesis testing, the maximum allowable type 1 error rate is fixed. Then the other error rate is minimized based on this. 
The fixed type 1 error rate is normally notated using the greek letter alpha. α
The type 2 error rate is β. Power of a test is commonly calculated as 1 - β .

## Uses

- Normally Hypothesis testing is used in A/B Testing. (If not A, then B?)
- Testing whether a treatment (drug?) had a sufficient impact in treating a disease in a control group
- Checking the statistical significance in any test environment.