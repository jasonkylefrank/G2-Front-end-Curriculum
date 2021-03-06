##Why do big-name companies use React?

In the previous section, we saw that many companies are using React.  In this section we will look at *why* some of those companies chose to use it.  

Note that just because other companies chose to use this technology does not mean it is a good fit for us.  See the "[Why React?](../why-react.md)" section for discussion and resources about why our team benefits from using this technology. 

### Why **Netflix** uses React

Netflix [likes React](http://techblog.netflix.com/2015/01/netflix-likes-react.html) because of its **performance**, **scalability**, and **compositional design patterns**.  In [this talk](https://www.youtube.com/watch?v=g01dGsKbXOk&list=PLRHV6us9ju3S5SSEVzjkBWEpHDrMn_Az4&index=12) they have also reported that it is:
* A clean, readable architecture
* Faster to bring people up to speed
* Faster to add features

### Why **Yahoo Mail** uses React

When Yahoo mail [revamped their front-end](http://yahooeng.tumblr.com/post/101682875656/evolving-yahoo-mail), they wanted:
* Predictable flow ~ Easy Debugging
* Independently deployable components
* Shorter learning curve 
* No dependency on large platform libraries

They evaluated Ember.js, Angular.js, Knockout.js, Durandal, Rivets, and React. They chose React. They said that it "felt like a good solution to make debugging and understand data flows much easier and predictable". 

### Why **Atlassian** uses React

Atlassian, makers of Jira, BitBucket, and HipChat, also considered Angular and Ember. They [chose React](https://developer.atlassian.com/blog/2015/02/rebuilding-hipchat-with-react/) because they believed it had several advantages.  A few they cited include:
* Its focus on **Components**: they cited being able to share code with native clients (desktop apps, mobile apps)
* React's **Virtual DOM** speed
* **Simplicity**: "The public API can be memorized in a day and once you've built your first component, it's easy to build the next one with confidence that it'll just work."
* **Unidirectional data flow**: "The benefit of this is that you know exactly where your data is mutating, making it easier to test and maintain your app."
* **Testability**: "React components simplify testing greatly. As a proof of it's simplicity, our new web client has more tests than any of our other clients."

Regarding sharing code with native clients, they are referring to one of React's unique advantages: [**React Native**](https://youtu.be/KVZ-P-ZI6W4?t=1035).  This allows them to create truly native apps using their React components.  They explain that, "This means all of the complex logic of managing message rendering, history fetching, user states, scrolling animations and state management will all be handled by React — **greatly simplifying our native client code**."  They go on to say that, "The **dev speed** we've gained with React+Flux (and its friends: gulp, webpack, lodash, karma) proves that we can release new client features faster and with more confidence on this platform than on any native client."

### Why **Rally** (CA Technologies) uses React

At the moment I did not find a great resource that focused on *why* CA Technologies chose to use React, but I can recommend [this video](https://www.youtube.com/watch?v=nQo0EdHNjto) by one of their developers.  He talks about what they've learned from the trenches while creating a React UI component library for use in their products.  

