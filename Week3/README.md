# Week 3

Note: Use the [developer documentation](https://developer.servicenow.com/app.do#!/api_doc?v=helsinki&id=server) to find more ways to solve these problems

1. Find how many incidents are open. (hint: there is an easier way than looping through all the records in the developer documentation)
2. How many are open in the `Software` category?
3. What are all the different category options? (hint: GlideElement docs are your friend)
4. How many incidents have a `Problem` associated with it?
5. How many have VIP Callers? (hint: you can dot-walk in queries)

There are multiple ways to solve these. Try not to use addEncodedQuery :). Bonus points if you use GlideAggregate.
