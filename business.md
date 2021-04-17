# Code and the Business

## The Goal: Solve the Business Need
We write code to solve a business need. Someone hired you to solve a difficult
problem by programming. At the end of the day, that's what is important. You 
can write an extremely elegant algorithm to sum up all the numbers from 1 to 100
but if it doesn't solve a business need, it isn't important.

That is not to say _you shouldn't be proud of what you write_. Take pride in
your work. I've spent hours thinking about complex business issues and love when
I find elegant solutions; _*solutions to business problems*_.

When we talk about system design, I'll mention a bit of code called _Business
Logic_. It is named _business logic_ because it's important to whatever business
you are in. Think of this code as your source of truth. You can put it into an
API or run it as a nightly batch job to train a model. At the end of the day,
it solves a business need.

## Code and Product
If possible, don't write any code. That's typically not possible, so strive to
write the bare minimum to solve the problem. There's a principle known as
_You Ain't Gonna Need It_ (YAGNI). That is, you should be writing the exact
amount of code needed to solve the problem; anymore _maybe_ a premature 
optimization.

Now, you are probably thinking:
> What if I have this great product idea and I can implement that at the same time?

That's great. Take a note of it, and backlog it. If you have a project manager,
tell them about it. That idea could help shift the product's roadmap later on.
Unless the client asked for the feature, it is superfluous _right now_.

Your goal is to get the feature to the client ASAP, and any extra features risk
slowing that process down. 

### Product's Goal
_It is product's mission to determine what you build, not how you build it._
