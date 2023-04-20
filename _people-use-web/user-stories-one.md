---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Alan, reporter with limited use of his arms"
nav_title: "Alan"
parent_in_h1:
  - ref: /people-use-web/user-stories/
    name: nav_title
  - ref: /people-use-web/
    name: nav_title

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2021-@@-@@   # Put the date of this translation YYYY-MM-DD (with month in the middle)

# translators:    # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-people-use-web
  path: people-use-web/user-stories-one.md    # Add the language shortcode to the middle of the filename, for example: people-use-web/user-stories-one.fr.md
permalink: /people-use-web/user-stories-one/   # Add the language shortcode to the end, with no slash at end, for example: /people-use-web/user-stories-one/fr

navigation:
  previous: /people-use-web/user-stories/
  next: /people-use-web/user-stories-two/

ref: /people-use-web/user-stories-one/      # Translators, do not change this
changelog: /people-use-web/changelog/
acknowledgements: /people-use-web/user-stories/acknowledgements/

description: add @@ - @@possibly create separate social images later
image: /content-images/wai-people-use-web/social.png

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
   <p><strong>Date: Draft in progress.</strong> Updated @@ Month 2021. First published Month 20@@. CHANGELOG.</p>
   <p><strong>Editors:</strong> Kevin White, Mark Palmer, Jane Schurick, and <a href="https://www.w3.org/People/shadi/">Shadi Abou_Zahra</a>.  <strong>Contributors:</strong> @@name, @@name, and <a href="https://www.w3.org/groups/wg/eowg/participants">participants of EOWG</a>. ACKNOWLEDGEMENTS lists past editors and additional contributors.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Previously developed with the <a href="https://www.w3.org/WAI/EO/2008/wai-age-tf">WAI-AGE Task Force</a>, with support of the <a href="https://www.w3.org/WAI/WAI-AGE/">WAI-AGE Project</a>.</p>

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Introduction to Alan

**Note:** The following scenario is not about a real person. It may not address every person with this disability.

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2..2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## About Alan

> It's not like I can't use a keyboard or mouse, I just can't use it for long periods because it is tiring.

Alan was involved in a accident which caused a spinal cord injury. This left him with limited use of his arms and no movement or sensation in his legs. He has worked as a reporter for more than 20 years. Alan uses a keyboard with larger keys to help him more easily hit the correct key and a joystick instead of a mouse. However, using these for extended periods can be tiring so he has started using speech recognition software for some tasks, such as dictating long pieces. 

Rather than using his fingers, Alan uses the palm of his hand to operate a joystick that has an enlarged lever. This can be inaccurate to use, particularly when pointing to and clicking on small areas. When this happens, he sometimes switches to using the keyboard for navigation. He can use the tab key to move through links and form elements. When using the keyboard, Alan has found that on some sites he couldn't see which field or link had focus. He also found that sometimes the links weren't in a logical order, which made it hard to find the element he was interested in. He could always use his joystick but that can interrupt his flow and slow him down. Sites often include good visual styling when you hover over a link but sometimes don't include this when the link has keyboard focus. For Alan, it is important that websites clearly show which link has the current focus and to navigate through links in a logical order, that is, following the visual order of links on the page.

When using a keyboard, Alan has found some features which really help. For example, a skip link that moves focus past all the navigation on the page is a big help. Alan tries to avoid sites that don't have this feature. However, it limits his research sources a bit.

Alan has started using speech control software which helps him to avoid having to use the joystick and keyboard. It is early days and he is not sure of how to use all the features. The software allows him to select and 'click' on links by speaking but only when the links are clear and coded correctly. The software also has a speech-to-text dictation feature. As someone who has spent years typing out his articles, Alan is having to train himself in a new way of working. He would still prefer to type as he thinks he is much slower with dictation but is hopeful that his speed will improve.

Outside of work, Alan finds his mobile device easier to use than the computer because there is limited navigation and no pointer device. Since it is hand-held, he has more options to place it in a position that he is comfortable with. He wishes his employer would create a mobile-friendly or responsive site that he could use for his job.

## Barrier examples

Focus styling barrier
: **Problem:** "When I tab through links and form fields there is no visual styling to show me which element I am on."
: **Works well:** "There is clear and strong visual styling for links and form fields when they receive focus."

Process time outs barrier
: **Problem:** "I usually take much longer to complete long forms or processes and often get timed out."
: **Works well:** "At the start of a long form or process, I am told that there is a time out and given the option to set it to be slightly longer."

Saving progress barrier
: **Problem:** "Completing long forms with no way to save progress and take a break can be tiring."
: **Words well:** "I have an option to save progress and take a break when completing long, multi-step forms like when I have to get a code in email or text and type it in."

Popup windows barrier
: **Problem:** "When a window opens and I can't close it using only the keyboard it can be difficult."
: **Works well:** "New windows have a close icon that I can access using the keyboard and some include the option to press the escape key to close them."

## Assistive technologies and adaptive strategies used

* [Accelerators (Input)](/people-use-web/tools-techniques-input/#accelerators)
* [Alternative keyboard and mouse (Input)](/people-use-web/tools-techniques-input/#input)
* [Speech recognition (Input)](/people-use-web/tools-techniques-input/#speech)
* [Word prediction (Input)](/people-use-web/tools-techniques-input/#prediction)
* [Keyboard navigation (Interaction)](/people-use-web/tools-techniques-navigation/#keyboard)
* [Skip links (Interation)](/people-use-web/tools-techniques-navigation/#skip)

## Related WAI resources

* Video: [Speech Recognition](https://www.w3.org/WAI/perspective-videos/voice/)
* Tip: [Use headings to convey meaning and structure](https://www.w3.org/WAI/tips/writing/#use-headings-to-convey-meaning-and-structure)
* Tip: [Make link text meaningful](https://www.w3.org/WAI/tips/writing/#make-link-text-meaningful)
* Tip: [Ensure that interactive elements are easy to identify](https://www.w3.org/WAI/tips/designing/#ensure-that-interactive-elements-are-easy-to-identify)
* Tip: [Associate a label with every form control](https://www.w3.org/WAI/tips/developing/#associate-a-label-with-every-form-control)
* Tip: [Ensure that all interactive elements are keyboard accessible](https://www.w3.org/WAI/tips/developing/#ensure-that-all-interactive-elements-are-keyboard-accessible)
* Check: [Keyboard access and visual focus](https://www.w3.org/WAI/test-evaluate/preliminary/#interaction)
* Check: [Forms, labels, and errors](https://www.w3.org/WAI/test-evaluate/preliminary/#forms)

## Related principles

* [Text alternatives for non-text content (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#alternatives)
* [Content can be presented in different ways (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#adaptable)
* [Functionality is available from a keyboard (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#keyboard)
* [Users have enough time to read and use the content (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#time)
* [Users can easily navigate, find content, and determine where they are (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#navigable)
* [Content appears and operates in predictable ways (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#predictable)
* [Users are helped to avoid and correct mistakes (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#tolerant)
* [Content is compatible with current and future user tools (Robust)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#compatible)
