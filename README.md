
## Writing workshop 

### Repo description

This repository includes a template for a USRESP submission, based on the description on the webpage [USRESP - Report Template](https://www.causeweb.org/usproc/report-template-USRESP). Note that this is **not an official template**. You should double-check that it conforms to the guidelines before submitting.

The template is meant to demonstrate:

1.  **child documents**\
    Use of *child documents* in Quarto to organize your work when writing. This means writing each section in a separate document (*child*, e.g. `01-introduction.qmd`) and incorporate all documents in a *main* document (here `00-research-report.qmd`). You edit child documents individually and save them (without rendering[^1]). When you render the main document, each section included in it will be rendered. This workflow is optional, and you could decide that you prefer to have everything in a single file instead. I like using child documents because it makes it easier to: 1. find the part that I want to edit; 2. track my changes and feel organized 3. eliminates chance of merge issues if each collaborator works on a different part at a time.
    
2. **how to plan a section**\
    One way to ensure our report has a good flow and has everything we need it to have is by planning each section. We can do this by using comments to define a sequence of paragraphs and define what each paragraph should be about. An example of this is in the Introduction. Note that different sequences than the one in the example can also work really well. The point is only to show how to start off by defining the line up of what we will write about in a way that we think will be effective.

3.  **cross-referencing**\
    Show how to reference Sections, Equations, Figures and Tables in your main text.

4.  **reference managament**\
    This will be shown in class during the workshop using Zotero and RStudio visual editor for Quarto documents. This combo rocks. Zotero is a free software for managing references (that is, keep save papers/book information and citations as you find them). To repeat what you were shown in class, you will need to [install Zotero](https://www.zotero.org/download/) and a [Zotero connector](https://www.zotero.org/download/connectors) for your browser.
    
The folder `usresp-examples` includes pdf of winners and honorable mentions from past USRESP competitions that were shown during the workshop.

The folder `practice` includes snippets from _Psychiatric Comorbidity In Opioid Use Treatment Outcomes_ (Linda Tang, winner at 2021 Fall USRESP). I chose this work because of its relation to the biostatistics theme of the ISI-BUDS program.

### Other repo information

Author of starting content: Federica Zoe Ricci (UC Irvine)

Starting content created on: Aug 2 2023

[^1]: If you render a child document, some things may not work the same way as if you render the main doc (e.g. cross reference of a previous section). Also, if you render child documents, you will end up with many pdf files in your repos, which is a bit messy.

