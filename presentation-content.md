# Presentation Content
### Estimated time: 2h

When you give a talk, ask yourself, “What are the key points that my audience should take away from the talk?” Then, elide everything that does not support those points. If you try to say too much (a tempting mistake), then your main points won't strike home and you will have wasted everyone's time. In particular, do not try to include all the details from a technical paper that describes your work; different levels of detail and a different presentation style are appropriate for each. Never paste PDF of a table from a paper to slides. Reformat the table to be more readable and to remove information that is not essential. The talk audience does not have as much time to comprehend the details as a paper reader does.

Do not try to fit too much material in a talk. About one slide per minute is a good pace (if lots of your slides are animations that take only moments to present, you may have more slides). Remember what your key points are, and focus on those. The key point should be written on the slide, for example as its title or as a callout. Don't present more information than your audience can grasp; for example, often intuitions and an explanation of the approach are more valuable than the gory details of a proof.

Just as there should be no extra slides, there should be no missing slides. As a rule, you shouldn't speak for more than a minute or so without having new information appear. If you have an important point to make, then have a slide to support it. (Very few people can mesmerize an audience on a technical topic, and leave the audience with a deep understanding of the key points, without any visual props. Unfortunately, you are probably not one of them.) As a particularly egregious example, do not discuss a user interface without presenting a picture of it — perhaps multiple ones. As another example, you should not dwell on the title slide for very long, but should present a graphic relevant to the problem you are solving, to make the motivation for your work concrete.

## The slides
### Slide titles
Use descriptive slide titles. Do not use the same title on multiple slides (except perhaps when the slides constitute an animation or build). Choose a descriptive title that helps the audience to appreciate what the specific contribution of this slide is. If you can't figure that out, then you do not yet understand your own material.

### Introduction
Start your talk with motivation and examples — and have lots of motivation and examples throughout. For the very beginning of your talk, you need to convince the audience that this talk is worth paying attention to: it is solving an important and comprehensible problem. **Your first slide after the title slide should be motivation**, such as an example of the problem you are solving.

### Outline slides
**Never start your talk with an outline slide.** (That's boring, and it's too early for the audience to understand the talk structure yet.) Outline slides can be useful, especially in a talk that runs longer than 30 minutes, because they help the audience to regain its bearings and to keep in mind your argument structure. Present an outline slide (with the current section indicated via color, font, and/or an arrow) at the beginning of each major section of the talk, except for the introductory, motivational section.

### Conclusion
The last slide should be a contributions or conclusions slide, reminding the audience of the take-home message of the talk. **Do not end the talk with future work, or with a slide that says “questions” or “thank you” or “the end” or merely gives your email address**. And, leave your contributions slide up after you finish the talk (while you are answering questions). One way to think about this rule is: What do you want to be the last thing that the audience sees (or that it sees while you field questions)?

### Builds/animations
When a subsequent slide adds material to a previous one (or in some other way just slightly changes the previous slide), **all common elements must remain in exactly the same position, pixel-for-pixel**.

In short ***don't use animations as much as possible!***

### Keep slides uncluttered
Don't put too much text (or other material) on a slide. When a new slide goes up, the audience will turn its attention to comprehending that slide. If the audience has to read a lot of text, they will tune you out, probably missing something important. This is one reason the diagrams must be simple and clear, and the text must be telegraphic. As a rule of thumb, 3 lines of text for a bullet point is always **too much**, and 2 full lines is usually **too much**. Shorten the text, or break it into pieces (say, subbullet points) so that the audience can skim it without having to ignore you for too long.

### Do not read your slides word-for-word
Reading your slides verbatim is very boring and will cause the audience to tune out. You are also guaranteed to go too fast for some audience members and too slow for others, compared to their natural reading speed, thus irritating many people. If you find yourself reading your slides, then there is probably too much text on your slides. The slides should be an outline, not a transcript. That is, your slides should give just the main points, and you can supply more detail verbally. It's fine to use the slides as a crutch to help you remember all the main points and the order in which you want to present them. However, if you need prompting to remember the extra details, then you do not have sufficient command of your material and you need to practice more before giving your talk.

Just as you should not read text verbatim, you should not read diagrams verbatim. When discussing the architecture of a system, don't just read the names of the components or give low-level details about the interfaces between them. Rather, explain whatever is important, interesting, or novel about your decomposition; or discuss how the parts work together to achieve some goal that clients of the system care about; or use other techniques to give high-level understanding of the system rather than merely presenting a mass of low-level details.

### Text
Keep fonts large and easy to read from the back of the room. If something isn't important enough for your audience to be able to read, then it probably does not belong on your slides. **The font size for Persian text should always be more than 18 and for English text more than 16.**

Use a sans-serif font for your slides. (Serifed fonts are best for reading on paper, but sans-serif fonts are easier to read on a screen.)

### Figures
Make effective use of figures. Avoid a presentation that is just text. Such a presentation misses important opportunities to convey information. It is also is wearying to the audience.

**Never include generic images**, such as clip art, that don't relate directly to your talk. For example, if you have a slide about security, don't use the image of a padlock. As another example, when describing the problem your work solves, don't use an image of a person sitting at a computer looking frustrated. Just as good pictures and text are better than text alone, ***text alone is better than text plus bad pictures.***

When you include a diagram on a slide, ensure that its background is the same color as that of the slide. For example, if your slides have a black background, then do not paste in a diagram with a white background, which is visually distracting, hard to read, and unattractive. You should invert the diagram so it matches the slide (which may require redrawing the diagram), or invert the slide background (e.g., use a white slide background) to match the diagrams. A light-colored background with dark text is usually the best choice (preferably white background with black text; see the next paragraph about eye candy).

**Do not use eye candy such as transition effects**, design elements that appear on every slide, or multi-color backgrounds. At best, you will distract the audience from the technical material that you are presenting. At worst, you will alienate the audience by giving them the impression that you are more interested in graphical glitz than in content. Your slides can be attractive and compelling without being fancy. Make sure that each element on the slides contributes to your message; if it does not, then remove it.

### Emphasis
Slides that are monocolor black on a white background can be boring. This tires the audience, and it may prevent them from appreciating the big picture. Use color, callouts (e.g., arrows or speech bubbles), or other mechanisms to draw attention to the most important parts of your slides or graphs. For example, suppose you have a list of 3-5 bullet points, each one line of text long. You might want to emphasize the 1-3 most important words in each bullet point.

## The presentation
Make eye contact with the audience. This draws them in. It also helps you determine when they are confused or have lost interest, and whether your pacing is too fast or too slow.

Stand and face the audience.

- Don't give a talk while seated. Standing gives you more energy, the talk is more dynamic, and it is easier to maintain eye contact.
- Do not face the screen, which puts your back to the audience. This is offputting, prevents you from getting feedback from the audience's body language, and can cause difficulty in hearing/understanding you. Do not look down at your computer, either, which shares many of the same problems.
- Don't stand in front of the screen. This prevents the audience from viewing your slides.
- Being animated is good, but do not pace. Pacing is very distracting, and it gives the impression that you are unprofessional or nervous.

For computer science, the typical dress code is **“business casual”**. (For men, this is a dress shirt with slacks or jeans). The most important thing is that you are comfortable with your clothing; if you are not, your discomfort will lead to a worse presentation.

## Answering questions
Answering questions from the audience is very hard! Even after you become very proficient at giving a talk, it will probably take you quite a bit longer to become good at answering questions. So, don't feel bad if that part does not go perfectly, but do work on improving it.

Just as you practice your talk, practice answering questions — both the ones that you can predict, and also unpredictable ones. Give practice talks to people who are willing to ask such questions.

When an audience member asks a question, it is a good idea to repeat the question, asking the questioner whether you have understood it, before answering the question. This has three benefits.

- You ensure that you have understood the question. When thinking under pressure, it can be far too easy to jump to conclusions, and it is bad to answer a question different than the one that was asked. A related benefit is that you get to frame the question in your own words or from your own viewpoint.
- You give yourself a few moments to think about your answer.
- If the audience member does not have a microphone, the rest of the audience may not have been able to hear the question clearly.

***Be willing to answer a question with “no” or “I don't know”. You will get into more trouble if you blather on or you make up an answer on the fly.***

## Templates
you can use [google slides templates](https://slidesgo.com/)
