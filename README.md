
# Simple calculator app 

This project is part of Meta's "React Basics" course. They gave us a template to create a simple calculator app — and it's very, very simple. Baby, even. The functionality of the calculator isn't entirely there. For example, the steps to print the result for `1 + 15` are: 

1. Type `1`.
2. Click `Add`. Your result updates to `1`.
3. Type `15`.
4. Click `Add` again. Your result updates to `16`. 

If you press enter, though, the result resets back to `0`.

This is confusing. Let's look at what happens when we use the `multiply` and `divide` functionality. If I want to multiply `15 * 2`, the steps I would take are: 

1. Input the number `15`.
2. Click `add`. This prints the result `15`. 
3. Input the number `2`
4. Click `multiply``.
5. Result prints. 

Given how simple this calculator is, it seems like the logic works like this:

* Result always defaults to 0. 
* To complete a new operation, you have to add the value to the default 0, hence always needing to click `add` after your first input. 
* If you want to multiply `15 * 2`, then the actual operation under the hood is `0 + 15 * 2`.

Obviously, you wouldn't want to use this app to do something financially urgent.

## Stylizing the app

I'm not a developer, but I do like making things cute. I spent more time stylizing the app itself than I did optimizing the actual app —  I know, I know. But I figured since I completed the assignment, I could do something fun for me. You can look at my code comments to see how I grouped the different buttons and why I chose the formatting I did. There are some things I wanted to do that I wasn't able to.

* I wanted to make this a Sailor Mercury-themed calculator, hence the color palette.
* I had an image that I wanted to anchor behind the app component at the lower-right of the webpage. It was cute! It would've been cute! 
* Since this app uses the `create-react-app`, which isn't supported afaik, I lacked ~things~ to make this happen. This might answer your question why I have so many packages installed. `0:-)`
* I tried different kinds of functions and CSS magic and yadda yadda, but the image only ever loaded in a broken way... if it didn't break the app altogether.
* Eventually, I accepted that if I want to make a cute webpage, then I should probably start my own project and move on from this one. 

## The easy and the difficult

I'll admit that I initially struggled a bit with reading the template code. I use React at work so am familiar with different React ~things, but I have pretty limited JavaScript. I can edit existing JavaScript code, but a concrete understanding of what does what and why isn't entirely there. I grokked it, though. After I read through the template a few times, it clicked and realized I had overcomplicated the project too much, lol. Typical. The easiest part was then just filling in the blanks that Meta left for us to do. I also thought stylizing the calculator was pretty straight forward, too... I have a lot more HTML/CSS experience than I do anything else, though.

The other hard part for me was figuring out packages. Obviously `create-react-app` isn't the best to use. I also use VS Code and GitHub at work fairly often and wanted this work reflected in a repo. Breaking apart all the packages I needed and getting the preview to build was a huge headache. In any case, by the second or third try I figured it out and am pretty confident I know exactly what steps to take to start a new project in the future. 

## Conclusion

Anyway, cheers.