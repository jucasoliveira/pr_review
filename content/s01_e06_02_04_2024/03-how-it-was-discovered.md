This backdoor were discovered on Friday, March 29th , when Andres Freun posted some odd symptons around liblzma
![liblzma](https://cdn-images-1.medium.com/max/800/1*-2m1Vu4AGfhfVivMqi25Kw.png)
And to be fair: the backdoor is NOT in the upstream source of build-to-host, nor is build-to-host used by xz in git , meaning is not on the repository itself. However, it is present in the tarballs released upstream, except for the "source code" links.

But how he discovered that ? 
![backdoor](https://cdn-images-1.medium.com/max/800/1*j1v_N2GYptSn5AsqOrztuw.png)
Well, he was doing some benchmark and discovered 500ms lag on the login ….

![login](https://cdn-images-1.medium.com/max/800/0*WdxspSQeUhqfHt6f)

When you see gamers freaking out about FPS drops. Imagine discovering a backdoor exploit because a 500ms lag sparked your suspicion?

Now , I'm not experience on this side of software development , not gonna lie, I'll like the sources like THIS I've consulted in other to make this article, as well a really good explainer from another content creator.

That was a good catch , something I do not think I would detect on my own, so props to Andres who caught it. And probably if wasnt for him this backdoor would be present in all major OS's, prompting a massive security hole.
