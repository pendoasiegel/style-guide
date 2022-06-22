# Product Style Guide

Many of the specific writing rules in the [Pendo Brand Voice and Style Guide](https://docs.google.com/presentation/d/1NA5n3Ac5lWPzANcUE7vVbaYnEcP1fDpkNK6RB7fpFlQ/edit#slide=id.g10f0d2d600c_0_1) and Pendo's guidance for Brand Copywriting are good practice for help documentation and UX writing.

The following additional guidance is based on established content design principles, cognitive psychology, UX writing guidelines, and industry standards.

Other good sources of guidance, if this style guide is ever lacking, are the [Microsoft Style Guide](https://docs.microsoft.com/en-us/style-guide/scannable-content/lists) and [Google developer documentation style guide](https://developers.google.com/style).

## Scannable content

Scannable content is more accessible, usable, and approachable, allowing readers to find the information they need without overwhelming them.

* Keep content as short as possible to the reduce the need for users to scroll.
* Use headings to break up content. Adopt a flat hierarchy (2-3 tiers).
* Write short blocks of text (2-4 sentences).
* Use bullet points.
* Consider the location of content. Place important content “above the fold” in a webpage.
* Use bold and italics selectively. Don’t use quotation marks for emphasis.

## Lean writing principles

To modify a quote from Antoine de Saint-Exupery, good writing is achieved, not when there is nothing left to add, but when there is nothing left to remove. Write content with lean writing principles in mind. This should make content easier to find, scan, read, and use.

### Write shorter sentences

*  Aim for paragraphs that are 75 words or fewer.
*  Sentences should be, on average, 15 words, and 28 words as a maximum.
*  Use shorter and less complicated words where possible.
*  Keep headings 12 words or fewer.

### Write purposeful content

Sentences tend to be shorter when you write purposeful content. Avoid redundancy to maintain the effectiveness of your content:

*  Get straight to the point based on what users want and need.
*  Don’t provide unnecessary information. For example, don’t give a detailed history of the product – focus on instructions for performing a specific task.
*  Remove titles that restate the text in the UI or a paragraph in the documentation.
*  Remove unnecessary words and content, for example, ”You’ll be asked to enter your password, which you created in the previous step.”
* Use as few words as possible to portray meaning.

### Get to the point, quicker

Avoid redundancy to maintain the effectiveness of your content.

|Guidance| Example|
|---|---|
|Avoid buried verbs (nominalization): using a noun and a verb when a verb alone would portray the meaning. |“Follow the guidelines for testing your software”, rather than “Follow the guidelines for *performing a test* of your software”. Turning the word “test” into an action removed the need for the word “performing”.
|Use the active voice.|“You can send emails from your phone”, rather than “Emails *can be sent from* your phone”.|
|Avoid prepositional phrases.|“Select the plus sign ~~in order~~ to add a new user” or “~~In this case,~~ delete the file.”|
|Write imperative sentences.| “If you need further help, ~~you can~~ contact the Support team”.|
|Avoid grammatical expletives (words that add emphasis by delaying the subject), such as “it is” or “there are”..|“There are six items in the list”, could be reworded to “The list has six items”.|
|Remove empty or unnecessary determiners and modifiers.|“The set up is ~~basically~~ the same”; “The process is ~~actually quite~~ straightforward”; “Selecting this option is ~~really~~ only needed if you’re using a Windows machine.”|
|Prune every excess or redundant word.|“*Repeat* the steps ~~again~~“ or “*Revert* ~~back~~ to your previous settings.”|
|Replace an intensifier or qualifier, along with the adjective it refers to, with a stronger word.|“Very important” could be replaced with “crucial”.|
|Avoid manner adverbs (usually formed from adjectives by adding “-ly”) and use precise language, instead.|“The change takes effect *quickly*“, could instead be, “The change takes effect *within 5 minutes*“.|
|Replace wordy phrases with single words where possible.|“With the exception of” could be replaced with “Unlike”.|

## Word choice

Use clear, consistent, and human language. For clarity, we need to avoid ambiguous terms, replace colloquialisms with accurate language, and commit to plain (American) English.


### Use unambiguous terms

Use terms that are clear and understood by global audiences.

*    Avoid language that requires special or local cultural knowledge, e.g., remove phrases like “Ready to jump in?”
*    Avoid “would”, “should”, and “may”, which can be ambiguous in describing whether something will, must, or can be done.
*    Don’t use double-negatives, for example, use “like” instead of “not unlike”.

### Use inclusive and unbiased language

You’re talking to humans, so be sensitive to the human meaning of words.

*    Avoid offensive or violent terms, like “hit”, “force”, “reject”, “kill”, “hang”, “abort”, and “terminate”.
*    Avoid terms that reflect historical racial bias, such as using color to communicate something is “good” or “bad” (like, "whitelist" and "blacklist"), and references that carry forward the master/slave paradigm (like, "master table").
*    Use gender-neutral alternatives to “he”, “she”, “him”, and “her”.

### Use plain English

Spend time researching what words the intended readers use rather than defaulting to corporate language.

*    Avoid marketing language and technical jargon.
*    Use intended words instead of Latin abbreviations, such as “specifically” instead of “i.e.” and “for example” instead of “e.g.”
*    Use industry-standard terminology when it will improve user understanding.
*    Use technical language only when it’s needed, and try to also explain it generally.

### User terminology consistently

Without consistency, documentation can come across as unreliable or lacking credibility.

*  Don’t switch between terms in the product documentation or in the product itself.
*  After introducing an acronym, don’t switch back and forth between full words and the acronym.
*  Don’t switch between language conventions, such as American and British spellings.
*  In instructions, refer to UI elements exactly as they appear in the product.

### Be considerate, not over-polite

Software and product documentation should, above all else, be considerate more so than polite, which means putting the needs of of the reader or user first.

For example, an error message that says, *“Sorry! There was a generic error”* is polite, but not especially useful because it focuses on its own function, and not what the reader or user needs to do.

Avoid overusing “please”, “thank you”, and “sorry”, especially for normal operations of the program. Adding these terms might seem polite, but they can come across as disingenuous and slow people down by adding wordiness to your sentences.

|Term|Guidance|When to use (example)|When not remove (example)|
|---|---|---|---|
|Please|Use “please” only in situations where you’re asking someone to do something inconvenient or where the software is at fault.|“Please try again later.”|“To view the file, ~~please~~ select **View**.”|
|Thank you|Use “thank you” when you’re asking someone to provide input that’s inconvenient. Convey gratitude from the people behind the documentation or product rather than the system itself.|“Thank you for giving us your feedback!”|“Check that you’ve entered your email address correctly before submitting. ~~Thank you.~~”|
|Sorry|Use “sorry” only in situations that cause problems for the user, such as a system crash or data loss. Don’t apologise for how the product or service is designed to function. |“Sorry. We were unable to connect you to the service. Please try again later.”|“~~Sorry.~~ It looks like your card is expired.”|

## Grammar and conventions

### Capitalization

There has been a recent shift towards sentence-case because it’s easier to read. Sentence-case involves capitalizing only the first word and proper nouns in a heading. In general, use sentence-case for:

*  Headlines, headers, and subheads.
*  Secondary web navigation and menu items.
*  Buttons and calls to action (CTA).
*  Titles and input fields.
*  Titles of charts, tables, and diagrams.
*  List items.

Use title case only for:

*  Main or global navigation on web pages (top-level/primary navigation).
*  Distinguishing products from general technology with similar names.
*  Titles of books, podcasts, webinars, and videos.
*  Trademarked product names.

### Headings

Sentence-case is easier to read and is especially useful in titles because it helps to disambiguate generic terms from proper nouns, for example, the difference between “feedback” submitted by end-users and “Feedback” the product.

Avoid having two headings in a row without text in between. An introduction/overview is almost always at the beginning, and so there's no need for an introductory heading to help readers locate that information.

For the information in the headings themselves:

*  Make titles task-based. Focus on what the reader does: use imperative sentences, action verbs, and the active voice whenever possible. For example, “Add customers to Feedback” instead of, “Adding customers to Feedback”.
*  Treat headings like micro-content – phrases that can be scanned to give readers a clear idea of what they’ll get if they click on it. You can do this by ensuring headings work out of context. For example, “Set up languages in Pendo Feedback” instead of “Languages Setup”.
*  Describe the purpose or goal of a feature. Aim for specific titles that provide concrete information and a clear advantage for the user. For example, “Set expectations with a Product Feedback Policy” instead of “Product Feedback Policy”.
*  Make article titles high-level enough to scale with product changes, and cover all the content within the article, including multiple product lines, for example "Roadmaps with Pendo Feedback" covers both current and Beta versions of Roadmaps, and will cover any additional features of Roadmaps.

### Links

Links in the body of the text are inserted in a wiki-like style, where select words in a normal sentence are hyperlinked to articles. This system involves reading the paragraph/sentence to infer what the link provides based on its context.

We should be introducing a link and then hyperlinking the actual name of the article so that we make people overtly aware of what to expect. Other guidelines for links include:

* Don’t link preceding articles (a, an, the).
* Don’t link punctuation.
* Don’t include words and phrases like “Click here” in a link; make links meaningful outwith the context of the full sentences.

### Symbols and punctuation

Don’t use symbols or characters to substitute words, either in headings or body text.

Keep punctuation simple. Complex constructions, for example, by using semicolons or multiple dashes, can impair readability and can make translation difficult.

Use the serial (Oxford) comma to provide clarity and to maintain consistency across content. Use a comma for a series of three or more elements.

Don’t use end punctuation (. : ! ?) in section titles, subheadings, UI titles, and items in a list that are three or fewer words.

Use common contractions, such as “don’t” instead of “do not”.

Don’t use a comma to combine two independent clauses (comma splicing). Instead, add a conjunction (like “and”) or separate the clauses into two sentences. For example, “I sent 100 emails, I plan to send 100 more” could instead be either:
*  “I sent 100 emails, and I plan to send 100 more.”
*  “I sent 100 emails. I plan to send 100 more.”

### Tense

It’s best practice for help docs to speak in present tense, which is easier to read and more directly relevant to the reader, who is reading the documentation to perform tasks or gather information in their present. We should only use the future tense when you need to emphasize that something will definitely occur later (from the users’ perspective).

For example, instead of, “After you save changes, a confirmation window will appear”, we should be writing, “After you save changes, a confirmation window appears”.

## Writing instructional content

Use the imperative mood for instructions: start with an action verb and second person singular, with “you” as its implied subject. Imperative sentences are typically in the active voice.

### Using emphasis

For visual clarity and scannability, we aim to follow specific industry standards for emphasis.

Rather than using bold to emphasise words, phrases, or sentences, use layout, callouts, headings, and short paragraphs to draw attention to important content or messages.

**Bold** is reserved for emphasizing UI and navigational elements in instructional content. For example: Navigate to **Settings > Product Settings > Custom Responses**.


Both italics and quotation marks should be avoided in help documentation, especially instructions. Use italics sparingly for gentle emphasis. Only use quotation marks to quote blocks of text, which is typically not present in help documentation.

Following these rules helps readers hone in on important actions, maintains consistency, and minimizes visual noise.

### Using numbers and bullet points

For clarity, use numbers only to denote the order in which steps are carried out. This helps readers recognise step-by-step instructions and helps you maintain consistency across articles.

Use bullet points for a general list, even if you preface the list with a statement like the following: “There are four different ways your visitors can access Feedback”.

 This means that users will always be able to recognize when a list is a set of procedural steps.

### Writing step-by-step instructions

In step-by-step instructions, refer to a full sequence of UI steps, in order, rather than as part of convoluted sentences. For example, rather than:

> “Scroll all the way down to the bottom of the Integrations page. Here you will find the Pendo Feedback panel under the User Feedback section. Click on the Pendo Feedback panel. Now you've opened the Pendo Feedback panel, you need to set the Pendo Feedback Auth Token for your Staging and Production environments. To do this, paste your Pendo Feedback Auth Token into the "Auth Token" field. Add a title and description for the integration too.”

You could instead write:

> “At the bottom of the **Integrations** page, open **User Feedback** and select the Pendo Feedback panel. To set the token for your staging and production environments, paste your Pendo Feedback Auth Token into the **Auth Token** field and add a title and description for the integration.”

This structure removes unnecessary words, and presents each of the UI elements in bold and in the order in which the user will find and interact with them.

Another way to make the sequence clear, as well as removing more unnecessary words, is with clickthrough instructions. Use chevrons (**>**) with spaces around them to separate items in a clickthrough and bold the chevrons along with the UI elements in the clickthrough. So, instead of the above example, you could write:

> “To set the Auth Token, navigate to **Settings > Integrations > User Feedback > Pendo Feedback** and paste your Pendo Feedback Auth Token into the **Auth Token** field.”

It’s also good practice to use a numbered list for step-by-step procedural tasks. This helps avoid big blocks of text whilst also providing a clear way to show a process. Using the same example, you could instead choose to write:

> 1. Navigate to **Settings > Integrations**.
>
> 2. Scroll down to the bottom of the **Integrations** page.
>
> 3. Open the **User Feedback** section.
>
> 4. Select the **Pendo Feedback** panel.
>
> 5. Paste your Pendo Feedback Auth Token into the **Auth Token** field.
>
> 6. Add a meaningful title and description in the appropriate fields.

Not all steps will require an image. You could introduce the task and an image (both before and after the list), thereby maintaining the visual integrity of the sequence for the reader as well as the context needed for the images.

If not already clear, introduce what a set of instructions will achieve before describing them so that readers can skip over irrelevant information. For example, “To create a shareable link, navigate to the top menu and select **File > Share > Copy Link**”.

### Word choice for instructions

It’s good practice in documentation to avoid talking about mouse actions. Instead, refer to user actions with words like “hover over”, “choose”, “select”, and “enter”. Only use the word “click” to refer to specific mouse actions.

In general, use “select”, to instruct the reader to select an item, like text, objects, or cells, and use “enter” to instruct the reader to type something into a text field.

### Sentence structure for instructions

|Guidance|Example|
|---|---|
|Put conditional clauses before instructions.|“For more information, see the disclosure document” (rather than “See the disclosure document for more information”).|
|To direct the user to do something, mention the circumstances before you provide the instruction.|“If you want a PDF of this page, select the **Download** button in the top-right of the screen” (rather than “Select the **Download** button in the top-right of the screen for a PDF of this page”).|
|When writing a series of steps, mention the location, followed by the action.|“From the drop-down menu, select the type of alert you want to send” (rather than “Select the type of alert you want to send from the dropdown menu”).|

### Callouts

The logic behind callouts is to capture user attention. However, research (e.g., Benway and Lane, 1998) shows that users have become habituated to these attempts so much so that they often skim over and fail to interact with images, quick links, internal navigational banners, and any other element designed to stand out on a page to attract attention.

This means that, contrary to the common sense intent behind bolding whole sentences and calling things out in highlighted boxes, the most visually salient items on a page are ignored. Additionally, since the human brain perceives and interprets information in chunks (see Gestalt Psychology), anything placed near these callouts are also likely to be overlooked by association.

This has been studied: in one experiment, users only noticed red banners with black text that was relevant to the task they were performing 58% of the time, compared to 94% when only control items were shown (Benway, 1998). Moreover, follow-up experiments showed that “noticing” banners had no impact on the speed with which users were able to complete their tasks.

The original intent of these experiments was to investigate whether changes in how banners were presented (text size and use of graphical elements) could mitigate “banner blindness”, but the lack of impact of any of these variables on users indicates that engineer and designer logic comes second to actual user research.

Instead of trying to force user attention with callouts, it’s recommended that we make content easy to scan and find by only presenting the most essential and relevant information in a digestible layout, structuring information so that it’s in line with reader mental models, and engaging in lean writing principles.

### Images

In general, too many images, and images that are too large, make content harder to read, while white space makes content more legible. Additionally, images can lead to frustration if the user can’t find the element or functions you’re trying to depict in the image. To avoid frustration and increase usability:

Like callouts, images create visual clutter that people become accustomed to skipping over instead of making use of them. This is especially true for annotated screenshots, which add visual clutter, making instructions hard to find and read. Additionally, images that include instructions within them are less accessible than written instructions for those that rely on screen-readers.

General guidelines for images include:

* Balance the number and size of images against the amount of text that surrounds it.
* Introduce an image before presenting it. Make visual content complementary to written text after you’ve written it, not a substitute for it.
* For accessibility, avoid annotations, and include captions and alt-text for screen-readers. Don't annotate images when they don’t need to be, for example, if the correct item in the screenshot is selected (and therefore highlighted).
* Use context-relevant and functional visual content. Don't zoom too far in to the element.
* Use SnagIt to create a 1pt border around images, blur sensitive information, and create annotations (using Pendo pink).
