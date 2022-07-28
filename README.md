# 🔢 #100Devs Push Project001: Calculator

### Goal: Build a Simple Calculator using JS OOP best practices

### What it should look like:

![Calculator](calculator.jpg)

### How to submit your code for review:

- Fork and clone this repo
- Create a new branch called answer
- Checkout answer branch
- Push to your fork
- Issue a pull request
- Your pull request description should contain the following:
  - (1 to 5 no 3) I completed the challenge
  - (1 to 5 no 3) I feel good about my code
  - Anything specific on which you want feedback!

Example:
```
I completed the challenge: 5
I feel good about my code: 4
I'm not sure if my constructors are setup cleanly...
```
# Calcy 386

This Object Oriented Calculator App was built as a challenge from #100Devs

Link to project: https://calcy-386-basic-calculator.netlify.app/
![calcy386](https://user-images.githubusercontent.com/85075266/181394996-dcbd500d-0b66-4f11-90e0-0f7beb2ff9bf.png)



## How It's Made:
<br/>
Tech used: HTML, CSS, Javascript

the calculator is an object, with all functions inside as properties or methods of the object.

## Optimizations
<br/>
I switched out .eval() for .function() based on recommendations over security of it, eval is depreciated and not used anymore.

I got user feedback on the calculator, adding in a sub-display that shows the calcluation chain based on what people said when they used it.

## Lessons Learned:
<br/>
I was happy with the look and feel of the calculator, making it look and sound good motivated me to put extra work into it.

Before using methods, I need to check them out in more detail first - just because it works doesn't mean it's the best solution.

The calculator performs badly at odd resolutions, and not at all on mobile, with future work I would go into the media queries with
more detail making it look better at a range of different shapes and sizes.
