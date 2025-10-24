
27. No, the patterns aren't the same as before, but it feels like a continuation of the previous pattern

28. The fill method from the java.util.Arrays class is used in the reset() method to set all the elements of the state array to a specific value, which is 0 in this case.

29. The patterns are deterministic, because the automaton will always "grow" in the same way, just like I mentioned in question 27

31. We created a new array so that updates won't interfere with each other. If we changed the state directly, we'll get the wrong results because we'd be using some already updated values while we're still calculating with the old values.

35. Since each cell can be 0 or 1, and it depends on three inputs, there are a total of 8 possible combinations. We know that each combination either produces a 0 or a 1 as its next state, which means that the total amount of rules should be 2 to the power of 8, which is 256.
