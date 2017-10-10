# Triangular-mesh

I was tossing around the idea of making this a wedding present for two friends of mine (not the code itself, but the result.) Alas, it didn't happen, but now I'd like to go through with it. 

As long as I'm not finished and not sharing this code with anyone, I can outline my plan for it on this readme. That's something people do, right? 

1) Take a picture, and randomly select coordinates throughout, with the probability of being selected being somehow proportional to the amount that's "happening" at that point. 
- Might use gradient as measure of this? 
- I'm 110% confident that whatever I initially come up with will need tweaking. It needs to look good, and pure randomness doesn't often, I guess, oblige that pursuit? Hahaha
2) Triangulate! Make a mesh out of it. I'm only familiar with Delaunay triangulization, and I like how it looks, so we'll probably stick with it and devote more time to messing with the parameters in the other parts.
3) Draw it nice and pretty. Pick colors for each triangle by... uh, some means? Perhaps by converting the colors to a color space with different parameters, picking one of them, and then just averaging over the triangle. Idk. We'll see! 

That's the main body of it! There'll surely be other hiccups, like how do I make things of sufficient resolution to print well, etc... but those 3 should constitute the actual code. Let's get working.


# Day 1

Let's get step 1 finished today. The algorithm doesn't have to be perfect, but I'd like it to be, like, not entirely garbage. It's plenty easy to tweak later, but I'd like something manageable today.
