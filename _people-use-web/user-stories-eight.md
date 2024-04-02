---
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Stefan, young student with attention deficit hyperactivity disorder and dyslexia"
nav_title: "Stefan"
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
  path: people-use-web/user-stories-eight.md    # Add the language shortcode to the middle of the filename, for example: people-use-web/user-stories-eight.fr.md
permalink: /people-use-web/user-stories-eight/   # Add the language shortcode to the end, with no slash at end, for example: /people-use-web/user-stories-eight/fr

navigation:
  previous: /people-use-web/user-stories-seven/
  next: /people-use-web/user-stories-nine/

ref: /people-use-web/user-stories-eight/      # Translators, do not change this
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

<style>
  #introduction p {
    font-size:120%;
    margin: 0.5em 0 0 0;
  }
  #introduction .box-i {
  }
  #introduction nav {
    border: 0;
    margin-top: 0;
  }
  #introduction nav header {
    padding: 8px 16px;
  }
  #introduction .video-card {
    margin: 1em;
    float: none !important;
    max-width: inherit !important;
    min-width: 45% !important;
  }
  #introduction .video-card p {
    font-size: 90%;
    margin: 0;
  }
  #introduction .video-card p:first-child {
    height: 190px;
  }
  #introduction img.video {
    border-radius: 5px;
    width: 300px;
    max-width: 300px;
  }
  #introduction .video-card .play-button {
    position: relative;
    top: -55px;
    left: -185px;
    width: 60px;
    height: 60px;
  }
  @media all and (min-width: 576px) {
    #introduction .box-i {
      display: flex;
      flex: 0 1;
    }
    #introduction .video-card .play-button {
      position: relative;
      top: -120px;
      left: 120px;
      width: 60px;
      height: 60px;
    }
  }
</style>

<aside id="introduction" class="box"><div class="box-i">
  <div>
{:/}

Stefan is a student who has dyslexia and attention deficit hyperactivity disorder (ADHD). Stefan finds it hard to maintain focus on his schoolwork, especially when reading a lot of dense text or following written instructions. He likes digital textbooks and websites that allow him to use text-to-speech software because he can follow both the written and auditory words. It’s important though that websites and other digital technology use plain language, a consistent layout, and don’t display pop-up ads or moving images, which are very distracting and confusing. Mobile apps and websites are often less cluttered and easier to use. 

{::options toc_levels="2..2" /}

{::nomarkdown}
  </div>
  <div class="video-card">
    {% include video-player-data.html
        video-id="user-stories_8"
        yt-id="Ie-RaV7UTCU"
    %}
    <p><a href="#transcript">Text Transcript with Descriptions of Visuals</a></p>
  </div>
</div>

{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
    
</aside>
{:/}

**Note:** This user story is an example of a person with this type of disability. Other people with this disability may have different experiences.

## About Stefan

> My text reader helps me focus on what I am reading. I don't use it all the time but for long text it is super helpful.

Stefan is a student with dyslexia and attention deficit hyperactivity disorder (ADHD). As a person with ADHD, Stefan has difficulty following multi-step or long tasks. This can make it hard to maintain focus on his schoolwork. Visual supports, such as icons and images, and good use of whitespace around what he is looking at can help him to focus. He can become lost in dense text and is unable to find the meaning. When this happens he gives up because it takes too long and is tiring. This has caused him to fall behind in his work compared to other students.

Stefan's school has recently transitioned to using digital textbooks. This has been a huge improvement for Stefan who can now use his text-to-speech software to aid his understanding of what are sometimes complex texts. Stefan also uses the web for research. Unfortunately, his experience on the web can be varied. Often sites contain content such as animated advertisments and graphics which he can find distracting.
 
Stefan finds it easier to use websites that have a simple and consistent layout with content written in plain language. Images or icons can also help to reinforce the meaning of the text. Sometimes he uses functionality in his text-to-speech software that allows him to change the page background color. This is especially helpful when he is tired. Stefan also uses captions when watching videos because both hearing and seeing the words reinforces their meaning.

Stefan is a fan of old science fiction movies and spends a lot of time on fan made sites and forums. He has spending limits on his card and he uses this to buy fan memorabilia. The design of these sites and purchasing process can make this difficult. They are often quite busy with distracting advertisements and complicated checkout forms. He has found that he can access these sites on his mobile phone where he can switch on the browser reading mode to remove a lot of the background clutter. This allows him to focus on the task and makes the steps much clearer.

Stefan experiences problems with sites where the navigation of the site is unclear. He finds it much easier to use sites that include functions such as a sitemap, breadcrumb trails, or a search function. Stefan has difficulty with spelling so benefits from search functionality, which suggests alternative spellings and error corrections.

## Barrier examples

Spelling suggestions
: **Problem:** "I have difficulty with spelling and sometimes misspell words. Sometimes I don't get the search results I'm looking for."
: **Works well:** "I like when search tools offer alternative spellings or alternative search suggestions instead of just returning no results."

Distracting pop-ups
: **Problem:** "Banner ads and popups can be distracting for me, especially if they contain moving text or images."
: **Works well:** "It's great when I can turn off these images and also any background audio. If the site includes controls to allow me to do that then that's great. Even better if I can turn these off using an ad blocker in my browser."

Complex language
: **Problem:** "Complex language and sentence structure are confusing to me and hard to read and retain. 
: **Works well:** Use short sentences and plain language as much as possible."

Excessive acronyms and abbreviations
: **Problem:** "Excessive use of acronyms and abbreviations is distracting and I often must reread several times or sometimes just get stuck and give up."
: **Works well:** "Spell out the complete words of an acronym at least the first time it is used. Avoid or explain abbreviations."

## Assistive technologies and adaptive strategies used

* [Captions (Perception)](/people-use-web/tools-techniques-perception/#captions)
* [Screen reader (Perception)](/people-use-web/tools-techniques-perception/#sr)
* [Text-to-speech (Perception)](/people-use-web/tools-techniques-perception/#tts)
* [Pop-up and animations blockers (Presentation)](/people-use-web/tools-techniques-presentation/#blockers)
* [Reading assistants (Presentation)](/people-use-web/tools-techniques-presentation/#reading)
* [Spelling and grammar tools (input)](/people-use-web/tools-techniques-input/#lexical)
* [Consistency and predictability (Interaction)](/people-use-web/tools-techniques-navigation/#consistency)
* [Helpful error and success messages (Interaction)](/people-use-web/tools-techniques-navigation/#messages)
* [Keyword search (Interaction)](/people-use-web/tools-techniques-navigation/#search)
* [Multiple navigation mechanisms (Interaction)](/people-use-web/tools-techniques-navigation/#navigating)

## Related WAI resources

* Use case: [Tal: A Student who has Dyslexia and Impaired Eye Hand Coordination](https://www.w3.org/TR/coga-usable/#tal-a-student-who-has-dyslexia-and-impaired-eye-hand-coordination)
* Use case: [Yuki: A Yoga Teacher who has AD(H)D](https://www.w3.org/TR/coga-usable/#yuki-a-yoga-teacher-who-has-ad-h-d)
* Video: [Clear Layout and Design](https://www.w3.org/WAI/perspective-videos/layout/)
* Tip: [Use headings to convey meaning and structure](https://www.w3.org/WAI/tips/writing/#use-headings-to-convey-meaning-and-structure)
* Tip: [Make link text meaningful](https://www.w3.org/WAI/tips/writing/#make-link-text-meaningful)
* Tip: [Provide clear instructions](https://www.w3.org/WAI/tips/writing/#provide-clear-instructions)
* Tip: [Keep content clear and concise](https://www.w3.org/WAI/tips/writing/#keep-content-clear-and-concise)
* Tip: [Include alternative text for images](https://www.w3.org/WAI/tips/developing/#include-alternative-text-for-images)
* Tip: [Help users avoid and correct mistakes](https://www.w3.org/WAI/tips/developing/#help-users-avoid-and-correct-mistakes)
* Tip: [Ensure that interactive elements are easy to identify](https://www.w3.org/WAI/tips/designing/#ensure-that-interactive-elements-are-easy-to-identify)
* Tip: [Provide easily identifiable feedback](https://www.w3.org/WAI/tips/designing/#provide-easily-identifiable-feedback)
* Tip: [Use headings and spacing to group related content](https://www.w3.org/WAI/tips/designing/#use-headings-and-spacing-to-group-related-content)
* Check: [Image text alternatives ("alt text")](https://www.w3.org/WAI/test-evaluate/preliminary/#images)
* Check: [Headings](https://www.w3.org/WAI/test-evaluate/preliminary/#headings)
* Check: [Forms, labels, and errors](https://www.w3.org/WAI/test-evaluate/preliminary/#forms)
* Check: [Moving, Flashing, or Blinking Content](https://www.w3.org/WAI/test-evaluate/preliminary/#moving)
* Check: [Basic structure check](https://www.w3.org/WAI/test-evaluate/preliminary/#structure)

## Related principles

* [Text alternatives for non-text content (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#alternatives)
* [Content can be presented in different ways (Perceivable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#adaptable)
* [Users have enough time to read and use the content (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#time)
* [Users can easily navigate, find content, and determine where they are (Operable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#navigable)
* [Content is readable and understandable (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#readable)
* [Content appears and operates in predictable ways (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#predictable)
* [Users are helped to avoid and correct mistakes (Understandable)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#tolerant)
* [Content is compatible with current and future user tools (Robust)](https://www.w3.org/WAI/fundamentals/accessibility-principles/#compatible)
