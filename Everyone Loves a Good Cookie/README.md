Cookies are used by websites to keep track of user sessions and help with authentication. Can you spot the issue with [this site](https://metaproblems.com/e7fce2f2fcac584b49fe615b11784ff3/) and convince it that you're authenticated?

The problem is fairly straightforward. Submit a random code. Then the server adds a cookie to the browser. The value is set to `0` since I was not authenticated. Change the value from `0` to `1` and reenter the page. The site is tricked. 

![before](./before.png)

![after](./after.png)

