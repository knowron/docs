# Product Update December 2023

!!! warning "This page is under construction"

    This page is under construction.


Welcome to our December update page! As always, this page is simply a summary of the features released from the [Roadmap](https://trello.com/b/UjCoUgke/knowron-roadmap). You can always check the roadmap page for the most up-to-date information on the product.

---

## Insights Dashboard makes it easier to close knowledge gaps (available immediately)

One of the main goals for this quarter was to make sure that editors and admins could understand how well their system was performing and were empowered to close the knowledge gaps in their organization.

The **Insights Dashboard** is our way to do that. 

<p align="center"><img src="https://i.imgur.com/ro4PDcx.png"></p>

### What is the current status of my system?
The main page of the dashboard answers this question by showing the percentage of questions answered, total searches and submitted user feedback.

### How is my system progressing over time?
The two graphs in this section show you the percentage of **questions answered**, i.e. the questions for which a user sees a **generated answer from our system**. A higher number is often indicative of a system capable of serving users the information they need - we recommend targeting a benchmark of around 75%. 

Additionally, you can monitor the number of **queries searched**, or the number of individual questions submitted by users over the past weeks. These will fluctuate with time, but the higher the better.

Additionally, you'll be able to see the change in these numbers over the last week.

### How can I improve my system?
This table shows you the **top unanswered questions** in your knowledge base. You can affect this table by uploading new sources which answer the questions or directly writing an **expert answer** about it (see below).

We use a clustering algorithm to show you an amalgamation of differently phrased questions under the same query so that e.g. "How much does the component weigh?" and "Tell me the component weight" are counted in one go.

### What are the frequently asked questions?
Finally, the most **frequently asked questions** are shown. These can be an important barometer in understanding whether users are finding what they need, regardless of whether they are receiving a generated answer from our system or not.

The **Search History** and **Feedback** screens have now been moved to be under the Insights Dashboard.

## Expert Answers makes closing knowledge gaps easier than ever (available immediately)

One of the main changes we have introduced is an all-new way to directly and simply answer users' questions.

<p align="center"><img src="https://i.imgur.com/m48FwjW.gif" width="100%"></p>

Whenever a user submits a feedback about the answer they have received or the search results in front of them, a new **feedback item** will be created. You can answer these feedback items (or unanswered questions, see above) with an **Expert Answer**. 

Expert answers are the best way to close gaps in your knowledge base. Think of them as similar to a dynamic FAQ list: an editor answer a user's query and any subsequent query that is similar will see the Expert Answer as one of the top sources. 

Expert answers behave much like articles: you can quickly write information and attach images or links to it. The expert answer will also show up on search like other sources, but it will be treated with priority for the query which it answered originally.

<p align="center"><img src="https://i.imgur.com/jKsjvL2.gif" width="100%"></p>

Expert answers can also contain sources, which refer the user to other articles or documents which might help them look up a specific value or data point. Please note that the public visibility of an expert answer might change based on the sources attached: expert answers with private sources are automatically private!

### Informing users

Whenever an editor answers a users' open feedback, Virtual Assist will automatically generate an email informing them that their query has been answered.

<p align="center"><img src=""></p>

## Chinese is now available for Virtual Assist (15.12.)

The Virtual Assist is now available in Chinese and in the People's Republic of China.

Users can upload Chinese documents, ask questions in Chinese and get answers in Chinese, even from documents that are not Chinese themselves.

This update includes a full localization of the user interface of both the Control Suite and the Application.

<p align="center"><img src="https://i.imgur.com/MxkHupO.png"></p>


## New tag system is now available for documents, articles and search (15 Dec)

As part of this update, we have released a reworked tag system that is available across content units (currently documents, articles and search). 

Tags can be used to easily narrow down search results or relevant documents in the documents and articles screens. They now conform to existing data structures within ASMPT (e.g. Inspection vs. Printing) and will be immediately recognizable to most users. 

<p align="center"><img src="https://i.imgur.com/xPuCYPj.gif" width="100%"></p>


We will slowly continue to add content units to this system (e.g. expert answers) as time goes on. Previously, only documents could be tagged - we have now expanded that possibility to articles as well.

<p align="center"><img src="https://i.imgur.com/R3ZQZPM.png"></p>

## Pictures can be explored more easily (available immediately)

We have now added a [Lightbox](https://en.wikipedia.org/wiki/Lightbox_(JavaScript)) component to the product, making it easier to zoom into small images appearing on e.g. articles.

<p align="center"><img src="https://i.imgur.com/W25B2OT.gif" width="100%"></p>

## Article drafts (available immediately)

Previously, articles could only be immediately published for everyone to see, making it harder to work on longer, more complex articles.

Editors can now simply save an article as a draft. This means that it will not appear on search and it will only be visible for other editors who can also edit them.

<p align="center"><img src="https://i.imgur.com/Dumfa1e.gif" width="100%"></p>

## New user feedback collection for Control Suite (15 Dec)

As part of our drive to make it easier for users to provide their feedback, we have reworked the feedback-collecting elements on Control Suite search. 

Users will now be able to select from among pre-defined categories for giving feedback on results which aren't helpful, instead of having to elaborate much. 

Users can now also submit feedback (positive and negative) to extracted answers.

## Multiple languages in articles (22 Dec)

Previously, articles were only available in the language in which they were initially written. This led to single-language knowledge areas cut off to the rest. 

Now, editors can create a version of all articles in any of the languages available for their organization in the same way that they can for tutorials. This update also includes the same auto-translation interaction as tutorials.