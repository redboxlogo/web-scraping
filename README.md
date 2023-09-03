# Web Scraping
<strong>Overview: </strong> Scrape questions, answers, comments, and metadata from StackOverflow, specifically questions about R, starting at the [URL](https://stackoverflow.com/questions/tagged/r).

<ul>
  <li>start at this first page of the search results on stackoverflow</li>
  <li>get the links to the questions on this page</li>
  <li>get the next page of results and the links to the questions on that</li>
  <li>process the questions on the first 3 and last page of results of the search results, fetching 50 results/questions per page</li>
</ul>

### Task
The goal is to explore the source of the HTML pages for the search results to find HTML structures identifying the elements of interest described below:
<ul>
  <li>the number of views of the question</li>
  <li>the number of votes</li>
  <li>the text of the question</li>
  <li>the tags for the question</li>
  <li>when the question was posted</li>
  <li>the user/display name of the person posting the question, their reputation, and how many gold, silver, and bronze badges they have</li>
  <li>who edited the question and when</li>
  <li>for each answer/comment, find: the text, the person who posted, when they posted, and their reputation and badge information</li>
</ul>
