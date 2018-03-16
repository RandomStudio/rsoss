# RSOSS
> Open Sourcing the Random Way, without being random about it 😉

Some guidelines and best practices.

**IMPORTANT DISCLAIMER: THIS DOCUMENT IS A DRAFT (WORK IN PROGRESS) AND DOES NOT CURRENTLY SIGNIFY OFFICIAL COMPANY POLICY. IT IS AN EXPLORATION OF POLICIES AND BEST PRACTICES UNDER DEVELOPMENT.**


___
## The Why Part
We need to build our public profile in the Open Source software development universe, which is after all the same universe where all the good developers are - the ones who work for us or who might work for us in the future! So, yes, it's part of **employer branding**.

On a surface level, our involvement in the works of others (the list of repos we contribute to) is a very good **advertisement of the stuff we're interested in and the technologies in which we have expertise**.

But we need to be more active than that. By improving and contributing to the tools and frameworks that make our work possible, we demonstrate that we are good Open Source citizens (givers and not just takers). Call it **Open Source virtue-signalling**. But really it's about **credibility**:
> Being visible, being a thought leader, not only helps drive the field in areas of interest to us, it also gives us credibility when we want to bring in the very best people in the field. 

*(From https://www.techrepublic.com/article/what-microsoft-understands-about-open-source-that-your-company-does-not/:)*


Last but not least, there is the potential to **harness the power of the crowd**: outsiders may end up improving (and QA'ing) things that we originally built by ourselves for ourselves. There will always be more smart people working outside our company than in it.

### Best possible outcomes
* We get better at gathering evidence of our Open Source expertise
* We gain credibility so that we can give talks, write articles, host events
* We attract good talent to work for us, or partner with us
* We might even get our name behind a wildly successful Open Source project or two (viral marketing)


___
## The How Part
### Forking public repos (not our own)
This is the easy part. We make use of Open Source tools and frameworks all the time, and we (should) help maintain and improve these on company time in the course of our work. So why not give Random Studio some credit for this?

When forking a project to improve/contribute, members (with repo create privileges) should see the option to fork either to their private account or to the Organization:

![forking public repos](forking-public.png "forking publicly")

If this is a work-related project (it is being done on company time and/or is being used in the process of client projects), then it is a good candidate to be forked under the Org.



### Brand new repos
When we create something that is useful to us and potentially useful to others, this should be created under the Random Studio Org (or transferred there if necessary). 

### Implications for our workflow
Building software in a modular way is a pretty good idea anyway, but now we have another motivation: we need to have the option of picking certain modules we have built and Open Sourcing them.

Not everything we make will be suitable. Anything specific to our clients and their IP should be excluded. And sometimes we might be building a ["majestic monolith"](https://m.signalvnoise.com/the-majestic-monolith-29166d022228) and that makes it difficult to pull things apart, but we should keep a lookout for suitable candidates. **Anything we ourselves could plausibly re-use between clients and/or projects is a good candidate for releasing Open Source.**

Some obvious candidates:
* Command-line utilities with a generic application 
* NPM modules
* openFrameworks addons or Cinder blocks

Generic tools could be
* media asset conversion, compression or packaging
* support for new sensor hardware
* configuration or deployment scripting
* frameworks that make common setups easier to get started

> TODO: More on how to manage conflicts of interest, legal IP issues, etc.



### Who gets the credit?
It is important to remember that even when a repo is "owned" by the Org (it was started under the Random Studio Org or ownership was transferred), all commit activity is still attributed to the individual **users**.

This is a good thing:
* Users get credit for their work publicly (it shows up on their GitHub profile under their activity)
* However, the repos owned by the Org do not show up under each user's list of repositories, on their GitHub profiles
* We can track who is responsible for what
* We can also allow outsiders to contribute (in a controlled way) to anything we're working on


___
## Useful resources and references
* GitHub's own [Open Source Guide](https://opensource.guide/): includes tips on growing community and some info on the legal side of Open Source
* [Why the Best Companies and Developers Give Away Almost Everything They Do](https://blog.ycombinator.com/why-the-best-give-away/) goes into some of the non-altruistic reasons why Open Source is good for companies
* [What Microsoft understands about open source that your company does not](https://www.techrepublic.com/article/what-microsoft-understands-about-open-source-that-your-company-does-not/): "Microsoft understands that its future depends upon contributing to open source, not just using it. Here's why your company needs the same strategy. "
