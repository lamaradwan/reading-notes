# Class-16
## I’ve reviewed the following topic:

1. Serverless Computing
Serverless is essentially a pricing model. The cloud vendor determines how many servers you need, and you only pay for actual consumption.

That’s not why developers love it, though. The reason it’s so great for us is that it introduces an additional abstraction layer.

It’s no small thing that’s abstracted away, either. In one sweep, you can remove all the hassle of managing your servers, as well as a ton of boilerplate glue code. Basically, many of the boring parts of software engineering go away. And it’s cheaper.

In the old days, you had to set up your own servers. It was all a big hassle. You needed space for your racks and cooling. You needed to take care of networking and security. It was expensive, inflexible and time-consuming. It all needed to be planned, and it probably involved lots of different people with different skillsets.

Then came the cloud, and everything became a lot simpler. All of a sudden, a single developer could easily spin up a virtual machine in a matter of a few minutes. It was cheaper, too. If you no longer needed the server, you just took it down.

All of that is great for operations. It’s good for developers too, but it doesn’t really change the way you write code.

Enter serverless, where instead of virtual servers, you have an entire server farm at your disposal, ready to run your code. You hardly have to think about scale. Not only that, but the functions you write come with preconfigured bindings to other services, meaning that you hardly need to write any CRUD code. No more data access layers or service layers. You basically just write the business logic. The fun parts.

Those who like microservices, generally love serverless. Now you can write nanoservices, because the overhead of introducing an additional service is reduced to a minimum.


