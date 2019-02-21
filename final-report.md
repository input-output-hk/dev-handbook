  - [Developer handbook](#sec-1)
    - [Intention](#sec-1-1)
    - [Implementation](#sec-1-2)
      - [Deployment/hosting longer term](#sec-1-2-1)
    - [Assessment of impact](#sec-1-3)

# Developer handbook<a id="sec-1"></a>

## Intention<a id="sec-1-1"></a>

The intent behind the dev handbook was to both be the instruction manual for how development is done at IOHK/cardano and as an asset that demonstrates for the wider public that IOHK is indeed the leading research driven blockchain company. As such it was always intended that developers and other contributors should "own" it themselves and be able to make changes to the content with the minimum of friction. I believe this is essential in order that such an body of knowledge stays in sync with reality.

There was also some discussion about integrating this with the work that the opensource manager did. I also thing that's a great idea as it would then be something that tells the "whole story" in a very transparent and open way. I believe this would ultimately serve the IOHK and the cardano community in the best way.

## Implementation<a id="sec-1-2"></a>

With the intention in mind, the development handbook was implemented initially as a collection of markdown files and later on towards the middle of last month it was converted to a static site generated from the markdown by the hugo toolset <http://gohugo.io/>. This is a website where the content is kept in a git repo and the website is re-generated when the content changes. The source is here <https://github.com/input-output-hk/dev-handbook> and it's currently set up for continuous delivery, hosted on netlify: <https://www.netlify.com/features/> (although at an obfuscated url here <https://festive-hoover-f1dec6.netlify.com/>). We should talk about how to hand that over, but essentially I can just disable it from my free netlify account and anyone can point a different netlify account to the git repo and continue as normal.

It's branded as consistently as possible IOHK/cardano based on feedback from Jane and Robert that the intention would probably be to host it under the cardano.org domain name. This was mostly done by me on a best effort basis as the content and front end teams are rather overloaded at present preparing for the summit and with other BAU tasks.

### Deployment/hosting longer term<a id="sec-1-2-1"></a>

There is a desire from Robert Moore to move this to a different static site generator based on nodejs (Gatsby) that they have more familiarity with. Whether this is necessary I guess depends on who will "own" it. I would advocate for at a bare minimum that development teams own the content, and if practical they own the whole solution.

There's also the question of hosting the developer handbook in the longer term. I personally think that netlify is the ideal solution for this as it makes it completely trivial to make sure that the site is up to date and make it very easy to inspect the effect of pull requests on the main site.

There is some confusion about the process of hosting this at a subdomain of cardano.org. Apparently the Cardano Foundation owns that domain and either lack the capability to add subdomains or there's still some political problems with doing so. From a technical point of view though, once this is sorted netlify makes that completely trivial.

## Assessment of impact<a id="sec-1-3"></a>

The developer handbook was intended to be a shared repository of best practice and the processes that the teams were following. Unfortunately most of the teams were quite busy and I never felt that we had coalesced around a common approach to enough of a degree that we could have a definitive development process shared across everyone.

There was never really the engagement from the teams in wanting to use the handbook in the way it was intended. I always thought that for this to have the most impact, the teams would have to have the buy in and the culture to want to use the handbook as the "source of truth". I ultimately think this is still something IOHK should really aim for, as I think this is the best way to shoot for a healthy opensource ecosystem around cardano and the related project going forward. However in the environment of continued delivery pressure teams (rightly) have to prioritise the "doing" over the "improving".

As such I feel that the impact could have been much greater. I was consciously trying to avoid a situation where one person (me) writes all the content with no engagement from other stakeholders and then that be perceived as being forced upon the company. I think this was something that happened with the previous development process and as a result it was never really utilised consistently. My hope this time round was that developers would own the content and a start to take pride in recording how they wanted things to work. That never really happened, partly I think because of delivery pressure not really letting up, and partly I guess because I didn't make enough noise.
