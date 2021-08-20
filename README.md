# WMT21SrcDA

Code and issue tracker for WMT21 source-based DA campaigns

## Updates

- 2021-08-20: Accounts are *live now*, please contact `{tomkocmi,chrife,rogrundk}@microsoft.com` about your accounts
- 2021-08-20: [WMT21.appraise.cf](http://wmt21.appraise.cf) goes live

## TL;DR

- WMT21 will feature source-based direct assessment (DA) with document-level annotation
- We will focus on non-English target languages, and annotators need to be native speakers of the target language
- Teams receive a number of anonymous accounts to perform annotations for language pairs of their choice
- The number of accounts received is based on the number of team's primary submissions
- Please use the [Github issue tracker](https://github.com/AppraiseDev/WMT21SrcDA/issues) to report any problems

## Timeline

- 2021-08-06: research teams request for annotation languages
- 2021-08-20: accounts shared with research teams
- 2021-08-20: annotation starts
- 2021-09-16: annotation ends

## Campaign overview

### How will the annotation work?

Annotations will be collected in Appraise, implementing document-level,
source-based direct assessment. For every language pair, we will generate
anonymised accounts which are pre-assigned to exactly two annotation tasks.

### How much annotation work is needed?

One account contain two tasks, each involving 100 sentence-level judgements.
The average annotation time for one task is ca. 45 minutes, so we assume that
each account is 90 minutes of annotation work.

Each research team is expected to contribute **ten hours of annotation work
per primary system** submission. We assign you with only nine hours of
annotations per primary system to keep buffer in case the annotations
would take longer. This translates to **12 completed tasks** or
**6 completed accounts** in total, on Appraise, per primary submission.

### Who can be an annotator?

The source-based evaluation requires native speakers of the non-English target
language who are also proficient in English and can assess translation quality
from English into their native language.

### How are accounts distributed?

Account distribution is based on first-come, first-served basis, i.e., once
an account is marked as ``assigned'' to a team you cannot claim it anymore.
Please note that **you can provide annotations for any language pair**, not
only language pairs you have submitted primary systems to.

Each research team should designate a team leader who is then responsible to
reserve the required amount of accounts for their team.

### Where can I claim my account?

Please contact `{tomkocmi,chrife,rogrundk}@microsoft.com` to request your accounts.

### How can I sign into Appraise?

For each account, we provide a **single sign-on (SSO) URL**. This allows you
to sign into Appraise with a single click on the URL, making access very easy.

### What information do you store about me?

There is no personal information attached to the annotation accounts. We
capture your assessments and related metadata, such as annotation start and
end time as well as duration per single assessment.

### How does source-based DA work?

This year the campaign features a document-level annotation view with the
entire document presented on a single screen in two columns. The left column
has source sentences and the right column has corresponding candidate
translations (see the screen), that you will be scoring using a slider.

![Screenshot of WMT21](/images/screen_wmt20.png)

The annotation process consists of scoring individual sentences one-by-one and
then assigning a single score for the entire document. Assigning the
document-level score (the slider at the very bottom of the page) becomes
available after all previous sentences are scored.

Submitting a score will automatically move the annotation to the next sentence
and open a new slider. A dot on the right side of the translated sentence
roughly indicates the assigned score: a reddish dot means a lower score (worse
translation), and a greenish dot means a higher score (better translation). The
tick means that the score has been successfully collected by the server and the
progress is saved (i.e. the web page can be reloaded without loosing the
progress made on the current document). If you decide to change the assigned
score, it is possible to do so at any point of the annotation process by
clicking on the sentence text to expand a slider, updating the score, and
clicking 'Update'. When the document-level score is submitted, the annotation
process continues with the next document until all documents assigned to your
account are annotated.

### How can I report problems?

Please use the [Github issue tracker](https://github.com/AppraiseDev/WMT21SrcDA/issues)
to report any problems. You can also contact us via ``{tomkocmi | chrife | rogrundk} [at] microsoft [dot] com``.

## Frequently asked questions

### Are there any reference based annotations or into English translations?

No, this campaign is source based DA for non-english target language only.

### Do I need to annotate languages of my primary system submissions?

No, that is not necessary. We balance annotations accross teams that speak various
languages. You can annotate any language pair in which you are proficient.

### Why does some documents in annotation are same/similar?

Various systems have translated the same document, therefore similar translations are
annotated. Furthermore, it may happen that the same document occurs in multiple tasks.

### We completed a task in each account but are asked to do more?

That is likely because you have finished only one task for some accounts when
we require completing both tasks assigned to each account. If the account is
fully completed, then you will not see any link on the Appraise dashboard.
