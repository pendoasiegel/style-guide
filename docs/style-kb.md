This is the basic styling and structure of a help center article.  Historically the Pendo Help Center hasn't had any consistent universal content structure. This is the first step to fix that. The main priority is always to provide the best education content to our users and strict adherence to a template shouldn't be a blocker to that. But consistent structure and depth of information provides a predictable, quality experience that builds trust and confidence in our users.

## Styling ##
### Text Formatting ###
`[h2]` - Section headers

`[h3]` - Subsection headers

`[h4]` - FAQ questions

`[p]` - Content body/everything else


### Lists ###
Bulleted lists for Requirements and simple lists describing stuff.
Create numbered lists manually. Never use structured numbered lists. Zendesk is bad at controlling formatting for numbered lists.
Try not to use complete sentences in bulleted lists. Items in a bulleted list shouldn’t end with any punctuation and punctuation within each list item should be minimal.

### Screenshots ###
All screenshots get a **1px solid color #C2D1D9 border** otherwise they blend into the background.

**Hero image**
For context and visual interest in Overview, Understand the Data, and maybe starting a workflow section
* Big, 500-550px wide, full width is ok for full screen screenshots
* Centered
* Interesting, lots of fake data, GIFs are cool too

**For instructions**
* Smaller, 300-350px, this width plays nicely with the Resource Center and nothing we’re showing in instructions should be that big
* Left justified to be inline with instructions
* Minimal, show the thing the user needs to interact with for that step. The entire set of instructions should provide all the necessary context.

**NEVER EVER EVER EVER SHOW CUSTOMER DATA**
* Don’t use pendo-internal for screenshots.
* If you literally can’t get a screenshot anywhere else (like dev) and you can’t wait for a feature to push to prod to get a screenshot in a demo environment, talk to Adam Siegel
  * Demo Experience
  * Acme Co (Spencer’s sub)
  * Dev/Lookaside
  * Inspect element and change details in dev tools as needed

## Spacing ##
* Add an extra paragraph space/empty row at the end of a section before the next section header
* Add an extra paragraph space/empty row after all screenshots
* Do not add an extra paragraph space/empty row after a bulleted list, even if it’s the last thing before starting a new section, bulleted list styling does this automatically

## Colored boxes ##
Boxes are created by editing the code in the Zendesk article and adding the CSS class to the HTML element manually. Adding the class will shade the background of the entire element with a thick border on the left side. You can add a new `<div` element to wrap multiple `[p]` or `[img]` elements if needed.

### Yellow is important boxes ###
`[class="notice"]`

They're always placed at the very beginning of the article for absolutely critical need to know information. Things that will break the feature, mess up data, legal disclaimers, that kind of stuff.

### Red is warning boxes ###
`[class="warning"]`

They're similar to yellow but for one or two lines of emergency information that we can include in line with instructions.

A way to distinguish the two is that yellow could be a collection of red boxes or yellow could be instead of red boxes so we don't have a bunch of red boxes interrupting the presentation of instructions or a narrative in the article. Breaking up the flow of text for a big colorful box is just bad UI. Yellow box fixes that. But if something already has a dedicated section in the article, like "Requirements" it doesn't need to be duplicated in the yellow box. Some information just needs to go at the beginning of an article, like a legal disclaimer, but throwing it in a red warning box is just way too harsh.

### Green is note boxes ###
`[class="note"]`

These are used for relevant callouts about how something works, how data is presented, or how features may interact with each other that need to be highlighted in the context of instructions but aren't really part of the narrative. Use them sparingly and try not to use them in the middle of a section. Again, bad UX to break up the flow of text with big colorful boxes. Historically, we use these way too much. Your first instinct should be to structure the body text better so that information can be included in the article instead of carved out into a notes box.
For example, in the Resource Center Metrics article, there's a section that talks about Top Stats. The body of the paragraph talks about the different data, what they are, what they mean. Then a note points out how we get the number for "eligible visitors" and how funky situations with segmentation can give certain values.

### Blue is tips boxes ###
`[class="tip"]`

This is like breaking the 4th wall and staring directly at the user to give them advice that we really wouldn't otherwise include in the KB. Like if you were sitting down with someone teaching them how to use something and they were just a little lost because there was some broader concept or informal advice they were missing. It's not as detailed as best practices. We're trying to stick to just academic content in the KB, explaining what the buttons due, and mostly how to use a feature with just enough why to have context. Best practices are mostly why with just enough how. Tips are an opportunity to add a little more why than we otherwise would. They usually come from feedback from CS or SEs. That little bit of extra knowledge for the folks that don't know what they don't know. We almost never use these, but when we do they make a huge impact.
* For example, in the Localization article there's a tip that steps back from explaining set up for localization and talks about how companies establish formal teams or departments for localization and they use third-party tools to manage translation at scale. We even link to a couple third-party tools that we don't have a formal business relationship with. Without it, some poor Pendo admin is trying to figure out how they manually edit all of these translation files in the raw code for every guide without realizing that there's an entire industry full of professionals that do only this.

## Basic Article Template ##

>[h2]Overview<br>
>[p]What it is, what it does, basic value prop<br>
>[p][/p] - empty line at the end of each section for spacing<br>
>
>[h2]Requirements (in a bulleted list)<br>
>* User permissions<br>
>* Minimum Agent or SDK version<br>
>* Subscription-tier requirements<br>
>* Settings or configuration requirements<br>
>
>[h2]Understanding the Data or more detailed context<br>
>[p]As needed for analytics tools and advanced concepts. This is the place to really get in the weeds and explain the calculations used by analytics tools and how to interpret them or specialized skills that most users may not be familiar with.<br>
>[p][/p] - empty line at the end of each section for spacing<br>
>
>[h3]These may need a subsection to organize content better.<br>
>[p][/p] - empty line at the end of each section for spacing<br>
>
>[h2]Workflow Sections<br>
>[p]**1.** One section per workflow, creating/adding the thing, using the thing, edit the thing, delete the thing.<br>
>[p]**2.** Any grouped features in an action bar with repeating patterns throughout the UI, just group into a single section that describes the action bar. Making them distinct sections with identifiable names helps with searchability in Zendesk and adds it to the table of contents for navigation in the article.<br>
>[p][/p] - empty line at the end of each section for spacing<br>
>
>[h2]Frequently Asked Questions<br>
>[h4]Does every article need an FAQ?<br>
>[p]Sometimes there are just weird edge cases and customer issues that need to be added to the article but don't belong in context anywhere in the body of the article.<br>
>[p][/p] - empty line after each answer for spacing<br>

## Detailed Article Template ##
>[h2]Overview[/h2]<br>
>[p]The overview section consists of three parts: a definition of the feature, a description of everything the feature can do, and the value proposition explaining why the feature is important or what a user persona can do with it. The overview section quickly tells the users what the article is about and the type of information contained in the article. This helps a user figure out if they want to read the article at all or jump to a particular section.[/p]<br>
>[p][/p]<br>
>[img]hero image[/img]<br>
>[p][/p]<br>
>
>[h2]Requirements[/h2]<br>
>Requirements are documented in a bulleted list presenting requirements in the same basic order<br>
>  * User permissions
>  * Minimum Agent or SDK version
>  * Subscription-tier requirements
>  * Settings or configuration requirements<
>  [p][/p]<br>
>
>[h2]Understanding the Data or detailed context[/h2]<br>
>[p]Some features have complicated calculations or advanced concepts that we don’t expect basic users to know or that we expect power users or SMEs to question. These subjects need additional detailed explanations. Putting this information in the overview sections makes the overview too long and cumbersome. Putting this information in the how-to instructions breaks up the instructions and makes them hard to follow. Putting this information in another article forces the user to go to another article and they lose broader context of learning about the feature in a natural flow. The PES and Control Group Experiments articles are good examples of these extra sections.[/p]<br>
>[p][/p]<br>
>[h3]Sub-section in a Section[/h3]<br>
>[p]Sometimes you need a subsection to break up parts of a subject when you don’t want to do a complete context switch. Most overview articles only need sub-sections in this bonus section. I try to avoid them in the first Overview section unless the subject is really complex and needs to be presented at a couple different levels. I avoid them in Instructions sections unless the instructions are super simple, like repeating duplicate, share, delete buttons in a header menu that are common throughout the Pendo UI. Each button with a 2-click workflow doesn’t need it’s own section. Keep it simple and combine them in one section and give instructions for each button a short subsection.[/p]<br>
>[p][/p]<br>
>
>[h2]Add a KB Article[/h2]<br>
>[p]Instructions get a dedicated section with easy-to-follow step-by-step instructions. Giving them a unique h2-level header makes them easy to find in the table of contents and a direct link if we need it. I like to start the instructions with a few sentences of context setting up the beginning of the workflow like this.[/p]<br>
>[p][/p]<br>
>[p]**1. Instructions are a numbered list.** Don’t use the formatted numbered list. The formatting is too limiting and hard to use in Zendesk if we want to add details in a step.[/p]<br>
>[p][/p]<br>
>**2. The number and action for each step is in bold.** It helps skim the instructions faster.[/p]<br>
>[p][/p]<br>
>[p]**3. Screenshots in instructions should be small and show the relevant action or menu.** They should also be left justified. This helps them stand out from the centered context screenshots in other sections.[/p]<br>
>  * Use a bulleted list to add details in a step, like context for a screenshot<br>
>  * Save - Add a description for elements in a menu like this<br>
>  * Open for comments - Uncheck to disable comments for the article, default is checked<br>
>
>[h2]Edit a KB Article[/h2]<br>
>[p]I’m not going to write another set of fake instructions. This is just here to show that you can use as many sets of instructions as you need to cover the various workflows for a feature.[/p]<br>
>[p][/p]<br>
>
>[h2]Frequently Asked Questions[/h2]<br>
>[h4]What goes in the FAQ section?[/h4]<br>
>[p]Weird edge cases, secondary workflows, customer-feedback that doesn’t naturally fit anywhere else in the article.[/p]<br>
>[p][/p]<br>
>[h4]Do I have to include an FAQ section?[/h4]<br>
>[p]No. We can add one later if FAQ topics come up. We shouldn’t need it if the article explains everything well. But don’t force extra details into instructions or sections where they don’t fit just to avoid an FAQ.[/p]<br>
