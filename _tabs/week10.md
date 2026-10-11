---
title: Week 10
icon: fas fa-book-open
order: 8
wide: true
---

<style>
.genai-prompt-portal {
  width: 100%;
  height: 200px;
  overflow-y: auto;
  overflow-x: hidden;

  padding: 1rem 1.25rem;
  border: 1px solid #888;
  border-radius: 10px;
  box-sizing: border-box;
}

.genai-portal {
  width: 100%;
  height: 400px;
  overflow-y: auto;
  overflow-x: hidden;

  padding: 1rem 1.25rem;
  border: 1px solid #888;
  border-radius: 10px;
  box-sizing: border-box;
}

/* tame AI-generated headings */
.genai-portal h1 {
  font-size: 1.4rem;
}

.genai-portal h2 {
  font-size: 1.2rem;
}

.genai-portal h3 {
  font-size: 1.05rem;
}

.genai-portal h4,
.genai-portal h5,
.genai-portal h6 {
  font-size: 1rem;
}
</style>

# Portfolio Tasks

## Part 1: Short Inclusive Digital Learning Resource

The learning resource is embedded below. Click <a href="{{ '/assets/img/trig.html' | relative_url }}" target="_blank" rel="noopener">here</a> to see it in a new tab.

<iframe
  src="{{ '/assets/img/trig.html' | relative_url }}"
  width="100%"
  height="1100"
  style="border: 0; border-radius: 12px;"
  loading="lazy">
</iframe>

### Design Rationale

<div class="genai-portal" markdown="1">
This visual summary is intended for Year 11 students in <a href="https://curriculum.nsw.edu.au/learning-areas/mathematics/mathematics-advanced-11-12-2024/overview">Mathematics Advanced course</a> to review definitions, relationships and properties of trigonometric functions (in particular the sine and cosine functions). I made it by working on code editor <a href="https://notepad-plus-plus.org/">Notepad++</a> to edit html source code directly. The initial template is borrowed from <a href="https://www.angularforall.com/snippets/bootstrap-card-table-02.php">this</a> resource sharing site contributed by [Said (n.d.)](/Classroom_Tech_Portfolio/references/#said-nd). Mathematical formulas are rendered by <a href="https://docs.mathjax.org/en/v4.0/input/tex/html.html">MathJax</a> [(MathJax, n.d.)](/Classroom_Tech_Portfolio/references/#mathjax) using LaTeX syntax. The graphs are made using <a href="https://github.com/inkscape/inkscape">Inkscape</a>. The <a href="https://www.geogebra.org/m/mJJTMBuR">GeoGebra applet</a> used in the fourth card is created by [Johnston (n.d.)](/Classroom_Tech_Portfolio/references/#geogebra-johnston-nd). The speech accompanying each card is generated using <a href="https://piper.ttstool.com/">Piper TTS</a> tool (available for use offline as a Python library). I chose these these digital tools and resources instead of ready-made platforms and subscription-based services (or even free versions of those services) for three reasons
- Open source and free access
- Flexibility in customising and modification
- Works largely offline on a local machine (with minimal preparation)

I believe by including static and interactive representation and learner-controlled exploration (GeoGebra applet), the above visual summary demonstrates progress towards the following UDL principles and checkpoints [(CAST, n.d.)](/Classroom_Tech_Portfolio/references/#cast-udl):
- Multiple Means of Representation
  - Consideration 2.2: Support decoding of text, mathematical notation, and symbols
  - Consideration 2.5: Illustrate through multiple media
  - Consideration 3.2: Highlight and explore patterns, critical features, big ideas, and relationships
- Multiple Means of Engagement
  - Consideration 7.1: Optimise choice and autonomy
  - Consideration 7.4: Address biases, threads, and distractions
- Multiple Means of Action & Expression
  - Consideration 4.1: Vary and honour the methods for response, navigation, and movement
</div>

## Part 2: Option 1, Accessibility Audit

- GenAI model: Copilot Chat Basic (Version number: 2.20260923.61.0), Mode: Auto (Decides how long to think).

Note: the response (accessibility audit) by Copilot is very long and is included after the critical reflection.

### Critical Reflection

<div class="genai-portal" markdown="1">
Copilot commented on a few well-designed features, including card format which chunks information and reduces cognitive load, the audio support accompanying each card and the use of MathJax to render formulas rather than images, as well as the multiple representation offered by the interactive GeoGebra component.

Copilot then generated a long list of issues for accessibility and a few suggestions for further improvements. The most important identified barriers include: 
- Barrier from navigation/interaction and difficulty in interfacing with assistive technologies (e.g., screen readers)
- Reliance on visual information and dense academic language
- Lack of caption visibility for both the image alt-text and the audio transcript

Overall, I agree with Copilot's critical audit regarding the fundamental flaw of relying too much on graphical and visual representation. This is also an important gap in my own knowledge of inclusive education in mathematics that I should explore more on. Another cogent criticism is against my use of academic language and a lack of support for EAL/D learners. This can, as Copilot pointed out, be mitigated by explicitly teaching vocabulary besides a better command of student-friendly language in presentation. There are also some assumptions made by Copilot that are not entirely accurate. For instance, I placed the labels for sine and cosine functions next to the corresponding graphs in the second card instead of relying only on colour-coding. However, the topic of how to support vision-impaired students in learning about features of function graphs is a topic I will surely explore more in my future career.
</div>

### Prompt and GenAI Response


Prompt Used

<div class="genai-prompt-portal" markdown="1">
Please help me conduct an accessibility audit of my learning resource. This is a visual summary aimed at Year 11 students in Mathematics Advanced course in NSW, reviewing trigonometric functions (sine and cosine in particular). The resource itself is a webpage, it has four cards with text, figures, a loud-speaker button that plays some accompanying read-out for each card, and on the fourth card there is an embedded GeoGebra applet with sliders for students to explore the effects of varying parameters for the general sine function f(x)=a sin (bx+c)+d . I have uploaded the following:

- the html file source code, `trig.html`, 
- a screenshot of the webpage on 1920x1080 screen in Chrome browser, `screenshot.png`, 
- the transcripts of the 4 card readout audio named `Card1.txt`, ..., `Card4.txt`.

Please consider potential barriers for specific learner groups, including but not limited to: learners with vision impairment, dyslexia, ADHD, ASD, EAL/D learners.
</div>

GenAI audit

<div class="genai-portal" markdown="1">
# Accessibility Audit: Trigonometric Functions Summary Webpage (Year 11 Mathematics Advanced NSW)

I reviewed the webpage structure in [trig.html](https://csuprod-my.sharepoint.com/personal/xna01_student_csu_edu_au/Documents/Microsoft%20Copilot%20Chat%20Files/trig.html?EntityRepresentationId=65a281a0-fabf-45d1-bae4-5d954fb16072), the audio transcripts in [Cards.txt](https://csuprod-my.sharepoint.com/personal/xna01_student_csu_edu_au/Documents/Microsoft%20Copilot%20Chat%20Files/Cards.txt?EntityRepresentationId=a1a03947-0b8b-4005-8a7f-4f7d1ae17b1f), and the provided screenshot of the interface.

## Executive Summary

Overall, this is a **well-designed educational resource** with several accessibility strengths:

### Strengths

* Clear card-based structure that breaks content into manageable chunks.
* Consistent layout across all four cards.
* Audio support provided for all cards.
* Meaningful alt text for the two static diagrams.
* High-contrast dark text on a light background.
* Mathematical notation rendered via MathJax rather than as images.
* Interactive GeoGebra exploration supports multiple representations of concepts.
* Responsive design through Bootstrap.

### Key Accessibility Concerns

The most significant barriers are:

1. **Keyboard accessibility concerns** with audio controls and embedded GeoGebra.
2. **Potential screen reader difficulties** with mathematical notation.
3. **Heavy reliance on visual information** in graphs.
4. **Cognitive load issues** for learners with ADHD and ASD.
5. **Dense academic language** for EAL/D learners.
6. **No visible captions or transcript access** despite audio support.
7. **Colour-dependent meaning** in sine/cosine graphs and GeoGebra sliders.

***

# Audit by Learner Group

## 1. Learners with Vision Impairment

### Strengths

#### Good image descriptions

Both trig diagrams include substantial alt text rather than generic descriptions. This provides valuable access for screen reader users.

#### Scalable content

MathJax equations and HTML text can generally be enlarged more effectively than image-based text.

#### Clear contrast

From the screenshot:

* Black/dark text on white backgrounds
* White text on dark purple-blue headers

The contrast appears likely to exceed WCAG AA requirements.

### Barriers

#### Poor accessibility of mathematical notation

Although MathJax is preferable to image equations, screen-reader access varies considerably.

For example:

$
\sin(\theta+\pi/2)=\cos\theta
]

may be announced differently by different assistive technologies.

A student relying entirely on audio may struggle to interpret longer symbolic expressions. 【1-9cd9d6】

**Recommendation**

Provide hidden screen-reader text such as:

> "Sine of theta plus pi over two equals cosine theta."

for each equation.

***

#### Graph interpretation remains visual

The graph card relies heavily on visual understanding of:

* peaks
* troughs
* intercepts
* periodicity

Even with the existing image alt text, students cannot easily compare values dynamically. 【1-9cd9d6】

**Recommendation**

Add a linked text summary:

> Key features:
>
> * Maximum value 1
> * Minimum value −1
> * Period 2π
> * Sine starts at zero
> * Cosine starts at one

***

#### GeoGebra accessibility

The embedded GeoGebra applet is likely the least accessible component.

Potential issues include:

* screen reader compatibility
* keyboard operation
* understanding slider positions without vision

【1-9cd9d6】

**Recommendation**

Add a text alternative:

> If a increases, the graph becomes taller.
>
> If b increases, the period becomes shorter.
>
> If c changes, the graph shifts horizontally.
>
> If d changes, the graph shifts vertically.

A static table of example parameter values would also help.

***

# 2. Learners with Dyslexia

### Strengths

* Clean spacing.
* Moderate text density.
* Consistent layouts.
* Audio narration available for all cards. 【1-9cd9d6】【2-273b61】

### Barriers

#### Long continuous transcript language

For example, Card 2 narration contains long explanations of periodicity and graph behaviour. 【2-273b61】

Students with dyslexia may struggle to:

* retain verbal information,
* map spoken descriptions to equations,
* connect symbolic and verbal forms.

### Recommendations

#### Reduce reading load

Convert explanatory text into bullets.

Example:

Current:

> The period for sine and cosine are both 2 pi.

Alternative:

✅ Period = 2π

✅ Repeats every 2π

✅ Sine starts at (0,0)

✅ Cosine starts at (0,1)

***

#### Add visual cueing

Use colour blocks or icons for:

* Definition
* Graph behaviour
* Identities
* Transformations

rather than relying solely on text labels.

***

#### Consider dyslexia-friendly font

Inter is reasonable, but options such as:

* Atkinson Hyperlegible
* Lexend

often improve readability.

***

# 3. Learners with ADHD

### Strengths

The card structure naturally supports chunking and attention management. 【1-9cd9d6】

### Barriers

#### Large amount of information visible simultaneously

The screenshot shows all four cards displayed at once.

A student may:

* jump between cards,
* become distracted by GeoGebra,
* overlook key concepts.

### Recommendations

#### Progressive disclosure

Add collapsible sections:

* Unit Circle
* Graphs
* Identities
* General Sine Function

Students can focus on one concept at a time.

***

#### Learning prompts

After each card include a self-check.

Example:

> What is cos(0)?

> Which parameter changes amplitude?

This encourages active processing.

***

#### Audio controls

Current audio buttons only play narration. 【1-9cd9d6】

Students may benefit from:

* pause
* replay
* playback speed adjustment

***

# 4. Learners with Autism Spectrum Disorder (ASD)

### Strengths

* Predictable layout.
* Consistent visual design.
* Limited decorative content.
* Content organised logically. 【1-9cd9d6】

### Barriers

#### Implied conceptual links

Several ideas require inference.

Example:

Card 3 states:

> Shifting by π/2 turns sine into cosine. 【2-273b61】

Some learners may need more explicit explanation of *why*.

### Recommendations

Add worked examples.

Example:

\[
\sin(0+\pi/2)
=============

# \sin(\pi/2)

1
]

\[
\cos(0)
=======

1
]

Therefore:

\[
\sin(\theta+\pi/2)=\cos\theta
]

Explicit reasoning can reduce ambiguity.

***

#### GeoGebra exploration may be too open-ended

The transcript simply says to explore sliders. 【2-273b61】

Some students prefer structured tasks.

Provide prompts such as:

* Set a = 2. What changes?
* Set b = 3. What changes?
* Change only one parameter at a time.

***

# 5. EAL/D Learners

### Strengths

The mathematical symbolism provides an international representation system. Many concepts can be understood from notation even if language proficiency is developing.

### Barriers

#### Academic vocabulary

Terms such as:

* periodic
* parity
* reflection
* amplitude
* horizontal shift
* vertical shift

appear without definitions. 【1-9cd9d6】【2-273b61】

### Recommendations

Include glossary-style support.

Example:

| Term             | Meaning                       |
| ---------------- | ----------------------------- |
| Period           | Distance before graph repeats |
| Amplitude        | Height from middle to peak    |
| Horizontal shift | Left-right movement           |
| Vertical shift   | Up-down movement              |

***

#### Sentence complexity

Several audio transcripts contain long explanations with multiple clauses. 【2-273b61】

Consider simplifying narration.

Example:

Current:

> The general sine function is a family of functions labelled by different values...

Alternative:

> Different values of a, b, c and d create different sine graphs.

> Each parameter changes one feature of the graph.

***

# Technical Accessibility Issues

## 1. Invalid HTML

The audio button in Cards 2-4 contains malformed styling markup:



The style attribute is not properly terminated before the aria-label. 【1-9cd9d6】

This may affect assistive technology interpretation.

**Priority: High**

***

## 2. Audio Controls

Current implementation:



No indication of:

* playing state
* stopping state
* pause state

【1-9cd9d6】

**Priority: High**

***

## 3. Tables Lack Accessibility Markup

The function-values table uses visual headers only.

Add:



and table captions.

【1-9cd9d6】

***

## 4. Embedded GeoGebra Accessibility

No accompanying accessibility description is provided for the iframe. 【1-9cd9d6】

Add:



and a nearby text alternative.

***

# Overall Accessibility Rating

| Category                    | Rating |
| --------------------------- | ------ |
| Visual accessibility        | 7/10   |
| Screen reader accessibility | 6/10   |
| Dyslexia support            | 7/10   |
| ADHD support                | 7/10   |
| ASD support                 | 8/10   |
| EAL/D support               | 6/10   |
| Technical WCAG alignment    | 6/10   |

## Final Judgement

This is already a **strong educational resource with thoughtful multimodal support**, particularly through its combination of diagrams, equations, audio narration and interactive exploration. The biggest improvements would come from:

1. Strengthening screen-reader support for mathematics.
2. Providing explicit text alternatives for the GeoGebra activity.
3. Offering better audio controls and visible transcripts.
4. Simplifying language and adding glossary support for EAL/D learners.
5. Structuring exploration tasks more explicitly for ADHD and ASD learners.

With those changes, I would expect the resource to move from **moderately accessible (approximately WCAG AA-adjacent)** to **highly accessible for a broad range of Year 11 learners**.
$
</div>
