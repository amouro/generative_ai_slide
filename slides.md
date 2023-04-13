---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Destructive Innovation with Generative AI

How Generative AI could improve our workflow

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/amouro/generative_ai_slide" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# What is your feeling about the AI?

- Feel anxious about it ⭐️⭐️⭐️⭐️⭐️
- Feel excited about it ⭐️⭐️⭐️⭐️⭐️
- I don't know about it at all ⭐️⭐️⭐️⭐️⭐️

---
transition: fade-out
---

# Understanding Generative AI

### Key Concepts and Applications

- 🤹 **Artificial Intelligence**: Generative AI is a subset of AI, where algorithms create new content, designs, or solutions by learning from data.

- 🛠 **Machine Learning**: It uses machine learning techniques, particularly deep learning, to train models on large datasets, allowing them to generate new outputs based on patterns they've learned.

- 🎨 **Creativity**: Generative AI can create content such as text, images, music, or even code, enabling machines to exhibit human-like creativity in various domains.

- 📝 **Data-driven**: The quality of generated content depends on the volume and diversity of training data, which helps the AI model to understand context and produce relevant results.

- 🧑‍💻 **Applications**: Generative AI is utilized in various industries, including art, marketing, entertainment, research, and automation, providing value by automating tasks, enhancing creativity, and generating novel solutions.

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: fade-out
---

# Would you be replaced by AI?

### You won't be, but your work may

![](/images/2023-04-12-20-56-48.png)


---
transition: slide-up
---

# Would you be replaced by AI?

### You won't be, but your work may

![](/images/2023-04-12-23-24-26.png)

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# How can we use AI to improve our workflow

1. Semantic Search
1. Video Transcription
1. Automate Content Drafting
1. Design an Application UI

---

# Semantic Search

---

# Video Transcription
Current workflows

![](/images/eng_transcribing.png)

---

# Video Transcription
Current workflows

![](/images/ja_transcribing.png)

---

# Video Transcription
Transcribing with OpenAI

streamlit_whisper

---

# Video Transcription
Transcribing with OpenAI

![](/images/openai_transcribing.png)

---

# Automate Content Drafting
Generative Summary

<video src="/images/generative_summary.mp4" width="600" height="300" autoplay></video>

---

# Design an Application UI



---
transition: fade-out
---

# ChatGPT

What to do with ChatGPT
1. Do not use it as Search engine / Do ask it to summarize from a provision content
2. Do not try to jailbrake it / Do instruct it to talk in a template
3. Do not ask it to calculate / Use calculator
4. Do not use vague instruction / Do step by step instruction and start from simple task


---
class: px-20
---

# Challenge in OIST

1. Need python developer and good data scientist 
2. Cost could be high for semantic search
3. Cost is impossible to predict
4. Concerns of the authenticity?
5. Ready to embrace the tool?

---

# Opportunity in OIST

- Government is actively want to leverage the ChatGPT in work. 
- Universities are trying to make policy of using the ChatGPT.
- We are using AI already

---

# What we should do

- Start trying to use AI to improve your work, find how to emplify your efforts
- Think how AI could be part of your work in two years.

---
transition: fade-out
---

# What is your feeling about the AI NOW?

- Feel anxious about it ⭐️⭐️⭐️⭐️⭐️
- Feel excited about it ⭐️⭐️⭐️⭐️⭐️
- I don't know about it at all ⭐️⭐️⭐️⭐️⭐️

