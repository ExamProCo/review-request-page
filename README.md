# review-request-page
Let AI and cloud vendors know what they can pay Andrew to review their products

## Lovable's GTP Engineer Prompting Tips
- You have to fine the copy yourself, focus on structure 

## Lovable's GPT Engineer Feedback
- It is not obvious that the projects you work on, are ALL public. (Make it clear, I am working in public, and everyone can see my project)
- I wish I could one press and have screenshots of the outputed website for documentation history
- I want to instead update golden technical doc and dump it in instead of tweaking the page through multi-convo because I want to capture all documentation for my technical doc. I want my prompting to be derminstic (replicable via steps)
- I want to review the code before I sync to my repo (otherwise I can't provide it feedback until it synced)
- I don't know if it it publishes the changes to the repo after each change.
- If it did, it would be nice if it was via a PR so I can review
- I don't know my usage when I'm using the app. I wish this was clear.
- Easy way to export chat history to audit the effectiveness with humans.
- How would I evaluate other than human review that the website/web-app I wanted met my technical and business use case.
- I wish I could have my technical doc updated.

## Prompt Engingeer History

### Spec 1

#### Results
- How close: 90% (before required changes)
    - see required changes below
- How close 97% (after required changes)
    - pagination doesn't show up (maybe only if there is pagination)
    - copy is still not improve for packages

#### HomePage Changes Required:
- Need to include pagination in video list for a limit of 50
- Request Review button should not be in the Meet Your Review card, it suppose to be its own call to action
- Watch button missing from video list
- Video list is not supposed to use a popup for videos thats only for meet your reviewer

#### RequestReview Changes Required:
- Plans should not have a button for each. We are suppose to have a Request Review Now Component because all plan buttons would go to the same form
- The bullets for the plans are fine but the summarization copy is wrong

## Follow Up Review

- Figure out Evaluations or test suite for outputted results
- How to structure technical doc into prompting chunks to get more accurate results.
    - Prompt Chunking
        (When your prompt is too large, that you need to break it down into step by step actions)