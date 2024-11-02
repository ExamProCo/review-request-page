# Business Goal 

We want to build a Pay-for-review website for ai and cloud products and services.

# Website Structure
The Website will contain two pages:
1. Home Page eg. /
2. Request Review Page eg. /request-review

## Home Page

The goal of this page is to introduce people to who the reviewer is, and show a list of videos reviews.

### Page's components:

- Meet Your Reviewer Components
    - Component should appear as card.
    - Video Thumbnail
        - When video thumbnail is clicked a popup will appear with the video.
        - Video is linked from Youtube.
    - Name
    - Description
    - Name and descript should be to the right of the video
- Call to Action Component
    - A button button that has a call to action to encourage AI and cloud tech companies to request video review
- Video Review List
    - This component is a list of video reviews that can be toggled between a grid of video thumbnails mode and data table.
    - Fields:
        - Name
        - 1 line desciprtion
        - Associated tags
        - Video Thumbnail (only for grid mode)
        - Watch button
            - link to youtube video in new tab
- Tag filter
    - allow for multiple filters to be selected

## RequestReview Page

The goal of this page is offering Pay-for-review services

### Page's components:
- Packages
    - Package Fields:
        - Name
        - Description
        - Price
    - Package 1 (Review): 1-Hour Single-Shot Blind Review
        - Andrew will sit down for 1 hour, start recording and use your produce, and provide first-impressions feedback.
    - Package 2 (Review): Plan and Record Blind Review
        - Andrew will spend 1 hour learning and using your product and then he will record in a single take all he is learned.
    - Package 3 (Review): Service Team and Video Review
        - Andrew will talk with your service or product team, to best understand your product
        - Andrew will spend 1 hour learning your product
        - Andrew will produce video
    - Pakage 4 (Preview): 
        Similar to package 3 but Andrew will work to demostrate your product in the way you want it to be shown.
- Request Review Now Component
    - call to action with button button that links to a external form
- Expections Component
    - Two cards side by side
    - What to expect
    - What we expect from you
- FAQs Component
    - accordion of questions which can be expanded.



# Technical Guidlines
- tag filtering should all be done client side 

# Tech Stack

The website should be built with the following tech stack:
- React
- Typescript
- Tailwind.css
- Radix and Shadcn
- Vite.js

# Target Audience

AI or Cloud tech companies that want a content creator to create a video review for their service or product for a price

## 

# Reference Websites

These reference either contain pay for review websites that we can draw inspiration or inquiry about pay for review services:
- https://www.meeplemountain.com/request-a-game-review/
- https://boardgamegeek.com/thread/1482415/how-do-you-get-a-game-reviewed-and-how-much-does-
- https://www.shutupandsitdown.com/videos-page/