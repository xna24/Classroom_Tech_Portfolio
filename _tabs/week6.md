---
title: Week 6
icon: fas fa-book-open
order: 6
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

.genai-portal-2 {
  width: 100%;
  height: 600px;
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

# Portfolio tasks

## Task 1: AI (or tech)-use Decision Making

### 1. Choice of a teacher/classroom task I had to do on my last practicum

Preparing a problems set (along with solution) for a Year 11 mathematics lesson on measurement (surface area of solids) to complete during individual practice.

### 2. GenAI risk assessment

<div class="accordion" id="myAccordion">

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading1">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse1"
              aria-expanded="true"
              aria-controls="collapse1">
        Duty of care risk
      </button>
    </h2>
    <div id="collapse1"
         class="accordion-collapse collapse"
         aria-labelledby="heading1"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        There is no clear safety/privacy risk for students. This is because the problem set is generated without the input of students' personal information and students are not involved in the interaction with GenAI.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading2">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse2"
              aria-expanded="false"
              aria-controls="collapse2">
        Equity risk
      </button>
    </h2>
    <div id="collapse2"
         class="accordion-collapse collapse"
         aria-labelledby="heading2"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        Once the problem set is generated, students can participate equally either by accessing it via the screen or through the printouts. Given that this particular Year 11 class has no students requiring additional accessibility support, there is no apparent equity risk.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading3">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse3"
              aria-expanded="false"
              aria-controls="collapse3">
        Is truth central?
      </button>
    </h2>
    <div id="collapse3"
         class="accordion-collapse collapse"
         aria-labelledby="heading3"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        Accuracy is very central because hallucination in the mathematics could lead to confusion and severely undermine student learning. The teacher should complete the problem set independently and check against the GenAI solution to ensure validity of problems and accuracy of the provided solution and reasoning.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading4">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse4"
              aria-expanded="false"
              aria-controls="collapse4">
        Is the output publishable or ethical to use?
      </button>
    </h2>
    <div id="collapse4"
         class="accordion-collapse collapse"
         aria-labelledby="heading4"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        The output (the problem set) is not intended for publication and there are no direct copyright concern. However, teacher should still carefully check the problem for potential inclusion of GenAI images and where appropriate, avoid the generated images or replace them with teachers' own creation.
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading5">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse5"
              aria-expanded="false"
              aria-controls="collapse5">
        Is the environmental/labour cost worth it?
      </button>
    </h2>
    <div id="collapse5"
         class="accordion-collapse collapse"
         aria-labelledby="heading5"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        <p>Despite the negligible cost of electricity and water of a single prompt, the cumulative effect of GenAI use on energy consumption and environmental cost can quickly scale <a href="/Classroom_Tech_Portfolio/references/#jegham-et-al-2025">(Jegham et al., 2025)</a>. Therefore, there may not be a clear answer without considering the overall frequency of use. However, the effect can be minimised:</p>
        <ul>
          <li>if the teacher can reduce the number of prompts with better prompt engineering skill, and</li>
          <li>if the problem set can be reused with some manual adjustment.</li>
        </ul>
        <p>While there is no such thing as purely "ethical consumption" when it comes to GenAI use considering the exploitation of human labour that have already occurred in its training <a href="/Classroom_Tech_Portfolio/references/#furze-2023-05-22">(Furze, 2023)</a>, a relevant discussion can be incorporated into the learning activity in some form to develop students' ethical understanding <a href="/Classroom_Tech_Portfolio/references/#acara-nd">(ACARA, n.d.)</a>.</p>
      </div>
    </div>
  </div>

  <div class="accordion-item">
    <h2 class="accordion-header" id="heading6">
      <button class="accordion-button collapsed" type="button"
              data-bs-toggle="collapse"
              data-bs-target="#collapse6"
              aria-expanded="false"
              aria-controls="collapse6">
        Who benefits from the use of genAI, and who is exposed (data or power)?
      </button>
    </h2>
    <div id="collapse6"
         class="accordion-collapse collapse"
         aria-labelledby="heading6"
         data-bs-parent="#myAccordion">
      <div class="accordion-body">
        This application benefits the teacher by reducing the work load from having to search textbook or problem banks. With appropriate quality check by the teacher, it benefits the students in the same manner as a teacher-made problem set. However, the school community should also have a long term
      </div>
    </div>
  </div>

</div>

### 3. Decision

<details open markdown="1">
<summary><strong>Context</strong></summary>

- Subject: Mathematics
- Year Level: Year 11
</details>

<details open markdown="1">
<summary><strong>Decision</strong></summary>
<big><strong><u>Use with limits</u></strong></big>
</details>

<details markdown="1">
<summary><strong>2 main risks + 2 safeguards</strong></summary>
Based on the preceding commentary, the two main risks of this particular GenAI use case are identified as the validity and truthfulness of the problem set (along with the solution) and the environmental cost of running the model. The decision "use with limits" is made based on safeguards to mitigate these two risk factors by respectively:
- limit the frequency of similar GenAI use, and
- teacher manually checking the validity and appropriateness of the problems and the solution

For the first risk factor, we have noted above that the environmental cost of frequent use by teachers on a large scale is unsustainable given the accumulated energy consumption and associated carbon footprint ([Jegham et al., 2025](/Classroom_Tech_Portfolio/references/#jegham-et-al-2025)). It should be noted that any consumption of AI models trained by exploitation of human labour under unfair conditions and on large amount of original work without an easy way to attribute credit ([Furze (2023b)](/Classroom_Tech_Portfolio/references/#furze-2023-04-04)) contributes to the concentration of power into the hands of a few AI companies and cannot be addressed through actions in any one field alone ([Selwyn, 2022](/Classroom_Tech_Portfolio/references/#selwyn-2022)).

The second risk factor is the potential inaccurate and misleading information in AI-generated problem set and solution. This risk is effectively mitigated by teacher completing the problem set by himself to ensure the validity of the problem (i.e., what was tested aligns with the learning intentions set out in the unit or the lesson) as well as the correctness and appropriateness of the corresponding solution.
</details>

### 4. A tiny artefact: traffic light cards

![Traffic light cards for similar use cases based on the two main risk factors identified above](/assets/img/traffic-lights.png){: style="display: block; width: 75%; height: auto; margin-left: auto; margin-right: auto;" }
<p style="width: 75%; margin: 0.35rem auto 0; text-align: center; font-size: 0.75rem; color: #777;"> Traffic light cards for similar use cases based on the two main risk factors identified above. The cards are made in Microsoft Word and this image is a screenshot.
</p>

## Task 2: GenAI Task - “Minimum Ethical Use Conditions” A Micro-Protocol for students or colleagues

### 1. Choice of a single GenAI classroom use

GenAI classroom use: using GenAI to draft feedback to students' written assignments

### 2. Micro-protocol

<div class="genai-portal" markdown="1">
For any GenAI use in providing feedback to students:
- Anonymise students' personal information and information about the class and the school. Whenever possible, upload students' assignment in pure text format instead of images of photos to limit accidental breaches
- Examine the nature of the writing task and avoid uploading students' work entirely if the assignment submission includes sensitive personal issue (including but not limited to: trauma, abuse, physical or mental health conditions, religious or political beliefs of personal nature, immigration status) of the student or any third party (e.g., family member, friends or relatives)
- Carefully and critically examine the AI-generated feedback for accuracy and appropriateness. Always edit the AI response to ensure the feedback is strength-based rather than deficit-oriented.
- Avoid uploading students' complete work of substantial projects (e.g., depth studies or research papers). Focus on providing targeted feedback to smaller pieces
- Use marking rubric effectively and use a representative sample of students' work rather than uploading the work of a whole class to generate feedback in batch
</div>

### 3. Series of guidelines for GenAI use in the classroom

The following six rules are written for teachers concerning GenAI use in the classroom, based partly on recommendations from the [Australian Government Department of Education](/Classroom_Tech_Portfolio/references/#australian-framework):

<div class="genai-portal" markdown="1">
- **No sensitive info rule**: Never enter personal and sensitive information including but not limited to the following items or combinations: name, year level, gender, sexuality, ethnicity, country of origin, religious belief, socioeconomic status, grades and test results. Avoid disclosure of intimate personal matter or private information of a third party with AI systems.
- **Truth rule**: GenAI is not an authority and is prone to hallucinate and produce misinformation. Carefully fact-check and critically examine and revise AI-generated results (including references and quotations). 
- **Attribution rule**: Teachers and staff should disclose all relevant stake-holders of any AI use when such use impact them. When GenAI use is approved, students must disclose AI use in assignments and tasks. All disclosures should include details such as AI model and prompts.
- **Bias check rule**: Students, teachers other school staff should closely examine AI-generated content for biases (e.g., gender, ethnicity, sexuality), stereotypes, prejudices and deficit-based language. Make necessary modification before release by further prompting or manual work.
- **Copyright/publishing rule**: Do not upload copyrighted material to AI systems in manner that violate copyright regulations and legislation. Teachers and staff should avoid sharing substantial parts of students' original work (including creative work, projects, research papers, posters). Always give acknowledgement that AI-generated content may contain intellectual properties that cannot be accurately attributed.
- **Limits rule**: Teachers and staff should prioritise non-AI solution whenever possible and avoid unnecessary AI use. Students should only use GenAI in assignments when explicitly permitted by the task description and only in the manner described in the task.
</div>

<details>
<summary>Note</summary>
<small>
My understanding of item 3 "produce a series of guidelines" is for GenAI use of all members of the school community (students, teachers, school staff) in a broader context rather than just for the use case given in item 1 (feedback writing). It does not seem reasonable to first write a "micro-protocol" then write a series of guideline that essentially overlap in purpose for the same context.
</small>
</details>

### 4. GenAI improved list of rules

- GenAI model: Copilot Chat Basic (Version number: 2.20260923.61.0), Mode: Auto (Decides how long to think).

Prompt used

<div class="genai-prompt-portal" markdown="1">
I have written the following six rules concerning GenAI use in the classroom:

- **No sensitive info rule**: Never enter personal and sensitive information including but not limited to the following items or combinations: name, year level, gender, sexuality, ethnicity, country of origin, religious belief, socioeconomic status, grades and test results. Avoid disclosure of intimate personal matter or private information of a third party with AI systems.
- **Truth rule**: GenAI is not an authority and is prone to hallucinate and produce misinformation. Carefully fact-check and critically examine and revise AI-generated results (including references and quotations). 
- **Attribution rule**: Teachers and staff should disclose all relevant stake-holders of any AI use when such use impact them. When GenAI use is approved, students must disclose AI use in assignments and tasks. All disclosures should include details such as AI model and prompts.
- **Bias check rule**: Students, teachers other school staff should closely examine AI-generated content for biases (e.g., gender, ethnicity, sexuality), stereotypes, prejudices and deficit-based language. Make necessary modification before release by further prompting or manual work.
- **Copyright/publishing rule**: Do not upload copyrighted material to AI systems in manner that violate copyright regulations and legislation. Teachers and staff should avoid sharing substantial parts of students' original work (including creative work, projects, research papers, posters). Always give acknowledgement that AI-generated content may contain intellectual properties that cannot be accurately attributed.
- **Limits rule**: Teachers and staff should prioritise non-AI solution whenever possible and avoid unnecessary AI use. Students should only use GenAI in assignments when explicitly permitted by the task description and only in the manner described in the task.

Please rewrite these rules to clarify them and specifically target the following audiences in 3 separate versions
- Students (secondary context, years 7 to 12)
- Teachers
- Parents/Carers
Pay attention to the language use for each audience. For instance, student's version can be written in simplified student-friendly language that may not be technically equivalent to the original text but inform students of the main spirit of the rule.
</div>

Un-edited response

<div class="genai-portal" markdown="1">
Below are three audience-specific versions of the six rules. I have adapted the language, tone, and level of detail for each group while preserving the intent of the original policy.

Version 1: Students (Years 7-12)
1. Keep Personal Information Private

Do not type personal information into AI tools. This includes your name, age, gender, cultural background, religion, grades, health information, or anything private about you or someone else.

Remember: If you would not post it publicly online, do not put it into an AI chatbot.

2. Don't Assume AI Is Always Right

AI can make mistakes, make up information, or get facts wrong.

Always:

Check facts using trusted sources.
Think critically about AI responses.
Make sure quotes, references, and information are accurate before using them.
3. Be Honest About Using AI

If your teacher allows AI for an assignment, you must say when and how you used it.

This may include:

Which AI tool you used.
What prompts or questions you asked.
Which parts of the work were supported by AI.

Using AI without acknowledging it may be considered academic misconduct.

4. Check for Fairness and Respect

AI sometimes produces biased, unfair, or stereotypical content.

Before submitting or sharing AI-generated work:

Check that people and groups are represented fairly.
Remove stereotypes or offensive language.
Make sure your work is respectful and inclusive.
5. Respect Other People's Work

Do not upload copyrighted materials to AI tools unless your teacher has specifically told you it is allowed.

Do not upload:

Other students' work.
Books, articles, images, or media that you do not have permission to use.

Remember that AI-generated content may sometimes include ideas or material that belong to someone else.

6. Only Use AI When Allowed

Only use AI when your teacher says it is allowed.

When AI is permitted:

Follow the instructions for the task.
Use AI only in the ways your teacher has approved.
Complete the work yourself rather than relying on AI to do everything for you.
Version 2: Teachers
1. Protect Personal and Sensitive Information

Do not enter students' personal, sensitive, or identifiable information into GenAI systems.

This includes, but is not limited to:

Names and identifying details
Academic records, grades, and assessment results
Gender, sexuality, ethnicity, religion, or cultural background
Health, wellbeing, behavioural, family, or socioeconomic information

Avoid disclosing confidential information about students, colleagues, or families unless explicitly authorised and compliant with privacy requirements.

2. Verify AI-Generated Content

GenAI tools are not authoritative sources and may generate inaccurate, fabricated, outdated, or misleading information.

Teachers should:

Fact-check AI-generated content using reliable sources.
Verify references, quotations, and citations.
Exercise professional judgement before using AI-generated materials in teaching, assessment, communication, or decision-making.

Responsibility for accuracy remains with the staff member, not the AI system.

3. Be Transparent About AI Use

Teachers should disclose AI use whenever it materially affects students, colleagues, families, or other stakeholders.

Where appropriate, disclosures should include:

The AI tool or model used
The purpose of its use
Relevant prompts, instructions, or workflows
The extent to which AI contributed to the final output

Teachers should also ensure students understand and comply with AI disclosure requirements in assessment tasks.

4. Review Content for Bias and Inclusion

AI-generated content may contain bias, stereotypes, prejudicial assumptions, or deficit-based representations.

Before publication or use, teachers should:

Review outputs for cultural responsiveness and inclusion.
Check representations relating to gender, ethnicity, sexuality, disability, religion, and other protected characteristics.
Revise, re-prompt, or manually edit content to ensure it aligns with school values and professional standards.
5. Respect Copyright and Intellectual Property

Staff must not upload copyrighted materials to AI systems in ways that infringe copyright law, licence agreements, or school policies.

Particular care should be taken with:

Student work and creative products
Assessment materials
Commercially licensed resources
Published text, images, audio, and video

Where AI-generated content is used, acknowledge that intellectual property ownership and attribution may not always be clear or verifiable.

6. Use AI Purposefully and Proportionately

AI should be used where it provides a clear educational, administrative, or professional benefit.

Teachers should:

Prefer non-AI approaches when they are effective and practical.
Avoid unnecessary or excessive reliance on AI systems.
Ensure AI supports, rather than replaces, professional expertise, pedagogy, and human decision-making.
Version 3: Parents and Carers
1. Protect Your Child's Privacy

Do not enter personal or sensitive information about your child, yourself, or other families into AI tools.

This includes information such as:

Names and contact details
School reports and grades
Health information
Family circumstances
Cultural, religious, or personal background details

As a general rule, avoid sharing information that could identify a child.

2. Check Information Carefully

AI tools can provide useful assistance, but they can also make mistakes and generate inaccurate information.

Before relying on AI-generated information:

Check important facts with trusted sources.
Verify quotations and references.
Use your own judgement when making decisions about your child's education.
3. Be Open About AI Use

If AI has been used to help create written communication, schoolwork, or other significant materials, it is good practice to acknowledge that assistance.

Transparency helps schools, families, and students maintain trust and understanding about how AI is being used.

4. Watch for Bias and Stereotypes

AI systems can sometimes reflect social biases or stereotypes.

When reviewing AI-generated content, consider whether:

Particular groups are portrayed unfairly.
Assumptions have been made about people or communities.
The language is respectful, inclusive, and appropriate.
5. Respect Copyright and Student Work

Avoid uploading copyrighted materials or students' original work into AI systems without appropriate permission.

Parents and carers should take care when sharing:

School assignments
Artwork and creative projects
Student photographs
Other materials that belong to students, teachers, or publishers

AI-generated content may also contain material whose original source cannot be clearly identified.

6. Use AI as a Support Tool, Not a Replacement

AI can be a helpful tool for learning, but it should not replace teachers, parents, carers, or students' own thinking.

Encourage your child to:

Develop their own ideas and skills.
Use AI only when appropriate.
Follow school expectations regarding AI use.
Learn how to think critically about AI-generated information.

These versions intentionally shift from compliance-focused language (teachers) to behaviour-focused language (students) and supportive guidance language (parents/carers), making the same principles accessible and relevant to each audience.
</div>

#### Edited guidelines for students

<details>
<summary>Edit note</summary>
<small>
Shortened some parts. Removed the requirement for students to check GenAI content for fair representation because I believe it works best as a learning activity instead of an enforced rule. Removed certain items that are somewhat redundant (e.g., last dot point from rule 6). Changed format to keep the output short. I have noticed that AI output tend to be unnecessarily long and vertically stretched. In actual practice, I should try to fit the list on a one-page printout to give to students.
</small>
</details>

<div class="genai-portal-2" markdown="1">
1. Keep personal information private
- Do not type personal info into AI tools. This includes name, age, gender, cultural background, religion, grades or anything private about you or someone else. If you would not post it publicly online, do not give it to AI chatbot.

2. Do not assume AI is always right
- Check facts using trusted sources
- Think critically about AI responses
- Make sure quotes, references and information are accurate before using them

3. Be honest about using AI
- Only use AI  for assignment if your teacher allows it
- Disclose how you used AI, including which AI tool you used, what part of work were supported by AI and what prompts or questions you asked.

4. Check for fairness and respect
- AI output can be biased, unfair or contain racist stereotype
- Check carefully to remove stereotypes or offensive language
- Make sure your work is respectful and inclusive

5. Respect other people's work
- Do not upload copyrighted material to AI tools unless explicitly your teacher has specifically instructed that the use is allowed
- Do not upload: other students' work, books, articles, images, or media that you do not have permission to use.
- Remember that AI-generated content may sometimes contain ideas or material that belong to someone else

6. Only use AI when allowed
- Only use AI in assignments when it is explicitly permitted
- Use AI only in the ways approved by your teacher
- Reduce reliance on AI use in other learning tasks such as explaining or summary. Ask teachers or your peer first if you need assistance.
</div>

#### Edited guidelines for teachers

<details markdown="1">
<summary>Edit note</summary>
<small>
Shortened some parts and condensed formatting. Changed wording at certain parts. For instance, added a "no harm" component to the limit rule. I was only reminded of this when reading the GenAI output, but it is actually also aligned with the suggestions in the [Australian Framework for GenAI in Schools](/Classroom_Tech_Portfolio/references/#australian-framework).
</small>
</details>

<div class="genai-portal-2" markdown="1">
1. Protect Personal and Sensitive Information
- Do not enter students' personal, sensitive, or identifiable information into GenAI systems.
  - Includes but not limited to: names, academic records, grades, gender, sexuality, ethnicity, religion, cultural background, health, wellbeing, behavioural, family, or socioeconomic information.
- Avoid disclosing confidential information about students, colleagues, or families unless explicitly authorised and compliant with privacy requirements.

2. Verify AI-Generated Content
- GenAI tools are not authoritative sources and may generate inaccurate, fabricated, outdated, or misleading information.
- Teacher should fact-check AI-generated content using reliable non-AI sources
- Verify references, quotations, and citations
- Exercise professional judgement before using AI-generated material in teaching, assessment, communication, or decision-making.

3. Be Transparent About AI Use
- Teacher should disclose AI use whenever it materially affects students, colleagues, families, or other stakeholders.
  - Disclosures should include where appropriate: the AI tool or model used; the purpose of its use; relevant prompts; extend to which AI contributed to the final output
- Teachers should ensure students understand and comply with AI disclosure requirements in assessment tasks

4. Review Content for Bias and Inclusion
- AI-generated content may contain bias, stereotypes, prejudicial assumptions or deficit-based representations
- Before publication or use, teachers should
  - Review output for cultural responsiveness and inclusion
  - Check representations relating to gender, ethnicity, sexuality, disability, religion, and other protected characteristics
  - Revise, re-prompt or manually edit content to ensure it aligns with school policies and professional standards

5. Respect Copyright and Intellectual Property
- Staff must not upload copyrighted materials to AI systems in ways that infringe copyright law, license agreements, or school policies.
- Particular care should be taken with: 
  - students work and creative products
  - assessment materials
  - commercially licensed resources
  - published text, images, audio, video
- Where AI-generated content is used, acknowledge that intellectual property ownership and attribution may not always be clear or verifiable.

6. Use AI Purposefully and Proportionately
- AI should be used where it provides a clear educational, administrative, or professional benefit and where it does not cause harm to wellbeing or rights of students, teachers, staff, parents/carers or the wider-community
- Prioritise non-AI approaches when they are effective and practical
- Avoid unnecessary or excessive reliance on AI systems
- Ensure AI supports, rather than replaces, professional expertise, pedagogy, and human decision-making
</div>

#### Unedited guideline for parents/carers

<div class="genai-portal" markdown="1">
1. Protect Your Child's Privacy

Do not enter personal or sensitive information about your child, yourself, or other families into AI tools.

This includes information such as:

Names and contact details
School reports and grades
Health information
Family circumstances
Cultural, religious, or personal background details

As a general rule, avoid sharing information that could identify a child.

2. Check Information Carefully

AI tools can provide useful assistance, but they can also make mistakes and generate inaccurate information.

Before relying on AI-generated information:

Check important facts with trusted sources.
Verify quotations and references.
Use your own judgement when making decisions about your child's education.
3. Be Open About AI Use

If AI has been used to help create written communication, schoolwork, or other significant materials, it is good practice to acknowledge that assistance.

Transparency helps schools, families, and students maintain trust and understanding about how AI is being used.

4. Watch for Bias and Stereotypes

AI systems can sometimes reflect social biases or stereotypes.

When reviewing AI-generated content, consider whether:

Particular groups are portrayed unfairly.
Assumptions have been made about people or communities.
The language is respectful, inclusive, and appropriate.
5. Respect Copyright and Student Work

Avoid uploading copyrighted materials or students' original work into AI systems without appropriate permission.

Parents and carers should take care when sharing:

School assignments
Artwork and creative projects
Student photographs
Other materials that belong to students, teachers, or publishers

AI-generated content may also contain material whose original source cannot be clearly identified.

6. Use AI as a Support Tool, Not a Replacement

AI can be a helpful tool for learning, but it should not replace teachers, parents, carers, or students' own thinking.

Encourage your child to:

Develop their own ideas and skills.
Use AI only when appropriate.
Follow school expectations regarding AI use.
Learn how to think critically about AI-generated information.
</div>

### 5. Comments

- Where did the AI rewrite improve?
  - AI rewrite improved clarity and polished the language in my original guideline
  - AI response also improved accessibility by, e.g., rewriting the guidelines in student-friendly language
- Where did it distort/oversimplify?
  - Copilot mostly kept loyal to the rules I have made in part 3 with a few exceptions
  - One example of distortion is its assumption that bias check applies to students and teachers in identical manner, when in fact this is not realistic nor advisable given students' limited AI-literacy
- What did you change and why?
  - See "Edit notes" above
  