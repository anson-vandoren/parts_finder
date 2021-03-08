# Parts Finder

This is a "dogfooding" project to help manage my ever-growing inventory of electronics and
mechatronics parts for various hobby projects. It's not really intended (yet) for anyone else
to use, and might never get to that stage. I am happy to consider issues and (especially) PRs
from others, but this is a side project and in its current state will likely not get much
attention devoted to issues/bugs/features that I don't face in my personal use.

# Initial plan

I plan to slowly build out features according to how I need to begin using this. The first
workflow I'd like to enable is:

- Create a new storage location and optionally print out a barcode that can
uniquely refer to that location.
- With a storage location selected, add a part, either by scanning its supplier barcode,
or by manually typing in some relevant information. Either way a quantity should be added.
- Provide a very basic UI to show what parts are in each location.

I have plenty of ideas that I want to add later, but step 1 is just to enable the above.

# Alternatives

If you're interested in software like this but don't want to wait for me to get around
to developing full functionality, or don't want to host it yourself, or whatever, some
alternatives you may possibly be interested in are (I have no affiliation to any of these,
they're just what I searched for and didn't quite meet my requirements prior to starting
this project):

- [PartsBox](https://partsbox.com): basically exactly what I am looking for, except
that for my usage, I can't justify the price of the lowest tier (45€/month)
- [BOMIST](https://bomist.com/): has all the features that I want, and has a free tier,
but the features that are important to me are locked behind either the $9/mo or the $34/mo
tiers, and it doesn't include all the features I have in mind for this project (when it's finished).
- [PartKeepr](https://www.partkeepr.org/): open source and free, and can be self-hosted. This
project doesn't appear to support barcodes, which are pretty key to the workflow I'd like
to have available. It also doesn't seem to be in active development any longer, and my
testing of the demo site makes it seem pretty slow, even for a modest number of parts.