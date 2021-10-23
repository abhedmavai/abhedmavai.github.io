---
title: "Static vs Unit vs Integration Tests"
layout: post
---

I love that metaphor in how it applies to testing because it's basically saying that choosing the right testing strategy is the same kind of choice you'd make when choosing a brush for painting a wall. Would you use a fine-point brush for the entire wall? Of course not.That would take too long and the end result would probably not look very even.

Would you use a roller to paint everything, including around the mounted furnishings your great-great-grandmother brought over the ocean two hundred years ago? No way. There are different brushes for different use cases and the same thing applies to tests.

## Testing Trophy

In the Testing Trophy, there are 4 types of tests. It shows this text above, but for the sake of those using assistive technologies (and in case the image fails to load for you), I'll write out what it says here from top to bottom:

- End to End: A helper robot that behaves like a user to click around the app and verify that it functions correctly. Sometimes called "functional testing" or e2e.
- Integration: Verify that several units work together in harmony.
- Unit: Verify that individual, isolated parts work as expected.
- Static: Catch typos and type errors as you write the code.

> The size of these forms of testing on the trophy is relative to the amount of focus you should give them when testing your applications (in general). I want to take a deep dive on these different forms of testing, what it means practically, and what we can do to optimize for the greatest bang for our testing buck.
