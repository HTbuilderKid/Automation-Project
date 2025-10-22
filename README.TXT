
27. No, the patterns aren't the same as before, but it feels like a continuation of the previous pattern

28. The fill method from the java.util.Arrays class is used in the reset() method to set all the elements of the state array to a specific value, which is 0 in this case.

29. The patterns are deterministic, because the automaton will always "grow" in the same way, just like I mentioned in question 27

31. We created a new array so that updates won't interfere with each other. If we changed the state directly, we'll get the wrong results because we'd be using some already updated values while we're still calculating with the old values.
