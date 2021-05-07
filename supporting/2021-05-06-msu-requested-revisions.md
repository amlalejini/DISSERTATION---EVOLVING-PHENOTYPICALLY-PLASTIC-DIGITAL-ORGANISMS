# 2021-05-06 - Formatting feedback from MSU

- [x] Name comparison: your name must match in all aspects of your submission. Your ProQuest ETD contact details state that your name is Alexander Michael Lalejini. Your title page, abstract page and copyright page state that your name is Alexander Lalejini. Note: when you submit your approval form your name on that must match the rest of your submission as well.
  - RESPONSE: Changed ETD contact details to 'Alexander Lalejini'

- [x] Title page: between Ecology, Evolutionary Biology and Behavior—Dual Major and 2021 is to be one double space.
  - RESPONSE: Added vertical space size of line skip between EEB and year.

- [x] Dedication page: this is the 4th page in the document so it should be numbered as iv, not ii. As a result, you will need to renumber the remainder of the preliminary pages.
  - RESPONSE: Update `\thispagestyle{empty} \setcounter{page}{2}` to `\thispagestyle{empty} \setcounter{page}{4}`

- [x] ACKNOWLEDGMENTS page: after the heading, only double space twice. You have far too much space here currently.
  - RESPONSE: Fix `vspace` after ACKNOWLEDGEMENTS

- [x] TABLE OF CONTENTS: the heading TABLE OF CONTENTS is to be centered, 1inch from the top of the page. It is too far down on the page currently.
  - RESPONSE: Tweak `cftbeforetoctitleskip` to adjust spacing from top of page.

- [ ] TABLE OF CONTENTS: after the heading, only double space twice. You have too much space here currently.
  - RESPONSE: Tweak `cftaftertoctitleskip`
  - TODO - double check spacing

- [x] Page 31 heading 2.3.1: since the heading is going onto two lines anyway, it would look better if plasticity was not hyphenated and it was all on the 2nd line.
  - RESPONSE: Use `raggedright` environment to tell latex it's okay to do what the MSU people want

- [x] Page 32 There is a lot of blank space between the caption for Table 2.2 and the document text. You could eliminate some of the blank space.
  - RESPONSE: Subtract some vspace after caption.

- [x] Page 33 heading 2.3.2: since the heading is going onto two lines anyway, it would look better if phenotypic was not hyphenated and it was all on the 2nd line.
  - RESPONSE: Use `raggedright` environment

- [x] Page 40 heading: 2.3.5: since the heading is going onto two lines anyway, it would look better if phenotypic was not hyphenated and it was all on the 2nd line. Make this correction where needed throughout the remainder of the document.
  - RESPONSE: $&*# Raggedright everywhere!
    - Sections: 2.3.5, 3.3.1, 3.3.3, 5.5.1, 5.5.3

- [x] Page 80 the spacing after 4.3.1 is too large. Remove one of the double spaces. Review your entire document to ensure that the spacing between headings and text is consistent throughout the document.
  - RESPONSE: use `raggedbottom` environment for entire document...

- [ ] Please submit the signed Approval Form. This form is taken as evidence that your document has been examined and approved by the major professor. The approval form, with the required signatures can be submitted to the Graduate School by email to msuetds.approval@grd.msu.edu . The approval form may be found at: https://grad.msu.edu/etd/Required-Paperwork-and-Surveys.
  - RESPONSE: Filled out new form. Check with Charles if he received an email.

- [x] Please submit the IRB Approval letter if human subjects were used or the IACUC letter if animal subjects were used. This may be submitted to the Graduate School by email to msuetds.approval@grd.msu.edu *****NOTE: if you used human subjects and your name does not appear on the IRB Letter you must provide documentation that you are an approved researcher on the project. Either send a screenshot from the “CLICK” site where you are listed as a researcher OR have your PI send an email to msuetds.approval@grd.msu.edu stating the IRB number, the project title and that you are an approved researcher on the project. (If you used animal subjects, your name does not need to appear on the IACUC letter.) 
