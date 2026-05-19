---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: JinsookLee2025.jpg
  image_circular: False # crops the image to make it circular
  more_info: 


selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="bio-row" markdown="1">

<div class="bio-photo">
<img src="{{ '/assets/img/JinsookLee2025.jpg' | relative_url }}" alt="Jinsook Lee" class="img-fluid rounded z-depth-1">
</div>

<div class="bio-text" markdown="1">

I'm a Ph.D. candidate in Information Science at Cornell University. I'm co-advised by [René F. Kizilcec](https://rene.kizilcec.com){:target="_blank"} in the [Future of Learning Lab](https://learning.cis.cornell.edu/){:target="_blank"} and [Thorsten Joachims](https://www.cs.cornell.edu/people/tj){:target="_blank"}, with [Nikhil Garg](https://gargnikhil.com){:target="_blank"} on the committee. I'm also fortunate to collaborate with [National Tutoring Observatory](https://nationaltutoringobservatory.org){:target="_blank"}, and [AJ Alvero](https://ajalvero.com){:target="_blank"}.

My research examines sociotechnical systems in education. My goal is to develop and evaluate responsible AI that supports an equitable society where future generations can thrive safely.

</div>

</div>

## research

<div class="research-list">

  <div class="research-item">
    <div class="research-thumb"><img src="{{ '/assets/img/digital_divide_thumbnail.png' | relative_url }}" alt="LLM usage by SES bar chart"></div>
    <div class="research-body">
      <div class="research-title">College Admissions and AI &amp; Policy</div>
      <p class="research-desc">I study how AI is reshaping U.S. higher education with two major threads: (1) post-affirmative-action admissions, asking how ML-driven decisions trade off diversity against arbitrariness, and (2) the equity implications of generative AI in admissions, comparing pre- and post-GPT application essays across socio-economic groups to ask what now counts as an admissible essay.</p>
      <p class="research-meta">
        <span class="meta-label">papers</span>
        <a href="{{ '/publications/#lee2026algorithmicVoices' | relative_url }}">The Digital Divide in Generative AI</a> · <a href="{{ '/publications/#lee2024affirmativeaction' | relative_url }}">Ending Affirmative Action Harms Diversity Without Improving Academic Merit</a>
      </p>
      <p class="research-meta">
        <span class="meta-label">press</span>
        <a href="https://www.insidehighered.com/news/admissions/traditional-age/2026/05/08/study-explores-ai-written-admissions-essays" target="_blank">Inside Higher Ed</a> · <a href="https://news.cornell.edu/stories/2024/11/race-blind-college-admissions-harm-diversity-without-improving-quality" target="_blank">Cornell Chronicle, 2024</a> · <a href="https://news.cornell.edu/stories/2025/09/ai-can-write-your-college-essay-it-wont-sound-you" target="_blank">Cornell Chronicle, 2025</a>
      </p>
    </div>
  </div>

  <div class="research-item">
    <div class="research-thumb"><img src="{{ '/assets/img/nto_pipeline.png' | relative_url }}" alt="NTO RAG/LLM semantic chunking pipeline"></div>
    <div class="research-body">
      <div class="research-title">Improving Annotation Quality of Pedagogical Dialogue Acts</div>
      <p class="research-desc">As part of the early studies at the <a href="https://nationaltutoringobservatory.org" target="_blank">National Tutoring Observatory</a>, I apply technical approach to improve tutoring move annotation. I challenge the current utterance-level annotation unit and propose a segmentation method using LLMs and other dialogue-segmentation algorithms.</p>
      <p class="research-meta">
        <span class="meta-label">papers</span>
        <a href="https://arxiv.org/abs/2604.03127" target="_blank">Domain-Adapted Retrieval for In-Context Annotation of Pedagogical Dialogue Acts</a> · <a href="{{ '/publications/#lee2026dynamicSegmentation' | relative_url }}">Codebook-Injected Dialogue Segmentation</a> · <a href="{{ '/publications/#ahtisham2026aiannotation' | relative_url }}">AI Annotation Orchestration</a>
      </p>
      <p class="research-meta">
        <span class="meta-label">support</span>
        NSF · Gates Foundation · Chan Zuckerberg Initiative
      </p>
    </div>
  </div>

  <div class="research-item">
    <div class="research-thumb"><img src="{{ '/assets/img/social-life.png' | relative_url }}" alt="Relational skills icon"></div>
    <div class="research-body">
      <div class="research-title">Measuring Relational Skills with AI Agents in hiring/workforce</div>
      <p class="research-desc">I explore whether we can steer conversational agents to evaluate relational skills that are hard to discover from text-based applications in hiring and workforce contexts. I focus on capturing signals in simulated dialogue situations that require relational skills, and identifying which signals are most predictive of later performance.</p>
      <p class="research-meta">
        <span class="meta-label">support</span>
        <a href="https://www.laude.org/moonshots" target="_blank">Laude Institute Moonshots</a>
      </p>
    </div>
  </div>

</div>

<style>
.research-list {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  margin-top: 1rem;
  margin-bottom: 2.5rem;
}
.research-item {
  display: flex;
  gap: 1.25rem;
  align-items: flex-start;
}
.research-thumb {
  flex: 0 0 140px;
  width: 140px;
  height: 140px;
  background-color: #f3f3f3;
  color: #c4c4c4;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.2rem;
  font-weight: 300;
  letter-spacing: 0.05em;
  border-radius: 3px;
  overflow: hidden;
}
.research-thumb img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  display: block;
}
[data-theme="dark"] .research-thumb {
  background-color: #2a2a2a;
  color: #555;
}
.research-body { flex: 1; min-width: 0; }
.research-title {
  font-size: 1.05rem;
  font-weight: 600;
  margin-bottom: 0.4rem;
  line-height: 1.3;
}
.research-desc {
  font-size: 0.95rem;
  margin-bottom: 0.5rem;
  line-height: 1.5;
}
.research-meta {
  font-size: 0.85rem;
  color: #6c757d;
  margin-bottom: 0.2rem;
  line-height: 1.5;
}
.research-meta .meta-label {
  display: inline-block;
  min-width: 3.5rem;
  font-variant: small-caps;
  letter-spacing: 0.04em;
  color: #999;
  margin-right: 0.4rem;
}
.research-meta a {
  color: var(--global-theme-color);
  text-decoration: none;
}
.research-meta a:hover { text-decoration: underline; }
@media (max-width: 576px) {
  .research-item { flex-direction: column; }
  .research-thumb { width: 100%; height: 100px; }
}
</style>

Prior to Cornell, I spent several years as a data scientist at Korea University to develop course and major recommender systems to support college students' decision making process.

I have a love-hate relationship with tennis — you'll often find me attempting to upgrade my skills from the ‘absolute beginner’ category. I also love listening to music and curating songs! 