# First iteration in order to model the subdomain of the checkout in a supermarket

The first problem I encounter was to limitate the domain of the problem which is *Pricing goods at supermarkets*. Why?, Because there is data like product stock or taxes that are shared betwween diferents departments or subdomains and/or are part of an external API.

The tool I will use for solving this problem is event storming and DDD.

This branch is a first iteration to find a solution and consist of a strategy modeling of the bussiness domain as it can be seen in /pr1.png. Here I asumme the supermarket has a procurement department whom takes the pricing decisions.