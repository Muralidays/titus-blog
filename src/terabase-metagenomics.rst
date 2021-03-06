Terabase metagenomics - meeting and outlook
###########################################

:author: C\. Titus Brown
:tags: bioinformatics,metagenomics
:date: 2010-07-24
:slug: terabase-metagenomics
:category: science


I'm on my way back from the `Terabase Metagenomics
<http://icis.anl.gov/programs/summer-1>`__ meeting in Snowbird, UT,
and I'm buzzing with ideas about how to move forward in metagenomics
and bioinformatics research.  Metagenomics, the use of genomics
approaches to study microbial communities, has been opening up as
sequencing drops in price.  With sequencing becoming ever more
ridiculously deep and inexpensive -- we're looking at a power of 2-5
increase in depth every year for the next 5 years -- the questions
have increasingly become intertwined with (surprise!) computational
science problems and specifically bioinformatics.  As we move towards
multiple individual terabase (and collectively *petabase*) sequencing
data sets in the next two years, life is going to become more
complicated for metagenomicists and the bioinformaticians who aspire
to help them.  (That's me.)

The meeting was focused on the promise of terabase metagenomics for a
"whole earth" microbial ecology sampling projects, and we spent quite
a lot of time trying to figure out the size of unknown unknowns in
metagenomics.  There was a great mix of people at the meeting -- both
"pure" microbial ecologists who regarded computers with suspicion and
computer scientists who didn't understand how DNA became protein, as
well as the entire range between those two poles. We talked about
questions such as: "how deep *do* we need to sequence in order to get
a real picture of microbial diversity?" (a: very) and "how do we
reconcile genomic and transcriptomic data sets?" (a: unknown) and "how
can we scale up 1000-fold when our existing algorithms are all
N-squared?" (a: with difficulty.) The discussion was at a reasonably
high level of sophistication: pretty much everyone in the room had
"seen the elephant", and representatives of the major analysis
pipelines were also present.

We didn't come to any firm conclusions about the biology, but we did
sketch the outlines of a global sampling project to look at global
microbial diversity, together with the deeper sequencing of specific
locales to plumb the depths of a few communities.  Coming up with a
computational pipeline to deal with data and metadata on this scale
-- storage, analysis, integration, presentation, and querying -- is
truly challenging and should be fun.

For me, one recurring theme in the meeting was entanglement with
management and standardization issues in big projects.  *Everyone* was
bitching about these on their existing projects, and I'm trying to
avoid them. I have little or no interest in telling other people how
to do their job; *absolutely* no interest in being told how to do *my*
job; and a general lack of patience with standardization issues,
however important and critical they may be.  (In some ways, the
Benevolent Dictator For Life approach to decision making used by the
Python community seems optimal for medium-sized projects, although of
course it takes a special person to pull it off.  I acknowledge that
decisions need to be made, but have no real interest in doing anything
more myself than exploring the technical issues that could inform the
decisions.  Hmm, I wonder if the PEP process might be a good way to do
a formal standards process in metagenomics?)  I don't if there's any
way for me to avoid this stuff in the future, but it's the main reason
that I'm wary of joining big projects.

A few interesting references came up during the meeting.  For example,
I hadn't seen `the Heilmeier Catechism
<http://en.wikipedia.org/wiki/George_H._Heilmeier#Heilmeier.27s_Catechism>`__
before; I think it's a good idea for both scientific and open source
projects to look at this before they do too much work!  I was also
entertained by `Jonathan Eisen's
<http://phylogenomics.blogspot.com/2010/07/what-is-not-getting-any-love-at-this.html>`__
report on things that the workshop participants disliked: for example,
"Bureaucracy (and how it impedes science)."

All in all, I think this meeting was fantastic: very small, very
focused, and with plenty of time for discussion and socializing.  I'm
happy the organizers invited me, so thanks to them!

--titus


----

**Legacy Comments**


Posted by Deepak on 2010-07-31 at 13:25. 

::

   Ben Black gave a talk at OSCON recently on standards in another
   context.  The point he made and which applies really well here, is
   that in any area that is moving rapidly, if you standardize too early
   you might standardize to the wrong thing.      While we should avoid
   inventing new formats or using old ones incorrectly, with next gen, is
   it sufficient to let the community settle on a common framework (set
   of formats, standards)?  It's happened in other areas (small
   molecules, proteins). At the current rate of change, by the time you
   get a committee in place it will be a moot point.


Posted by Titus Brown on 2010-08-02 at 14:57. 

::

   I have no comment other than "great point" ;).  I think the metadata
   issues are pretty important, though, and should be something that
   microbial ecologists have already thought through thoroughly.    also
   see <a
   href="http://gensc.wordpress.com/">http://gensc.wordpress.com/</a>.

