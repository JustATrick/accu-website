# ACCU Website

Notes on functionality for the accu-website

## What are we aiming at?

We'd like a system to support:

*   Ease of Use
*   Ease of Publishing
*   Ease of Submission

The next milestone is to have use cases and wireframes to present to the next
committee meeting, which will be sometime in September.

* **Q. How much prioritization should we have done by then?** Moscow?
* **Q. How much feasibility work should we have done by then?**

## User Types / "Stakeholders"

*   Member
*   Non-Member
*   Editor
    *    Committee Member
    *    Journal Editor
    *    Conference Committee Chair (Members?)
*   Membership Secretary
*   Mailing List Moderator
*   Advertisers
*   Advertising Officer

## Functions

### Member Account Info

We took a look at some of the pages surrounding account info for Members.
Though it mostly works, it's hard for users to find, and clunky when they do.

**We need to decide whether it's feasible to set up a new site that delegates
this stuff to the existing one.** I think doing so would go against our aim of
making the site easy to use, but might allow us to make some visible progress.
I suspect that doing a new membership system would take a lot of effort.

#### User Stories

* As a Member I want to update my mailing info so that the journals reach me

* As a Member I want to renew my subscription so I can keep benefiting

* As a Member I want to control how you contact me, so I don't feel I'm being
  spammed

* As a Member I want to see a receipt of my last payment, so I can commit tax
  fraud

* As a Non-Member I want to find out about the benefits and costs of
  Membership, so I can decide whether to join

* As a Non-Member I want to join the ACCU so I can take advantage of the
  benefits

* As a Membership Secretary I want to do loads of reporting things...(do we
  need to go into this)?

### Articles

We saw a little of how difficult it is to add an article, and how the result is
plain and boring. We imagined that initially all committee members and members
of the journal teams should be able to easily post news articles. Ideally the
journal articles would be available to the system in the same way as news
articles (though CVu will be behind the paywall), rather than being tucked away
in an archive.

(Sorry about the 'curation' nonsense - I'm trying to prevent premature focus on a single homepage. We will have articles linked to from the homepage, but eventually we could have a separate articles page, or a page for each journal, or a set of topic pages...)

#### User Stories

* As a Non-Member I want to see a selection of articles to get a feel for what
  ACCU is about.

* As a Non-Member I want to see a recently curated selection of articles so I
  can see that ACCU is alive.

* As a Non-Member I want to be able to find articles I might be interested in.

* As a ? I want Non-Members to see that paywalled articles exist, and a little
  about them, so they can see a benefit of joining.

* As an Editor I want to import all the journal article archives so that I
  have a rich selection from which I can choose material to promote.

* As an Editor I want to automatically create articles from each issue of the
  journals so that I always have fresh material to promote.

* As an Editor I want to add new articles so I can publish news.

* As an Editor I want to be able to create rich articles with images and
  consistent formatting, so that I can be proud of my work.

* As an Editor I want to be able to easily curate a selection of articles so I
  can keep it fresh.

### Mailing Lists

The current mailing lists sit outside of the CMS-backed website, and are
managed by Mailman. This means that we found lists that we know exist were not
shown on the website. Also, it's hard to ensure that only authorised members
can join.

#### User Stories

* As a Non-Member I want to join public ACCU mailing lists so I can join the
  discussion

* As a Member I want to join private ACCU mailing lists so I can join the
  discussion

* As a Committee Member I want all mailing lists advertised on the website, so
  that we attract people to ACCU

* As a Non-Member I want to see the archives of public mailing lists, so I can
  find out what sort of discussion goes on

* As a Member I want to search the archives of mailing lists, so I can find
  that cool thing I only half remember

### Book Reviews

The book review homepage is a boring looking search box. It hides that we have
~1900 book reviews. We'd like to an attractive, frequently changing, display of
new/topical reviews at the entry point. Then easy ways to search and browse the
collection, by title, author, subject, journal...

We should allow members (non-members?) to post book reviews direct to the site
(whether they got the book from us or not). They'll need to be reviewed by an
editor before they go live. We wished for a workflow system for reviewing
submissions, where editors can claim an entry to review and either
accept/reject/return to queue. And an alert system for items that have been in
the queue too long.

#### User Stories

(Maybe - do we think these are useful?)

### Conference

This bit of the site is one of the most successful. Other than a wish that it
looked more modern, we imagined improvements where we could view the sessions
in different ways: either via the schedule, or browse/search by session title,
speaker. We could make more of the videos and slides that we have after a
conference - we should certainly link to them, and if we could embed then it
would add some colour to the site.

### ACCU Admin

We noted the constitution page. We should have details of the committee with
photos and contact details. We should make minutes and agenda available here.

### Events

We have a calendar, but it's not really used. We should have one. We'd like to
see conferences and local meetings here, and other stuff of interest. Maybe
anyone can contribute, but entries are reviewed before publishing? We should
have a way to highlight upcoming events (probably on the homepage). We imagined
that we'd be showing title, description, url, location, date & time and
organiser for each event.

Articles will be able to link to events, should events be able to link back to
articles? e.g. experience reports...

### Mentored Developer Projects

## Non Functions

### Backup/Restore

### Reliability

### Payment Processing

### Development
