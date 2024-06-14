---
layout: post
title: Some Advice for My Younger Self
date: 2024-06-14 01:07:17
description:
tags: swe
categories: software-engineering
giscus_comments: true
toc:
  sidebar: left
---

This is a small list of things I would tell my younger self entering the workforce. While I don't claim to be an expert today, I think I've picked up some insights that would have been beneficial to my younger self at the start of his journey into the software engineering industry.

## 1. You Don't Need to Know Everything

When I first started studying computer science in college, I felt like I needed to know everything to land a job. Then, when I started my first job, I felt like I needed to master every new technology and framework to feel like a "real engineer." The reality is that you don't need to know everything.

That being said, I _do_ think it's beneficial to have a surface-level understanding of various areas within this field. Take a look at [roadmap.sh](https://roadmap.sh/), and you'll see that there's no shortage of areas within software engineering to learn about.

This field is unique in that it seemingly changes by the hour, with new technologies to learn springing into existence _all the time_. It's important to cultivate a mindset of continuous growth and learning, and equally important to know and accept that you won't know everything. And that's okay.

## 2. Learn `git`

One of the very first things you should learn is how to version control your code. I highly recommend learning `git`. Not only is it by far the most popular tool for version control, [overtaking others by a large margin](https://openhub.net/repositories/compare), but it can (and will) save you a lot of headache throughout your career. **I never write code without version control.**

If you learn the basics of `git`, you'll be able to handle the following scenarios:

- Delete a file by accident? [You can get it back using `git checkout`](https://4ddig.tenorshare.com/windows-recovery-solutions/git-restore-deleted-file.html).

- Want to stash a small change to use (i.e. apply) later? [`git stash` is your friend](https://www.atlassian.com/git/tutorials/saving-changes/git-stash)

- Have a fancy new feature you want to work on without affecting existing stable code? [Create a new branch](https://www.atlassian.com/git/tutorials/using-branches) and work on that feature worry free.

These scenarios scratch the surface of what you can accomplish. You can spend months learning all the ins and outs of `git`, but at the very least, learn the basics. Learn how to commit changes, push and pull from a remote, work with branches, etc. The importance of version control cannot be overstated.

## 3. Prioritize Your Health

This one is likely the most important tidbit out of this list. Yes, even more important than knowing how to use `git`.

Working as an engineer can be remarkably sedentary. It's very easy to slip into a routine of sitting at a desk for 8+ hours a day followed by more sitting on the couch, thereby not moving much at all. When I find myself slipping into a routine like this, I feel noticeably worse. My body tightens up. My back starts hurting. General motivation quickly wanes.

The (probably obvious) solution is consistent exercise to combat the sedentary lifestyle that comes with being stuck in front of a computer a majority of the day.

Exercise daily no matter what in some way, shape, or form. For bonus points, add a stretching and mobility routine.

I've found that not only do I feel drastically better when I'm exercising regularly, but I also tend to be more motivated to excel in my work and personal projects. So not only will you be healthier, but you'll also trend towards being a better, productive engineer if that's your goal.

## 4. Don't Be Afraid to Say **No** (within reason)

This one is a little hard to do when you're fresh, possibly starting your first job, and don't know much.

I still think it's worth mentioning since saying "no" is an underutilized option that most people forget they have.

I wouldn't recommend flat out refusing to do something that your manager or team lead asks of you, but developing a "pushback" muscle as you gain more years of experience isn't a bad thing. In fact, I'd argue that it's a really good thing.

For example, I think being hit with an unrealistic deadline that would compromise quality is a good candidate for speaking up. Or maybe your team is using a specific technology for a task when a much better one exists. As a beneficial byproduct, conveying your (possibly) contradictory thoughts can lead to constructive, productive discussion within your team.

In a weird way, I think exercising your "pushback" muscle when it makes sense to do so can garner more respect from your colleagues. It shows that you're invested in your work and care about its quality and longevity.

Having the knowledge or the confidence to speak up when something doesn't makes sense won't happen overnight. Additionally, as a fresh engineer you won't even know when something even _deserves_ pushback. Be that as it may, I write this so that you keep the option of saying **no** (when it makes sense) in your back pocket for when you _do_ have enough experience and you _do_ know what you're talking about.

## 5. Keep Track of Your Accomplishments

Keeping a detailed record of your accomplishments helps you in many ways, from being able to advocate for yourself in performance reviews to keeping your resume is up to date.

I guarantee you will forget the many tasks and projects you've successfully completed over time. Maintaining a "brag document" that outlines accomplishments you're proud of is a good way to keep track of what you've done so you can reference it later. There's a great resource on brag documents [here](https://jvns.ca/blog/brag-documents/) that I highly recommend checking out. I wish I started doing this as soon as I entered the workforce.

**Pro tip**: Your brag document will help you have prepared answers and stories for the "Tell me about a time when..." or "Explain a past project..." questions that are common in interviews.

## 6. Start a Blog

Blogception :smile:

I think starting a blog is an excellent way to showcase your technical skills and knowledge while maintaining a record of your technical growth and experimentation over time. I'm hoping that being able to reflect on my journey as an engineer and documenting my experiences will prove itself to be incredibly rewarding, both personally and professionally. I wish I had started writing earlier in my career. So start writing!

Being able to look back at things like:

- **Technical Problems Encountered and Solved**: Documenting the challenges you face and their solutions serves as a valuable resource for yourself and others who might encounter similar issues
- **Life Events and Milestones**: Writing about what was happening in your life at different times can provide context to your technical journey and highlight how personal experiences influence your professional growth.
- **Technologies Learned**: Keeping track of the technologies you learn and experiment with helps can help with identifying areas of interest. Additionally, looking back at what you've learned can be a great motivator to keep pushing forward and learning new things.

Even if no one but you ever reads these posts, having concrete data (i.e., written pieces) to track progress over time as a constantly learning engineer will end up being invaluable.

I think starting a blog is not just about showcasing your technical skills to the world; it's about creating a personal archive of your journey as an engineer.

## 7. Clever Code `!=` Good Code

As a new programmer entering the workforce, there's likely going to be a temptation to flex your muscles and write clever, concise code to showcase your technical prowess.

This is the opposite of what you should be doing.

Clever code or code written for the sake of brevity is almost never synonymous with good code.
Good code is maintainable, readable, and abundantly easy to understand.
It prioritizes clarity over brevity, making it easier for others (and your future self) to understand and modify.

One of your goals when writing code should always be to (aside from solving the problem) communicate your intent in the clearest way possible to anyone who reads it.
Someone who looks at your code should be able to understand what it does and why without having to spend time attempting to decipher it or asking you for clarification.

You'll pat yourself on the back when some time has passed, and you need to revisit that code you wrote weeks or even months ago.

### The Pitfalls of Clever Code

Clever code can be difficult to understand, debug, and maintain.
Concise one-liners may look cool, but using obscure language features or advanced techniques that are not immediately clear to someone reading the code for the first time can lead to increased development time and more bugs.

Not to mention annoyed (possibly new) team members who have no idea what your code is doing.

Lets look at a couple examples.

### Example 1: List Comprehension vs. Loop

#### Clever

```python
result = [x**2 for x in range(10) if x % 2 == 0]
```

#### Good

```python
result = []
for num in range(10):
    num_is_even = num % 2 == 0
    if num_is_even:
        result.append(num**2)
```

In this example, the list comprehension is concise (one liner!), but it may not be immediately clear to someone who isn't familiar with [list comprehensions in Python](https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions).

You could argue that list comprehensions aren't _that_ difficult, but anyone looking at the version which uses an explicit loop should be able to pretty quickly understand what's going on.

### Example 2: Using Built-in Functions vs. Explicit Code

#### Clever

```python
result = list(map(lambda x: x**2, filter(lambda x: x % 2 == 0, range(10))))
```

#### Good Code

```python
result = []
for num in range(10):
    num_is_even = num % 2 == 0
    if num_is_even:
        result.append(num**2)
```

Here we're doing the same thing as the previous example, but using the `map` and `filter` functions with lambda expressions.

Another one liner!

Are you familiar with [map](https://docs.python.org/3/library/functions.html#map) and [filter](https://docs.python.org/3/library/functions.html#filter)? If not, this code may be difficult to understand at first glance. Throw in a couple of [lambda expressions](https://docs.python.org/3/tutorial/controlflow.html#lambda-expressions) and things can become really confusing.. which is why the explicit loop version is again preferable.

### Writing "Good" Code

When you're writing your code, try and keep some of these things in mind:

1. **Be Explicit**: Write code that very clearly expresses its intent to the reader. Try and avoid using possibly obscure language features that someone may not be familiar with. If this means writing a couple more lines of code, so be it. It's not the end of the world.
2. **Use Meaningful Names**: Choose variable and function names that describe their purpose and usage. (Duh!) Don't be the guy that uses single letter variable names or names that don't make sense.
3. **Add Comments**: Most of the time, your code should be self-documenting.. meaning you shouldn't need comments. You've made your code easy to understand remember? But if you're doing something non-obvious, add a comment explaining why you're doing it.
4. **Follow Established Conventions**: Adhere to coding standards and conventions for your particular language and project. If you're working on a team, this is especially important. Example: your team prepends python function names with an underscore like `_some_cool_function()` to denote that they're private. Stick to that.

Profit.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/xkcd-1513-code_quality.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
  <a href="https://xkcd.com/1513">https://xkcd.com/1513</a>
</div>
