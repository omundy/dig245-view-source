
# View Source

![view source](assets/img/console-what-is-code.png)

<sup>Paul Ford <a href="https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/">What is Code?</a> 2015</sup>



## Introduction

Design and code a [concrete poem](https://www.theguardian.com/artanddesign/gallery/2017/apr/07/masterpieces-concrete-poetry-pictures-getty-center-ian-hamilton-finlay-augusto-campos) using HTML/CSS/JS. Exhibit good development practices using browser DevTools.

<details>
<summary>Learning Objectives, Preparation, Rubric</summary>

### Learning Objectives

Students who complete this assignment will be able to:

- Recall the main structural tags required for HTML documents
- Describe how to use Chrome DevTools for web development
- Compare reasons and locations for using `<style>`, `<link>`, and `<script>` tags
- Code a web page using HTML, CSS, and Javascript

### Preparation

Complete the following to prepare for this assignment: 

- Chapter 2 of Critical Web Design
- Course content listed on the schedule

### Rubric

See Moodle.

</details>





## Design

Follow the prompt in Chapter 2 of *Critical Web Design* ...

1. Select a text to visualize from a [manifesto](#manifestos) or other source.
1. Find [inspiration](#inspiration) in other works.
1. Create a [wireframe](https://www.figma.com/resource-library/what-is-wireframing/) for your concrete poem. Then create additional designs (bring them all to class!) to improve your layout.
1. Your text and/or design should somehow reflect on concepts from the "View Source" chapter 






## Code

1. Fork this repository and clone it to your machine.
1. Use HTML, CSS, and JS to code your design in `index.html`
1. Style your page with CSS using `<style>` tag or an external stylesheet file. 
1. Use DevTools to inspect your page in the browser and experiment with different CSS rules to control its display. Refer back to your wireframe and the [CSS box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) documentation as needed. See also this [Chrome Dev Tools](https://www.youtube.com/watch?v=25R1Jl5P7Mw) (11:49) tutorial.
1. Incorporate design choices using focal point and contrast to add context or new meaning to the text in your design. Use the eye movement test often to ensure your layout matches your intentions.
1. Use `console.log()` to show a citation for the quote, poem, or manifesto you selected in the Console. Include the title, author, date, and a link to the original. Finally, log a license for work.
1. See Chapter 2 for more details.



## Publish

1. [Save and refresh](https://github.com/omundy/learn-computing/blob/main/topics/keyboard-shortcuts.md#web-development-edit-save-refresh-loop) your work in the browser often to see your changes.
1. Commit changes regularly.
1. Confirm valid [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/) <sup>([?](https://github.com/omundy/dig245-critical-web-design/blob/main/topics/html-css/css.md#css-validation))</sup>
1. When finished, push, publish, and post all deliverables to Moodle per documentation in the Assignments.





<!-- 
<= 2022 prompts

1. Using an ordered list, write step by step instructions for viewing the source code of a web page in your favorite browser. Include the name of the browser.
1. Using an unordered list, write three other things you can do with the Dev Tools.
1. Invent and add a new unique metaphor for this action (e.g. “Looking under the hood”).
1. Find a website with a secret message in the console or source code (see examples below). Add a screenshot and link to the page with instructions to see the mesage.
1. Using Javascript, add your own secret message for curious users to the console that somehow *reflects on the content of this assignment*. Add your code using either the `script` tag at the end of the document, or link to an external `.js` file. Experiment with different `console` [methods](https://developer.mozilla.org/en-US/docs/Web/API/console).
1. Add an image of your favorite animal somewhere on the page. -->


<!--
<= 2019 PROMPTS

Explain how your metaphor communicates the act of looking at source code
1. Does it still communicate your experience of being able to look “under the hood” after you now have learned to code?
1. Why is it important to be able to look at the source code of a web page when you are making web pages?
1. Did you look at source code to make something this semester? Write about it.
1. Why is it important to see how things you consume are constructed? What are the larger sociological arguments for transparency? Think about ingredients in the food you eat or chemicals from a factory or how laws are made for example. -->






## Resources

### Technology

- Course resources [HTML](https://github.com/omundy/dig245-critical-web-design/blob/main/topics/html-css/html.md), [CSS](https://github.com/omundy/dig245-critical-web-design/blob/main/topics/html-css/css.md), [JS](https://github.com/omundy/dig245-critical-web-design/blob/main/topics/javascript/javascript.md), [Figma](https://github.com/omundy/dig245-critical-web-design#figma), [Bootstrap](https://github.com/omundy/dig245-critical-web-design#bootstrap)
- [Mozilla Developer Guides](https://developer.mozilla.org/en-US/docs/Web/Guide)


### Inspiration

- 📚 "View Source" (chapter 2) in *Critical Web Design*
- Chapter [examples](https://criticalwebdesign.github.io/book/#chapter-2-view-source): 
[Poem (Shake)](https://criticalwebdesign.github.io/book/02-view-source/examples/poem-shake.html), 
[Poem (Think)](https://criticalwebdesign.github.io/book/02-view-source/examples/poem-think.html), 
[After Gerhard Rühm](https://criticalwebdesign.github.io/book/02-view-source/examples/after-ruhm.html), 
[Poem (Click)](https://criticalwebdesign.github.io/book/02-view-source/examples/poem-click.html), 
[Poem (Chaos)](https://criticalwebdesign.github.io/book/02-view-source/examples/poem-chaos.html) 
- Related projects (and tags [#poetry](https://criticalwebdesign.github.io/index#poetry) [#visual poetry](https://criticalwebdesign.github.io/index#visual-poetry) [#text](https://criticalwebdesign.github.io/index#text)) in the [Critical Web Design Index](https://criticalwebdesign.github.io/index/)...
  - Rafaël Rozendaal [abstractbrowsing.net](http://www.abstractbrowsing.net) (2014)
  - Ben Grosser [Safebook](https://bengrosser.com/projects/safebook/) (2018) 
  - Matt DesLauriers [Concrete](https://generative-unfoldings.mit.edu/works/concrete/view.html)
  - Allison Parrish [Compasses](https://sync.abue.io/issues/190705ap_sync2_27_compasses.pdf) ([see also](https://bombmagazine.org/articles/compass-poems/)) and [other works](https://portfolio.decontextualize.com/)
  - Ruth Lin [Web Experiments](https://ruthl.in/small-web-tests)
  - Nick Montfort [Progress](https://thehtml.review/01/progress.html) (2022) 
  - Nick Montfort and (Stephanie Strickland) [Sea and Spar Between](https://nickm.com/montfort_strickland/sea_and_spar_between/index.html) (2011)





### Manifestos

- 📚 First Things First [Introduction](https://www.emigre.com/Essays/Magazine/FirstThingsFirstRevisited), [1960 Manifesto](http://www.designishistory.com/1960/first-things-first/), and [2020 Manifesto](https://www.eyemagazine.com/feature/article/first-things-first-manifesto-2000)
- [Big Data Manifesto](https://molleindustria.org/files/BIG-DATA.html) inspired by Tristan Tzara's [DADA soulève tout](https://www.moma.org/collection/works/184054?artist_id=13398&page=1&sov_referrer=artist) (1921)
- [1000manifestos.com](https://1000manifestos.com/list/)


### Articles

- 📚 Michael Bierut “Warning: May Contain Non-Design Content” (11-13) in Seventy-nine Short Essays on Design (2007)
- 📚 Frank Chimero [How and Why](https://shapeofdesignbook.com/chapters/01-how-and-why/) (18-27) in [The Shape of Design](https://shapeofdesignbook.com/chapters/01-how-and-why/) (18-27)
- 📚 Figma [02-What is Graphic Design](https://www.figma.com/resource-library/what-is-graphic-design/) (1-9) 



### Other examples of visual poetry 

- [Gerhard Rühm](https://www.google.com/search?q=Gerhard+R%C3%BChm+concrete+poem)
- [Endless Constellations: On Women in Concrete Poetry 1959–1979](https://www.google.com/search?q=Endless+Constellations%3A+On+Women+in+Concrete+Poetry+1959%E2%80%931979)
- [Augusto de Campos](https://www.google.com/search?q=augusto+de+campos+concrete+poetry) + [more](https://www.theguardian.com/artanddesign/gallery/2017/apr/07/masterpieces-concrete-poetry-pictures-getty-center-ian-hamilton-finlay-augusto-campos)
- [Guillaume Apollinaire](https://en.wikipedia.org/wiki/Calligrammes)
- other works in this collection on [UbuWeb](https://www.ubu.com/vp) 



### Console Examples

See: https://omundy.github.io/console.love 

![view source](assets/img/jodi-wwwwwwwww-1.png)
![view source](assets/img/jodi-wwwwwwwww-2.png)
[wwwwwwwww.jodi.org](https://wwwwwwwww.jodi.org/)

![view source](assets/img/console-ericwbailey.design.png)
[ericwbailey.design](https://ericwbailey.design/)

![view source](assets/img/console-zhi.hu.png)
[zhihu.com](https://www.zhihu.com/)

![view source](assets/img/console-text-game.png)
[google "text adventure"](https://www.google.com/search?q=text+adventure) [microsoft](https://microsoft.github.io/join-dev-design/)



<details>
<summary>Past examples</summary>

- 2025
    [Matthew](https://matthewpearso.github.io/dig245-view-source/)
    [Dmytro](https://dmku33.github.io/web-dev-view-source/)
- 2023
    [Maria](https://mafajardo23.github.io/dig245-view-source/)
    [Richard](https://aequor29.github.io/dig245-view-source/)
    [David](https://davidmhilton.github.io/dig245-view-source/)
    [Nam](https://namdao2508.github.io/dig245-view-source/)
    [Blake](https://blakecraig25.github.io/dig245-view-source/)
    [Riana](https://rianadoctor.github.io/dig245-view-source/)
    [Tyler](https://tyleryandt18.github.io/dig245-view-source/)
    [Meredith](https://merhaines.github.io/dig245-view-source/)
    [Isabell](https://isabelra26.github.io/dig245-view-source/)
    [Alp](https://alpnix.github.io/dig245-view-source/)

</details>

