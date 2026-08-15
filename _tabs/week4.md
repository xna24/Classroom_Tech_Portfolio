---
title: Week 4
icon: fas fa-book-open
order: 4
---

# Portfolio task: Two Models and One Lesson

## My lesson idea: an overview

Below is a lesson idea for year 11 mathematics (a unit of work on trigonometry and geometry) that I have planned for during my last placement but did not materialise due to logistics restrictions. The main activity involves collaborative small groups to work on a series of questions all involving the standard cube:

![Standard cube in three-dimensional space](/assets/img/cube_learning_activity.png){: style="display: block; width: 100%; height: auto; margin-left: auto; margin-right: auto;" }

The questions range from closed-form ones such as tabulating all congruence types of triangles made up of vertices of the cube to open-ended ones such as designing a building based on a cubic design with a tilted window and justify the architecture choice (e.g., budget, energy efficiency). The whole activity is facilitated by a [JavaScript applet](https://xna24.github.io/math_teaching/tinyCAD.html) allows students to plot points and lines in 3D (but not other geometric objects) using a minimalist programming language (syntax such as `Point (x,y,z)` and `Line (x1, y1, z1) to (x2, y2, z2)`).

## Model 1: SAMR

- This model helps me notice that this simple open-source resource have fulfilled <u>augmentation</u> level through enhancing pencil-paper drawing by allowing students to freely construct, modify, and drag to change viewing angle and interact with the 3D model in ways not easily achievable without this digital resource. It may have even reached <u>modification</u> level since it allows for significant redesign of the task compared to tech-free alternative ([Kohnke & Zou (2025)](#kohnke-zou-2025)).
- I find that in the lens of SAMR, the pedagogical focus of this learning activity (e.g., encouraging collaboration and perseverance through trial and error) are lost by projecting into a one-dimensional measure of how much the technology reshapes the task.

## Model 2: TPACK

- As suggested [Marcovitz and Janiszewski (2015)](#marcovitz-janiszewski-2015), TPACK model is suitable in the evaluation phase of a cycle of continuing improvement. In my case, it helped me realise the disproportional demand of TK (technology knowledge) and although I like how this learning activity itself challenged my JavaScript coding abilities, it is perhaps wiser to re-direct my limited TK to more manageable lesson designs in my future teaching career and rely more on existing resources and collaboration with colleagues (to take advantage of their technological content knowledge or technological pedagogical knowledge)
- What [Marcovitz and Janiszewski (2015)](#marcovitz-janiszewski-2015) have also reminded me is that TPACK is a bit too teacher-focused. It focuses singularly on the demand of teacher knowledge instead on how the learning experience might be for students.

## What might this look like in a real classroom?

Here are some potential complications of my lesson idea utilising digital technology:
- In actuality, I first wrote this applet in Python and shared it using Google Colab only to find out on the day of the lesson that the placement school do not allow students to login. Since I cannot sacrifice lesson time to teach everybody how to install Python on their laptops, I chose to use GeoGebra 3D instead and had to implement a completely different lesson activity
- A technical access issue is that students do not all have computer mouse and clicking and dragging might be a bit awkward. Since the activity is left as an optional one students could complete at home, some student may experience poorer accessibility of internet and laptop computers at home which is an equity issue I should have considered.
- One no tech alternative is to allow students to build actual 3D models using paper or boxboards and glue.

## GenAI task: summary of models, strengths and weaknesses

- GenAI model: [ChatGPT-5.6 Luna (free plan)](#open-ai-nd)

- Prompt used: 

> I have uploaded 4 readings regarding models and frameworks of digital technologies in education. I'm interested in comparing these two models in particular: `SAMR` model and `TPACK` model. Please generate for me a diagram that summarises the models, their strengths and weaknesses. Please do so with the readings in mind but not exclusively restricted to information available in the reading. Please also include a list of references you have used to make this diagram for me (excluding the readings). Thanks!

- Summary diagram:

![ChatGPT-generated summary/comparison of SAMR vs TPACK model](/assets/img/ChatGPT_model_comparison_summary.png){: style="display: block; width: 100%; height: auto; margin-left: auto; margin-right: auto;" }

## References

<span id="kohnke-zou-2025"></span>

- Kohnke, L., & Zou, D. (2025). Artificial intelligence integration in TESOL Teacher education:
Promoting a critical lens guided by TPACK and SAMR. TESOL Quarterly.

<span id="marcovitz-janiszewski-2015"></span>

- Marcovitz, D., & Janiszewski, N. (2015, March). Technology, models, and 21st-century learning:
How models, standards, and theories make learning powerful. In Society for information
technology & teacher education international conference (pp. 1227-1232). Association for the
Advancement of Computing in Education (AACE).

<span id="open-ai-nd"></span>

- OpenAI (n.d.). ChatGPT: Pricing Retrieved from: [https://chatgpt.com/pricing/](https://chatgpt.com/pricing/)