# Problem

# 1. What are the capacity usage patterns?

## From the barplot it can be interpreted that in most of **late_night** time there is a peak load conidtion , in the **early morning** majority of time there is an idle load condition, **evening time** has the highest traffic/peak load condition and at last in the **night time** most of the random times are in idle condition.

# 2. What do you infer from the missing timestamps?
## Much information can't be infered from the timestamp but it can be used to **determine the load variation at different randomm time points**

# 3. How would you solve this optimization problem - wherein at some time we’re overusing the capacity, and at other times, we’re under-using. How do we cut down on the extra costs that we end up paying either way?

## Approach to optimize this problem is to perform load shifting. Since the **night** time is mostly in idle conditon, we can shift the load from evening to that time period which will help in further reduction of the extra costs.

