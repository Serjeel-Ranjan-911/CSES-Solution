[problem](https://cses.fi/problemset/task/1131)

The solution can be broken down in two parts. 

    First for each subtree calculate the height of that subtree. This can be done with dfs in O(n)

    Once we have height of all subtree. Go to all nodes. For each node find the two child nodes with heighest heights. So the diameter will compose these two subtrees. Take the maximum of all possible diameters. 

Both parts can be done in one dfs call.