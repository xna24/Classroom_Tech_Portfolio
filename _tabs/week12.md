---
title: Week 12
icon: fas fa-book-open
order: 9
wide: true
math: true
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

.genai-prompt-portal-2 {
  width: 100%;
  height: 75px;
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

.genai-portal-2 {
  width: 100%;
  height: 300px;
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

# Portfolio GenAI Tasks 1: Design an assessment task with technology

Original worksheet:

![Original worksheet](/assets/img/W12_original_worksheet.png){: style="display: block; width: 75%; height: auto; margin-left: auto; margin-right: auto;" }

- Model used: ChatGPT-5.6 Luna

## Step 0: generic redesign prompt
- Prompt used (original worksheet uploaded with the prompt as an image):

<div class="genai-prompt-portal-2" markdown="1">
Please redesign this pen-and-paper worksheet for accessibility.
</div>

- GenAI response (a single generated image)

<div class="genai-portal-2" markdown="1">
![Original worksheet](/assets/img/W12_redesign1.png){: style="display: block; width: 75%; height: auto; margin-left: auto; margin-right: auto;" }
</div>

## Step 1: redesign with a UDL approach

- Prompt used (no further image uploaded)

<div class="genai-prompt-portal-2" markdown="1">
Can you now redesign it with an UDL approach and tell me how your redesign follows one or more UDL principles or guidelines?
</div>

- GenAI response (a single generated image)

<div class="genai-portal-2" markdown="1">
![Original worksheet](/assets/img/W12_redesign2.png){: style="display: block; width: 75%; height: auto; margin-left: auto; margin-right: auto;" }
</div>

## Step 2: redesign for student with dyslexia

- Prompt used (original worksheet image attached again)

<div class="genai-prompt-portal" markdown="1">
The attached image is a part of an actual mathematics worksheet previously used with year 9 students. Redesign this assessment task to improve accessibility particularly for a student with dyslexia.

Please do not only generate a single new image. Instead, include a redesigned worksheet with written explanation (in text, not in picture) of the redesign to tell me why it is likely to support student with dyslexia. Preserve the graphs of solids used in the worksheet if necessary or redesign them to improve accessibility for students with dyslexia but tell me the visual changes and reasoning behind them.
</div>

- GenAI response (PDF of redesigned worksheet is <a href="/Classroom_Tech_Portfolio/assets/img/dyslexia_accessible_surface_area_worksheet.pdf">here</a>)

<div class="genai-portal" markdown="1">
I would redesign this worksheet using a combination of dyslexia-friendly presentation, Universal Design for Learning (UDL), and accessible assessment design. The goal is to reduce unnecessary reading, visual-search and working-memory demands so that students can focus on the intended Year 9 mathematics: calculating and comparing surface areas and forming algebraic expressions.

The redesign retains all four original questions, their mathematical objectives and their key measurements. It changes how the information is presented, rather than making the mathematics easier.

## 1. Redesigned worksheet

<img src="/assets/img/W12_redesign3_Q5.jpg" width="250">

Q5 — Composite prism

Students calculate the total surface area and give their answer to three significant figures.

Accessibility changes: clearer diagram labels, a short description of the given dimensions, more working space and a less crowded layout.

<img src="/assets/img/W12_redesign3_Q6.jpg" width="250">

Q6 — Compare two solids

Students calculate both surface areas and determine which solid has the larger surface area.

Accessibility changes: the measurements are also stated in text, and the calculation and comparison are presented as distinct steps.

<img src="/assets/img/W12_redesign3_Q7.jpg" width="250">

Q7 — Solve for \\(x\\)

Students use the surface-area equation \\(392\pi\text{ cm}^2\\) to find \\(x\\).

Accessibility changes: the relationship between the diameter, height and variable is made explicit, with enough room to write algebraic steps.

<img src="/assets/img/W12_redesign3_Q8.jpg" width="250">

Q8 — Equal surface areas

Students equate the surface-area expressions for a cylinder and cuboid, then express \\(h\\) in terms of \\(r\\).

Accessibility changes: the dimensions are explicitly restated, and students have room to construct and manipulate their own algebraic expressions.

I have also prepared a printable worksheet PDF with a larger sans-serif typeface, clearer spacing, redrawn diagrams and dedicated working areas.

Accessible surface-area worksheet

PDF · 3 pages · Questions Q5–Q8

<a href="/Classroom_Tech_Portfolio/assets/img/dyslexia_accessible_surface_area_worksheet.pdf">Open the redesigned worksheet PDF</a>

## 2. Why the redesign is likely to support a student with dyslexia

Dyslexia affects individuals differently. Some students experience difficulties with decoding written words, spelling or reading fluency; others may also find dense layouts, copying between representations or managing multiple instructions challenging. The following design choices are intended to reduce common barriers without assuming that every student with dyslexia has the same needs.

### A. Clear typography and visual organisation

Use a clear, readable sans-serif font

The redesigned worksheet uses DejaVu Sans, with larger text, clear mathematical notation and distinct bold headings. This avoids a cramped, visually complicated presentation.

Why it may help: some students find clearly differentiated letters and adequate text size easier to read. No single font is proven to be universally best for dyslexia.

Reduce visual crowding

Each question has a clear heading, a separated prompt, a diagram and a designated working area. Questions are spread across pages rather than squeezed into four dense boxes.

Why it may help: clearer visual grouping can make it easier to locate relevant information and return to the correct question after a distraction.

Maintain strong contrast

Dark text and clear lines are used against a light background. Colour is not needed to distinguish mathematical information.

Why it may help: high contrast can improve legibility for some learners. Colour overlays or tinted paper should be offered only if the individual student finds them helpful.

These changes primarily support access to the printed material. They do not eliminate the need for students to read mathematical instructions or interpret symbols.

### B. Reduce unnecessary language and memory demands

The original worksheet combines prose, measurements and diagrams, sometimes requiring students to move their attention between different parts of a small panel.

The redesigned version separates each prompt into manageable parts and restates the dimensions in text.

For example, Q6 explicitly lists:

- Triangular prism: equal sloping sides of 13 ft, base of 10 ft and length of 20 ft.
- Semi-cylinder: diameter of 10 ft and length of 30 ft.

Why this may help: students do not have to rely solely on reading small labels from the diagram or repeatedly search the picture to recover the dimensions. This can reduce incidental demands on visual attention and working memory.

The mathematical reasoning remains unchanged: students must still calculate both surface areas correctly and compare their results.

### C. Improve the diagrams without removing mathematical information

The diagrams remain central because interpreting three-dimensional solids is an intended part of the assessment.

| Visual change                                          | Reason for the change                                                                        |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| Larger, more distinct diagrams                         | Makes the dimensions and geometric relationships easier to inspect.                          |
| Consistent, clearly placed labels                      | Reduces ambiguity about which measurement belongs to which part of a solid.                  |
| Strong outlines and differentiated dashed hidden edges | Helps students distinguish visible edges from edges concealed by the three-dimensional view. |
| Written restatement of dimensions                      | Provides another way to access the same mathematical information.                            |
| Space between the diagram and the question text        | Reduces competition between visual elements.                                                 |

These changes should preserve the mathematical content. For example, Q5 still requires students to understand the semicircular and rectangular cross-section and the length of the prism. Q8 still requires them to interpret the radius, height and cuboid dimensions correctly.

A useful precaution is to avoid making the diagrams too visually simplified. Removing hidden edges, changing the perspective or omitting geometric details could unintentionally remove information students need to solve the problem.

### D. Provide structured working space without prescribing a solution

The revised worksheet includes dedicated writing lines and a short instruction at the beginning explaining that students can use equations, labelled diagrams and numbers to show their reasoning.

This may help students who find copying calculations into cramped spaces difficult or who lose track of a sequence of steps.

Importantly, the worksheet does not supply a formula or a partially completed equation for every question. Students remain responsible for selecting the relevant surface-area formulas, deciding which faces to include, setting up equations and reaching a conclusion.

This distinction matters in an assessment: supporting the process of recording mathematical thinking should not inadvertently provide the mathematical reasoning being assessed.

## 3. How the redesign follows UDL principles

UDL, or Universal Design for Learning, provides a broader framework for making the worksheet accessible to students with varied learning needs. Dyslexia-friendly formatting is one part of that approach, rather than a complete UDL intervention on its own.

The three UDL principles are engagement, representation, and action and expression.

Principle 1: Multiple means of representation

Strongly addressed

Information is presented through concise text, labelled diagrams and a written summary of the dimensions. Clear headings and spacing help students locate and interpret information.

Relevant UDL guideline: Perception and Language and symbols.

The intention is to give students more than one way to access the same mathematical information, without changing what they need to understand.

Principle 2: Multiple means of action and expression

Partly addressed

Dedicated working space and permission to use equations, numbers and labelled diagrams provide some flexibility in how students record their mathematical thinking.

Relevant UDL guideline: Physical action and Expression and communication.

To strengthen this further, the teacher could permit an equivalent oral explanation or a separately labelled diagram when handwriting or written language is an access barrier, provided the response still demonstrates the assessed mathematics.

Principle 3: Multiple means of engagement

Partly addressed

The predictable structure and one-question-at-a-time presentation may make the assessment feel more manageable and help students sustain attention.

Relevant UDL guideline: Sustaining effort and persistence and Self-regulation.

The worksheet alone offers limited choice or active engagement. These aspects could be strengthened by allowing students to choose the order in which they tackle questions, use a ruler or scrap paper, and take an agreed brief pause if required.

These connections align with the UDL framework developed by CAST. The redesign most directly addresses representation; the other principles would benefit from complementary assessment procedures and classroom practices.

## 4. Preserving assessment validity

Accessibility changes must be considered alongside the purpose of the assessment. For these Year 9 questions, I would retain the same mathematical learning objectives and the following expectations.

- Q5: Correctly calculate the surface area of a prism with a composite cross-section and round to three significant figures.
- Q6: Calculate and compare the total surface areas of two different solids.
- Q7: Translate the given dimensions into an appropriate surface-area equation and solve for \\(x\\).
- Q8: Construct and equate surface-area expressions, then rearrange to express \\(h\\) in terms of \\(r\\).

I would also be cautious about adding worked examples, sentence starters that reveal the next mathematical step, or a formula sheet if independent formula selection is part of what the assessment measures.

Instead, the teacher can separate the access arrangements from the mathematical criteria. For instance, extra time, a quieter setting, a ruler, an agreed reading accommodation or an alternative way of recording reasoning may be appropriate depending on the student's established needs and the assessment rules.

## 5. One final recommendation

Before using the redesigned worksheet for a formal assessment, I would trial it with the student and ask a few specific questions:

- Can you easily find the measurements you need?
- Is any part of the text or diagram difficult to read?
- Is there enough space to show your calculations?
- Did the layout help you understand the task, or did anything make it more confusing?

This feedback matters because dyslexia is heterogeneous: a layout that supports one student may not suit another. The strongest approach is to combine a clear, predictable worksheet with the student's own preferences and established accommodations, while keeping the intended mathematical challenge intact.
</div>

## Step 3a: generate case study examples

- Prompt used:

<div class="genai-prompt-portal" markdown="1">
I wish to see how to redesign this worksheet for some particular students individually. However, I am not allowed to disclose students' learning profiles that may contain identifiable information. Please generate 3 case-study examples of year 9 students, include:
- Interests and motivations
- Family, cultural, linguistic context
- Classroom participation or preference of communication style
- Disabilities, neurodivergence, health condition
- Literacy and numeracy readiness
- Academic strengths and areas requiring support
</div>

- GenAI response (GenAI generated images of each student has not been included for irrelevance):

<div class="genai-portal" markdown="1">
Below are three fictional Year 9 student case studies designed to help you explore how the same surface-area worksheet could be redesigned for different learners. They are composites created for educational planning, not descriptions of real students.

I've deliberately included a range of strengths, interests, family and linguistic contexts, learning needs and mathematical readiness. The profiles are not intended to suggest that a particular disability, cultural background or language automatically produces a particular learning preference.

# Three fictional Year 9 student case studies


## Case study 1: Alex

The visual thinker who finds dense text tiring

Alex is interested in drawing, model building and designing game environments. Alex can often see how objects fit together in three dimensions but finds lengthy written instructions slow to process.

Primary design focus: reading accessibility


## Case study 2: Samira

The multilingual learner with developing academic English

Samira enjoys practical science, cooking and solving problems with physical objects. She often understands a mathematical relationship before she can comfortably explain it in extended academic English.

Primary design focus: language accessibility

## Case study 3: Jordan

The capable problem-solver who benefits from structure

Jordan enjoys sport statistics, puzzles and practical challenges. Jordan can reason mathematically but sometimes loses track of multistep tasks, particularly when instructions and diagrams compete for attention.

Primary design focus: executive-function support

## Case study 1 — Alex: visual thinker, reluctant reader

### Student profile

| Dimension                                       | Fictional case-study details                                                                                                                                                                                                                                   |
| ----------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Interests and motivations                       | Enjoys sketching, digital art, building with construction sets and designing levels for video games. Motivated by tasks with a visible outcome or practical purpose.                                                                                           |
| Family, cultural and linguistic context         | Lives with a parent and a grandparent in a household where English is the main language. Family members value education and encourage creative interests. They have limited time to provide regular homework support because of work commitments.              |
| Classroom participation and communication       | Usually quiet during whole-class discussion. More willing to explain ideas using a sketch, a physical model or a brief one-to-one conversation. May avoid volunteering when reading aloud is involved.                                                         |
| Disability, neurodivergence or health condition | Has a formal diagnosis of dyslexia. Experiences persistent difficulty with reading fluency and spelling. No assumption is made about intellectual ability or visual processing.                                                                                |
| Literacy readiness                              | Understands age-appropriate spoken explanations and familiar vocabulary. Reads more slowly than many peers, especially when text is dense or contains unfamiliar technical terms. Written explanations may be shorter than the student's actual understanding. |
| Numeracy readiness                              | Secure with basic arithmetic and familiar area calculations. Can recognise common 2D and 3D shapes. Less consistent when a word problem contains several instructions or requires translating text into an equation.                                           |
| Academic strengths                              | Strong spatial intuition, creative thinking and ability to notice patterns in diagrams. Often recognises geometric relationships without immediately expressing them in formal mathematical language.                                                          |
| Areas requiring support                         | Reading lengthy prompts efficiently, distinguishing essential information from surrounding text, recording multistep reasoning and checking written responses.                                                                                                 |

### What this means for the worksheet

Alex may understand the surface-area problem but spend so much effort decoding the wording that less attention remains for mathematical reasoning.

I would redesign the worksheet by:

- Using a readable sans-serif font, generous spacing, left-aligned text and clear question headings.
- Presenting each question in a consistent sequence: task, diagram, measurements and working area.
- Keeping technical terms such as radius, diameter, curved surface and cross-section consistent throughout.
- Repeating critical dimensions in text as well as on the diagram.
- Providing sufficient space for calculations and labelled sketches.

For Q5, for example, Alex could annotate the prism diagram, mark the semicircular ends and rectangular faces, and calculate each contribution before adding them. The student would still need to identify all the external faces and calculate the correct total surface area.

UDL connection: Multiple means of representation, especially the guidelines concerning perception and language and symbols. Multiple means of action and expression may also be useful if Alex can demonstrate mathematical understanding more accurately through equations and labelled diagrams than through extended prose.

Important distinction: Dyslexia does not necessarily mean a student is a visual learner. The proposed supports respond to Alex's stated strengths and reading needs rather than assuming that all students with dyslexia benefit from the same visual format.

## Case study 2 — Samira: multilingual learner developing academic English

### Student profile

| Dimension                                       | Fictional case-study details                                                                                                                                                                                                                                                             |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Interests and motivations                       | Enjoys cooking, science experiments and practical construction tasks. Likes investigating how changing a measurement affects the final result.                                                                                                                                           |
| Family, cultural and linguistic context         | Recently arrived in Australia with family members. Arabic is the main language used at home, and Samira also uses English with peers and at school. Family members are supportive of education but may be unfamiliar with Australian mathematics terminology and assessment conventions. |
| Classroom participation and communication       | Participates actively in pair work and practical demonstrations. Often points to a diagram or writes a numerical example before explaining an idea in English. May pause or remain silent during fast-paced whole-class discussion.                                                      |
| Disability, neurodivergence or health condition | No diagnosed disability or health condition is specified in this hypothetical profile. Her developing English proficiency should not be treated as evidence of a learning disability.                                                                                                    |
| Literacy readiness                              | Can understand everyday classroom English and follow many short instructions. Unfamiliar mathematical vocabulary and complex sentence structures slow comprehension. Written explanations may not fully communicate what she understands.                                                |
| Numeracy readiness                              | Has a sound grasp of basic operations, measurement and familiar area calculations. Has had different prior experiences with some geometry notation and mathematical vocabulary.                                                                                                          |
| Academic strengths                              | Strong practical reasoning, persistence, estimation and ability to recognise relationships between quantities. Can often predict whether a change in a dimension will increase or decrease surface area.                                                                                 |
| Areas requiring support                         | Learning specialised English terminology, interpreting compound instructions, communicating comparisons precisely and becoming familiar with local mathematical conventions.                                                                                                             |

### What this means for the worksheet

Samira's central barrier may be the language used to express mathematical concepts, rather than the mathematical concepts themselves.

I would redesign the worksheet by:

- Using short, direct sentences and avoiding unnecessary idioms.
- Keeping the original mathematical terminology while explicitly explaining important words.
- Pairing written instructions with labelled diagrams and consistent notation.
- Providing a small glossary for terms such as surface area, radius, diameter, prism and semi-cylinder.
- Allowing Samira to plan using equations, sketches, annotations or bilingual notes where assessment rules permit.

For Q6, Samira could calculate the two surface areas separately, label the results and use a comparison symbol such as \\(>\\) or \\(<\\) to indicate which is larger. If a verbal justification is also required, the teacher could distinguish the mathematical reasoning from the student's developing ability to express that reasoning in academic English.

This should not remove the need to interpret the shapes or choose appropriate calculations. The objective is to make the language accessible without revealing the answer.

UDL connection: Multiple means of representation, particularly language and symbols, and multiple means of action and expression. Engagement can also be supported by connecting surface area to familiar practical applications, such as packaging or covering an object.

Important distinction: EAL/D learners are not a homogeneous group. Their prior mathematics education, literacy in their first language, English proficiency and familiarity with Australian classroom practices may differ considerably.

## Case study 3 — Jordan: mathematically capable, needs help managing multistep tasks

### Student profile

| Dimension                                       | Fictional case-study details                                                                                                                                                                                          |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Interests and motivations                       | Enjoys basketball statistics, logic puzzles and challenges involving real-world measurements. Motivated by tasks with clear goals and visible progress.                                                               |
| Family, cultural and linguistic context         | Grew up in Australia in a multilingual household where English is used for schoolwork and another family language is used regularly at home. Family members encourage independence but have busy schedules.           |
| Classroom participation and communication       | Contributes enthusiastically to discussion and may answer quickly. Sometimes starts calculating before reading the full question. Benefits from brief check-ins and opportunities to explain a strategy to a partner. |
| Disability, neurodivergence or health condition | Has ADHD. Experiences difficulties with sustaining attention, organising multistep work and checking completed answers. These needs vary by task and setting.                                                         |
| Literacy readiness                              | Reads age-appropriate texts competently but can overlook qualifiers such as “total”, “all faces” or “three significant figures” when working quickly.                                                                 |
| Numeracy readiness                              | Strong with arithmetic, substitution and familiar formulas. Can solve equations accurately when the relevant information is organised. May omit a face or skip a step when a geometry problem becomes lengthy.        |
| Academic strengths                              | Quick estimation, flexible mathematical thinking, strong number sense and willingness to try different approaches. Often identifies an efficient calculation strategy.                                                |
| Areas requiring support                         | Sustaining attention across a longer problem, organising calculations, recording intermediate steps, noticing constraints and reviewing answers.                                                                      |

### What this means for the worksheet

Jordan may know how to calculate surface area but lose marks by omitting a face, overlooking a measurement or failing to answer the question fully.

I would redesign the worksheet by:

- Using predictable question layouts and clear visual separation.
- Breaking long instructions into short, numbered actions without giving away the calculations.
- Keeping diagrams close to their prompts.
- Including enough room for intermediate steps so calculations are not squeezed into margins.
- Adding a brief self-check routine that encourages the student to review the completeness of the calculation.

For Q5, a neutral checklist might ask Jordan to check that all external faces have been considered, units are consistent and the final answer is rounded as requested. It should not tell the student exactly which surface-area formula to use if choosing that formula is part of the assessment.

UDL connection: Multiple means of engagement, especially sustaining effort and persistence and self-regulation. The clear structure also supports representation, while a flexible way to organise and record calculations supports action and expression.

Important distinction: ADHD does not necessarily imply weak mathematical understanding, low motivation or an inability to concentrate. Jordan's support needs are tied to organisation, attention and task demands, not to an assumption of lower ability.

# 4. Comparing the three redesigns

The same worksheet can be adjusted in different ways according to the barriers identified in each profile.

| Design feature                        | Alex: dyslexia                      | Samira: EAL/D                                               | Jordan: ADHD                         |
| ------------------------------------- | ----------------------------------- | ----------------------------------------------------------- | ------------------------------------ |
| Readable font and spacing             | High priority                       | Useful                                                      | Useful                               |
| Concise instructions                  | High priority                       | High priority                                               | High priority                        |
| Written dimensions alongside diagrams | Reduces repeated visual searching   | Provides language and visual links                          | Reduces missed measurements          |
| Glossary of mathematical terms        | Useful if terminology is unfamiliar | High priority                                               | Useful                               |
| Clearly separated calculation stages  | Helps organise reasoning            | Helps interpret the task                                    | Helps sustain task sequence          |
| Flexible ways to show reasoning       | Labelled diagrams and equations     | Equations, annotations and bilingual planning where allowed | Organised calculations and diagrams  |
| Self-check prompts                    | Check units and requested accuracy  | Check interpretation and comparison                         | Check completeness and skipped steps |

These are priorities, not exclusive allocations. Most of these features may help a wide range of students, including those without a diagnosis.

## 5. Applying the case studies without lowering mathematical demand

A useful design rule is to separate the barrier to accessing the question from the mathematical thinking the question assesses.

### Example: Q8 — Equal surface areas

Original mathematical objective: form surface-area expressions for a cylinder and cuboid, equate them and rearrange to express \\(h\\) in terms of \\(r\\).

Accessible for Alex

Use clear typography, larger diagrams, explicitly labelled dimensions and adequate working space. Alex must still form both expressions independently.

Accessible for Samira

Use concise wording and a glossary for radius, height, cuboid and surface area. Samira must still interpret the relationships and construct the algebraic equation.

Accessible for Jordan

Keep the prompt, diagram and measurements together, allow room to show each stage and include a final check for the requested form of the answer. Jordan must still perform the algebraic manipulation.

In all three cases, the intended mathematics remains intact. The differences concern how students access the information, organise their work and communicate what they know.

## 6. How to use these fictional profiles in your redesign project

I suggest treating each case study as a hypothesis to test, rather than a fixed description of how a student will learn.

1. Identify the mathematical knowledge each question is intended to assess.
2. Identify the unnecessary barriers the worksheet may introduce.
3. Select design changes that address the barriers described in the relevant profile.
4. Check whether any change accidentally gives away a mathematical step or changes the assessment construct.
5. Review the redesigned task against student feedback and the accuracy of their mathematical responses.

This allows you to explore individualised accessibility while protecting student confidentiality. When working with actual students, use de-identified information, share only the details necessary for the redesign and avoid combinations of personal details that could identify a student within a school community.
</div>

## Step 3b: redesign for a particular student

- Prompt used:

<div class="genai-prompt-portal-2" markdown="1">
Thanks! Now please redesign the original worksheet particularly for the learning needs of Samira (the second student in your list). Again, please do not only generate a single image. Instead, tell me what adjustment you made and why in a concise manner.
</div>

- GenAI response (a single generated image, refused to follow explicit instruction)

<div class="genai-portal" markdown="1">
<img src="/assets/img/W12_redesign4.png">
</div>

## Comments

The results are somewhat disappointing (compared to both my previous experience working with GenAI tools and the GenAI tasks in previous weeks) in the following ways:
- ChatGPT have insisted upon generating images without explaining unless explicitly prompted to do so
- generated images contain numerous errors, typos and significant mismatch between picture and description
- responses (the 3rd redesign and the case study) have been very lengthy but contain very little useful information

This could be a reflection of model limitation or my weakness in prompting skills (or most likely both). 

There are also a lot of suggestions I can learn from in the GenAI response. For instance, in the third redesign (for students with dyslexia), GenAI suggested a reasonable reformatting of the worksheet for clearer heading and question prompts and a "designated working area". ChatGPT incorrectly assumed that I intend for students to use the small image format as work space for students to write on. However, after some reflection I think student might also have the same assumption and indeed use the tiny space on the worksheet despite being explicitly instructed to use their notebooks instead. ChatGPT's redesign "separates each prompt into manageable parts" and can indeed help students with dyslexia process the information without watering down mathematical demand.

# Portfolio Task 2: Using technology for assessment in the classroom

- Choose a lesson plan

I picked <a href="/Classroom_Tech_Portfolio/assets/img/LP_Science_Year11.pdf">this</a> (partially filled) double-period lesson plan for a Year 11 science unit about wave (using NESA syllabus).

- Choose a digital tool that might be useful as a formative assessment tool

Based on the formative assessment opportunity, I choose Google Drive as the digital tool to be used in combination with cellphone camera. Its usage will elaborated below.

- Rewrite existing lesson plan to include digital formative assessment

In more detail, the learning goal of the lesson was for students to understand and be able to demonstrate how mechanical waves (sound waves in this instance) transfer energy. 

The learning activity to be moditified is a short lab session where students are given materials (e.g., tuning fork, speaker, string, ping-pong ball, paper, etc.) and they collaborate in groups to design and conduct an experiment to prove that sound wave indeed transfer energy. The original lesson plan has students fill out a lab report template detailing their design and teacher will collect and inspect the reports as a formative assessment. The rewrite targets "formative assessment: lab report" to extend it using shared videos of experiment process of different groups.

- Short justification

The digital redesign encourages students to use their cellphones to record video of their experiment, use free and open source tools (such as <a href="https://ffmpeg.guru/en/">FFmpeg.guru</a>) to compress the video to reduce size, then upload to a shared Google Drive. This then allows the teacher to share experiment set-up and process of each group with the whole class which will stimulate further discussion and serve as formative and peer assessment tool. In the meantime, the use of compression tool also models locating reliable resource online, which further contributes to "create, communicate and collaborate" sub-element under the "creating and exchanging" element in Digital Literacy general capability [(ACARA, n.d.)](/Classroom_Tech_Portfolio/references/#acara-DL).

