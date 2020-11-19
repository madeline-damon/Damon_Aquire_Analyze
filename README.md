# Damon_Aquire_Analyze
This is a repository for my Acquire and Analyze project

It is focused on looking at the language used in twenty different conservation nonprofit's mission, vision, and values statments as well as their tweets. 

I looked at the most common words used in each as well as different values embedded. The most common words helped me learn about some of the topics the nonprofits focus on in their missions and tweets to see how similar they were. Looking at different values in their missions and tweets let me identify the values the nonprofits portray to their audiences and any differences between their stated missions and their communication to the public via tweets.

## Feedback

Great work, this is **complete**. Looking forward to seeing where this research takes you. 

Some other thoughts: 

* TNC has some html-y words creeping in. I'd remove those unless they're legit.
* I'd probably go with either the counts or the charts (and I prefer charts), but not both.
* Really nice interpretation of the common words. 
* I'd think you'd be able to build `MVV_files` with a call to `os.listdir()` if you stored 
  the files in their own folder.
* It'd be super interesting to generate a large reference set of organizations that *aren't* 
  in the conservation space. You could use that to see if the use of, say, "we" is disproportionately
  high or low for this set.
* These values percentages give you a 10-dimensional vector for each org. I'd recommend calculating 
  the cosine distance we talked about the last week of class to measure the distance. It'd be 
  cool to visualize the orgs by running these vectors through a principal components analysis (PCA).
* Interesting to see TNC, which probably has the biggest budget, having alignment between their 
  social media values and their mission values. 
* Cool analysis on the values and words underneath the values (self-direction stuff, etc.)
* Throw the executive summary at the top, kind of like an abstract. 

