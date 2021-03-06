# Malcolm Gladwell

Malcolm Gladwell is an author and public speaker.  Although he is not a
technologist, the topics he writes about are widely applicable.  He is
informative and entertaining to listen to.  A collection of his speaches
have been listed below along with some notes about how they might apply
in professional specializations such as Operations and Site Reliability
Engineering.

## [Why Do Planes Crash?](https://www.youtube.com/watch?v=a4TXS7ck8bQ)

> Gladwell talks about one of the chapters from his book 
> [Outliers](https://www.gladwellbooks.com/titles/malcolm-gladwell/outliers/9780316040341/)
> to illustrate how failures in cockpit communication can lead to catasrophic 
> outcomes in commercial aviation.  In his talk he discusses 
> [Avianca Flight 52](https://en.wikipedia.org/wiki/Avianca_Flight_52) and
> [Air Florida Flight 90](https://en.wikipedia.org/wiki/Air_Florida_Flight_90)
> to demonstrate how subtle human errors rather than engineering failures
> ultimately led to the plan crashes.

This story is relatable in a number of ways:

Similar to the analysis of plan crases, the software industry 
has it's own hierarchical structure that can interfere with communication
and lead to catastrophic failure.  Age, race, gender, and job title can
all be factors in how well communication functions throughout the product
development lifecycle.  In an industry where communication must flow between
product managers, developers, testers, documentation, and sales there are
often barriers to communication which leave certain job functions with
less input or authority of how decisions are made.  The software industry
has tried to improve the situation by inventing the role of DevSecOps to
introduce many of these roles earlier on in the develpment process, but
it tries to address a human problem with a technical solution.  In the end,
developers try to assume too much responsibility and expertise rather than
extending communication and working more closely with other roles who have
the appropriate depth and expertise in that area. 

## [The Challenge of Hiring in the Modern World](https://www.youtube.com/watch?v=gLQC3EzDGr4)

> In his talk at The New Yorker Conference on May 8th, 2008 Malcolm
> Gladwell talks about the challenges of hiring and interviewing in
> the modern business environment.  He talks about how the draft
> process in professional sports frequently has no correlation to
> how sucessful an athlete will actually be in their professional
> career.

Why is this important:

When we interview potential candidates, we often use technical
interview questions or programming problems to determine how qualified
a candidate is for the job.  However, the ability of a candidate to
answer these questions is often no more indicative of their future
success than measuring how high a basketball player can jump during
the scouting and drafting process.


## [The Kenna Problem](https://youtube.com/watch?v=PwWq1K-s0Ms)

> In this talk given in 2003, Malcolm Gladwell discusses topics 
> from his book [Blink](https://www.gladwellbooks.com/titles/malcolm-gladwell/blink/9780316005043/). 
> By relating a story about [Kenna Zemedkun](https://en.wikipedia.org/wiki/Kenna),
> a musician who was loved by experts but failed to break through in
> radio market.  Other examples given in the talk are the Pepsi Challenge,
> Aeron chairs, and various forms of market research are wrong.

The important message I took away from this talk was that
subject matter experts can often conciously make informed and
correct judgements about their areas of expertise when prompted.
Non-experts, on the other hand, lack the vocabulary to articulate
the reasons for their preferences, which often causes their decisions
to be heavily influenced toward ideas that they are able to articulate
and explain using the vocabulary they do have.

## [The Right Attitude](https://www.youtube.com/watch?v=zIfdIJR309c)

> At the TIBCO NOW 2014 conference, Malcolm talks about how attitude
> affects people's ability to drive or adopt transformative changes.
> He talks about the story of [Malcom McLean](https://en.wikipedia.org/wiki/Malcom_McLean),
> an American businessman who transformed the transportation business
> through the use of intermodal shipping containers.

The story of how shipping containers became widely adopted has a lot
of similarities to the use of Kubernetes and containers in cloud
computing.  The adoption of these ideas as well as the underlying
efficiency drivers have brought about a fundamental shift in the
way companies run their operations.

## [Overconfidence and the Economic Crisis](https://www.youtube.com/watch?v=BN4yTXGhU0Q)

> In this talk at the New Yorker Summit on May 5th, 2009, Malcolm
> uses examples of military battles to illustrate how miscalibration
> contributed to the financial crisis of 2008.  For a similar talk,
> see his talk at [High Point University in 2012](https://www.youtube.com/watch?v=7rMDr4P9BOw).

The risk of miscalibration is an ever present danger in software
development.  As developers rely on metrics and data to improve
their confidence in ever larger and more complex applications, they
risk falling into the belief that they can anticipate any failure.
As they perform security scans and automated testing, they can become
complacent in the belief that they can prevent security holes.
However, the risk of a catastrophic failure or security breach
is ever present and any disaster recovery plans should account
for all reasonable possibilities.

## [Income Inequality](https://www.youtube.com/watch?v=iKvFlSedpNI)

> At The New Yorker Festival in 2014, Gladwell talks about how
> [Marvin Miller](https://en.wikipedia.org/wiki/Marvin_Miller),
> head of the Major League Baseball Players Association from 1966
> to 1982, was one of the leading figures to bring about the
> extraordinary income inequality in 1975.

This talk is particularly interesting when considered in the context
of salary negotiations and the trade-offs we make when negotiating
our salary.  Not all factors are monetary, and as freedom and
flexibility become more important, salary offers and negotiations
reflect a wider range of variables to consider.

## [The Dark Side of How We Think Without Thinking: Amadou Diallo](https://www.youtube.com/watch?v=1MQav8p2fJA)

> In this talk and his book [Blink](https://www.gladwellbooks.com/titles/malcolm-gladwell/blink/9780316005043/),
> Malcom uses the shooting of Amadou Diallo an example of how
> stressful situations and time pressure radically shape the way
> our minds process information.

Beyond the tradgedy of Amadou's death and what it says about
racism and police training in this country, there are other
aspects that can be applied to everyday office settings.  Situations
where time is compressed and unplanned tasks are undertaken,
the opportunity for snap judgements abound.  This is one of the
reasons why Change Requests require both an implementation plan
and a backout plan to be provided in detail.  Not only is it
important for the approvers to review this information, but also
for the implementer to reference it during a change to ensure
that a planned course of action has been prepared ahead of time.
If something goes wrong during the maintenance, the pressure of
trying to restore service without a detailed plan often leads
to mistakes which can make the situation even worse or unrecoverable.

## [Talking to Strangers](https://www.youtube.com/watch?v=M-l8d9lJTiw)

> In this talk given at the Dominican University of California
> on September 22, 2019 he talks about a story from his book,
> [Talking to Strangers](https://www.gladwellbooks.com/titles/malcolm-gladwell/talking-to-strangers/9780316478526/).
> He uses examples such as CIA spies, financial fraud, and other
> criminal acts to examine why people are so easily convinced to
> believe what they're told by others.


