# Jared Video Pages
Jared gives talks at many conferences and meet-ups. These video pages serve as a resource that helps in all phases of these talks. In advance of the presentation, these can be easily shared so attendees have something to look forward to. During the presentation, he references related topics that he cannot go in depth on, but attendees can refer to these resources after the presentation. Finally, after the presentation, attendees can refer to the video page to get missing notes, related content, and be given an opportunity to share the presentation with others (including, but not limited to, leaders within their organization). This could lead to additional conversations that may become sales leads, new speaking engagements, coaching calls or just additional conversations on how Jared and UIE can help other companies and those in the UX community.

The links to these videos have been shared by Jared and conference organizers on Twitter, as well as by presentation attendees on LinkedIn. This page allows Jared to provide attendees a next step interaction with UIE, and a means to share the resources with individuals who could not attend.

While this repo is titled "jaredlive", this project is NOT the same as the Jared Live page that currently exists on uie.com. Some of the content is the same. The Jared Live page shows eight total presentations, where the individual page can focus on the singular topic (with updated copy, videos and links) that relates to what Jared wants to highlight to each individual or group he speaks to. The Jared Live page also does not have easily shareable links (bulky links with anchor tags in the URL), where the intent of these pages is to have an easy to remember link that can be shared easily.

[Link to user scenarios](https://docs.google.com/document/d/1lqC9rIqYmJcV5DrvvBW4lFe4mhI_HTWQyopgehbbjrw/) that drove the below list of **priorities**:
1. Easy to share URL
2. Video can be played
3. Easily accessible related resources (presentation slides, transcripts, articles and blogs referenced in the presentation)
4. CTA to sign up for the _UX Strategy with Jared Spool_ newsletter
5. Form to contact Jared
---  
### Create a New Page
1. Duplicate a video page that already exists using Atom on your local machine. The working directory is /Users/Shared/jaredlive
2. Update the following HTML sections:
  1. h1 title to the title of the video
  2. Update the video link
  3. Update the link to transcript. Need a new transcript? Refer to that section below
  4. Update the link to presentation slides. Need new slides? Refer to that section below
  5. Update the copy beneath the video
  6. Update the link, title, and by-line (if necessary) of each card in the related content section at the bottom. You may need to add or remove card divs accordingly. Link to the related content is in the section below
  7. Unless directed by Jared or someone else, that should be the only changes needed to the template
2. Log in to uie.com Wordpress account
3. Navigate to "Pages" on the dashboard on the left side of the screen
4. At the top of the page, click "Add New"
5. In the "Enter title here" field, populate the title of the presentation
6. Below that, edit the Permalink. It should be one or two words from the talk, maximum, to ensure ease of sharing.
7. Copy and paste the code from Atom into the WYSIWYG, then click on the preview button in the top right corner. Review for accuracy (ensure video plays, links go to the right resource, typos)
8. Once everything looks good, you can publish. Share with the team for additional sets of eyes to review

**Making Updates to Design**
1. In WordPress, there is a page called "Video page test" that you can use to preview working code. Click on that page to edit
2. Copy and paste the code from Atom into the WYSIWYG, then click on the preview button in the top right corner
3. Continue to use this page for any development needs, especially the Chrome developer tools to inspect and to view changes directly on this preview page
4. When desired changes have been made and reviewed on this page, you can go ahead and put those changes into the respective video page
5. Be sure to push the changes to GitHub

Any other content that needs to be updated can be done in Atom, then pasted into the page on WordPress.

---
### Assets and Other Resources

**Transcripts** are located in /home/uiewp/uiewp/wp-assets/transcripts and can be accessed through Transmit.

If a transcript does not exist, a new one will need to be generated on rev. Speak with Adam for authorization to generate this transcript. You simply need to add a link to the video, and rev will generate a transcript. From there, follow steps 1-7 from the "Putting the Transcript in Place" section from [notion](https://www.notion.so/centercentre/AYCL-New-Seminar-Release-f607f76923734f4ab055502b88036952). Next, you'll open a copy of the prior transcript and save it as a new file. Then you'll want to update the following:
1. Title in the head tag and in the h1 in the div with id="header"
2. Link for the h1 in the div with id="header"
3. The location and date of the presentation in the small tag in the div with id="header"
4. Replace the p tags with the new transcript content in the div with id="article"

Once that is complete, you can transfer the file to the wp-assets/transcripts directory on the server. Check the link to ensure it works, and check that the content is correct.

**Slides** are located /home/asset/slides and can be accessed through Transmit. The original slides are located in a Dropbox folder that is pinned in the #web_intern_projects channel. You will want to ensure you use the latest version number for the slides.

[Link to related content](https://docs.google.com/document/d/1-pBnNEFN2qIBA5fWYe37hhlG9I1K0KxVdu6vhnVlQqI/) that will populate the article cards beneath the video.



---
### Future considerations:
Below are unresolved issues to be addressed in future versions:  
1. Including a contact form. Current challenges are how to create a means to contact Jared without seeming like it will invite a sales call, and where to place it on the page.
2. Descriptions for each related article and why a user would want to click on the link for the resource. Current challenge is how to fit that in stylistically.
3. Adding open graph images to each individual page so that when it is shared, it shows either a picture of Jared giving a talk, or a slide from the talk instead of the UIE logo. Current issue is the header page is pulling a set of OG tags as part of the header from WordPress.
4. Adding open graph text with a short description of the talk, instead of the UIE line. Current issue is the header page is pulling a set of OG tags as part of the header from WordPress.
---
### Live links:  
1. Beyond The UX Tipping Point: https://www.uie.com/tipping/
2. Building a Winning UX Strategy Using the Kano Model: https://www.uie.com/kano/
3. Design is a Team Sport: https://www.uie.com/designteam/
4. Insecure & Unintuitive: How We Need to Fix the UX of Security: https://www.uie.com/uxsecurity/
5. Is Design Metrically Opposed?: https://www.uie.com/designmetrics/
6. It’s a Great Time To Be a UX Designer: https://www.uie.com/greattime/
7. The Evolution of a New UX Design Resolution: https://www.uie.com/resolution/
8. UX Strategy Means Business: https://www.uie.com/business/
