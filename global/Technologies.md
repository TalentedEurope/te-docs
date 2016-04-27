# Tecnologies

This document is a summary of Talented Europe technology stack.

## Web application

**Laravel:**

We’ve been heavy Django users in the past and learned a lot from the community and the vast amount of top notch documentation it provides. But sadly Django upgrade path is, to put it nicely 'annoying', plus we needed a lot of 3rd party libraries to achieve what we needed on this project. 

Laravel on the other way is fresh, stable, nicely documented (even better than Django) and covers almost out of the box all our requirements for Talented Europe.

**PHP**

PHP is our language of choice for backend code. It is probably the most boring choice in our stack. PHP offers great libraries and a has been evolving lately into a way better language than it used to be. Plus there's a healthy community that cares about documentation and stability.

Plus it offers us high compatibility, which helps to lower our maintenance costs.

**MySQL/MariaDB**

Just to clarify, we're building the application as database agnostic as possible, so it should work with PostgreSQL or others without issues. We're choosing MySQL basically because *It just works™*. What we mean, is that it delivers the performance and features we need and almost all shared hosting

**Vue.js**

We’ve been using vue since the early betas. It is *'somewhat similar'* to the other major JS frameworks, but unlike those it gives us more flexibility. Just as an example, for prototyping small things, we can just pull it from the CDN and start working with it, without any heavy tooling like it happens with for example React.

It's also very nice documented, and just to give a few examples it's used on the Facebook NewsFeed Marketing Site, interactive experiences like YouTube Adblitz, or projects like Statamic or Pagekit.

**ES6**
While we're fans of Javascript, ES6 gives us a better tooling which helps us to maintain better clarity codewise, And in the end it's the future of javascript and since this is a long term project, we think it's better to go bleeding edge in those aspects, to avoid having to maintain *old stuff* in a few years.

**Debian**

While things like Ubuntu Server are nice and have a lot of bleeding edge technologies, we're fan of rock solid servers and thats where debian comes in. It's a good mix of stability and modernity.