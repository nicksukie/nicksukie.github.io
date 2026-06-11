---
layout: default
---
<div class="page-content">
    <div class=" text-body paragraph-text-home mx-auto mb2">
<div class="who-am-i">
  <img src="/assets/images/pp.jpeg" alt="Nick Sukiennik" class="profile-photo">
  <div class="who-am-i-text">
    <h2>About Me</h2>
    <br>
    <p>
    I'm Nick. I'm currently a PhD candidate at Tsinghua University. I do research on recommender systems and their social impacts. I have also, along with virtually the entire academic community, begun delving into the capabilities of large language models.
    <br>
    <br>
    I'm interested in the intersection between technology and society, namely, how the platforms/LLMs we use influence the information we are exposed to, and, in turn, how that information informs our views.
    <br>
    <br>
    My research is multi-disciplinary and transcends computer science, electronic engineering, as well as social science/sociology, linguistics, and to some extent, philosophy.
    </p>
  </div>
</div>

<!--Having taken an unconventional career path, my experiences living and travel abroad for ~10 years will serve (whether I like it or not) as the mental context and foundational inspiration for all of my work, technical or otherwise. I have spent quite some time trying to reconcile all the aspects of my life, only to realize that doing so is impossible, at least at this point in my state of <a href="/">consciousness</a>. As such, I will here be focusing primarily on technology and academia, and whatever tangential topics happen to be related to my academic journey. What I hope to achieve here is, well... nothing. I just want an outlet to express myself. And if, in the process, I am able to offer tips, guidance, inspiration, tools and/or resources to help others succeed in academia, that would be nice too.-->

<!--div style="font-style: italic;">
Tl;dr - I'll be using this site as a platform to share my research journey, but in a "meta" (not -verse) sense, i.e. all the aspects that go into a research career, minus the actual research, which will (ideally) be published self-evidently. </div-->
<br>
<br>
<h2> My Recent Works</h2>

<ul class="publications-list">
  <li class="publication">
    <span class="publication-text">
      <em>Personalized Graph Sampling for Diverse Short Video Recommendation</em> (2026), <strong>N Sukiennik</strong>, C Gao, Y Zheng, Q Luo, P Chen, Y Li,
      ACM Transactions on the Web (Accepted).
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">Efforts to improve diversity in recommendations typically come at a cost of accuracy. While several works have proposed methods to overcome this trade-off, they neglect the unique challenges of short-video platforms: extreme long-tail distributions and hierarchical category structures with multiple granularity levels. Meanwhile, graph neural networks have become the state-of-the-art for recommendation because of their ability to achieve collaborative filtering and learn higher-order relationships between users and items. We therefore aim to unlock the capabilities of GNNs for personalization to adapt diversity to individual user preferences and overcome the accuracy-diversity dilemma in short-video recommendation. In this work, we identify two dimensions of diversity preferences—validated by psychological theory and readily inferable from interaction data and modeled using graph neighbor sampling—: user preferences for diverse content across category levels, and preferences for fine-grained diversity within broad-level interests. We integrate these dimensions directly into the graph propagation process through neighbor sampling, enabling the model to dynamically balance exploration of diverse categories with exploitation of user preferences during training. We also employ a curriculum training strategy that schedules exposure to items based on popularity-based hardness to determine how this scheduling improves the latent representations of long-tail items and mitigates the accuracy-diversity trade-off. Through extensive experiments against both standard graph and state-of-the-art graph-based diversified recommendation baselines, we show that our solution achieves superior balance between diversity and accuracy on datasets with extreme long-tail distributions while outperforming state-of-the-art methods at deeper levels of the category hierarchy.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>The Institutional Gap in LLM Social Simulation: A Study of International Trade Policy Deliberation</em> (2026), <strong>N Sukiennik</strong>, T Sim, Yichuan Xu, X Gao, C Gao, Y Li,
      EMNLP (Under Review).
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">LLM-based social simulators can generate plausible policy responses, but they rarely reveal how institutions deliberate, coordinate, and adapt under pressure. We introduce ProcessSociety, a framework for autonomous institutional decision-making process discovery: it structures policy shocks, role-specific agents, communication channels, questionnaires, and event traces so researchers can study decision processes rather than only final outcomes. We instantiate the framework in an international trade-policy simulation of the 2025 US tariff escalation, modeling citizens and government stakeholders across multiple institutional roles and countries. The simulation shows that stakeholders produce coherent, role-sensitive policy reasoning and adapt their stances as pressure escalates; 92.4% of government stakeholders change stance by mid-simulation. ProcessSociety also makes the boundary between elicited reasoning and autonomous institutional action directly observable: in this setting, stakeholders generate rich prompted deliberation, while autonomous inter-agent messaging and spontaneous trade events remain absent. We interpret this as a central diagnostic finding: ProcessSociety exposes where current LLM-agent architectures already support institutional reasoning, and where additional mechanisms are needed to support self-initiated coordination. The framework therefore provides a process-discovery tool and empirical baseline for building more autonomous institutional simulations.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>The Retrieval-Distribution Gap: Diagnosing Factual Inconsistency in Deployed LLMs</em> (2026), <strong>N Sukiennik</strong>, C Gao, Y Li,
      EMNLP (Under Review).
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">Large language models (LLMs) are increasingly deployed in production for factual question-answering across finance, healthcare, logistics, and global intelligence. Standard evaluation practices measure isolated accuracy on individual questions, but we show this is dangerously misleading: an LLM that correctly retrieves a numeric fact still fails to contextualize it correctly 22--43\% of the time---classifying a country at the 45th percentile as ``high'' or placing it in the ``top third'' when it belongs in the middle. We formalize this as the \textbf{retrieval-distribution gap} and introduce the \textbf{Tripartite Consistency Score (TCS)}, a diagnostic metric that any deploying team can compute to detect cross-modal factual inconsistency. Evaluating 12 LLMs across 3 API providers on 845 fact triplets spanning 5 industry-relevant knowledge verticals, we find that the best model achieves TCS=0.254, and the conditional probability of correct contextualization given correct numeric recall averages only 0.70. Explicit reasoning prompts improve numeric recall but \emph{increase} the dissonance rate in five of six tested models---by up to 94\%---while decreasing TCS for four of six and costing 3--5$\times$ more in inference tokens. We provide three lightweight detection strategies that practitioners can implement without ground truth data to monitor for tripartite dissonance in production systems.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>LLM Agents as Simulated Users: A Platform for Studying Recommender Dynamics in Short-Video Environment</em> (2026), <strong>N Sukiennik</strong>, H Wang, C Gao, Y Li,
      ACM Transactions on Information Systems (Under Review).
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">Short-video platforms are shaped by interactions among personalized recommendation, user feedback, and creator behavior, yet these dynamics are difficult to study through live experimentation alone. We present SimTok, an LLM-agent simulation platform for studying recommender dynamics in short-video environments. The framework couples LLM-based user agents with a recommendation module in a closed loop, enabling controlled analysis of recommendation accuracy, diversity, fairness, and emergent behavioral trends. We examine whether simulated recommendations predict real-world interactions, benchmarking against naive baselines and ablations. We study two datasets with different temporal characteristics to assess simulation fidelity. Beyond predictive performance, we investigate user-level diversity and fairness across demographic groups, item-level popularity bias, and other phenomena driven by the recommender-user-agent loop. We further ask whether LLM-simulated users reproduce real-world recommendation biases or introduce new distortions through their interaction with ranking policy. Our findings show that LLM agents reproduce several important short-video platform behaviors while also surfacing new trends, including stronger preference for agent-generated content over organic content and attention overconcentration in some settings. We also develop a user interface for launching experiments and monitoring results. Overall, SimTok provides a practical tool for controlled recommender-system analysis, bias diagnosis, and hypothesis generation in short-video settings</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>Uncovering the Deep Filter Bubble: Narrow Exposure in Short-Video Recommendation</em> (2024), <strong>N Sukiennik</strong>, C Gao, N Li,
      Proceedings of the ACM Web Conference 2024 (WWW24).
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">Filter bubbles have been studied extensively within the context of online content platforms due to their potential to cause undesirable outcomes such as user dissatisfaction or polarization. With the rise of short-video platforms, the filter bubble has been given extra attention because these platforms rely on an unprecedented use of the recommender system to provide relevant content. In our work, we investigate the deep filter bubble, which refers to the user being exposed to narrow content within their broad interests. We accomplish this using one-year interaction data from a top short-video platform in China, which includes hierarchical data with three levels of categories for each video. We formalize our definition of a "deep" filter bubble within this context, and then explore various correlations within the data: first understanding the evolution of the deep filter bubble over time, and later revealing some of the factors that give rise to this phenomenon, such as specific categories, user demographics, and feedback type. We observe that while the overall proportion of users in a filter bubble remains largely constant over time, the depth composition of their filter bubble changes. In addition, we find that some demographic groups have a higher likelihood of seeing narrower content, and that implicit feedback signals can lead to less bubble formation. Finally, we propose some ways in which recommender systems can be designed to reduce the risk of a user getting caught in a bubble.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>Can't Stop Scrolling: Understanding the Online Behavioral Factors and Trends of Short-Video Addiction</em> (2025), JY Wang, <strong>N Sukiennik</strong>, J Piao, Z Pan, C Gao, Y Li,
      Proceedings of the International AAAI Conference on Web and Social Media.
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">The pervasive use of short-video applications has raised concerns about their potential negative effects on users, particularly addiction. Existing research often relies on psychological questionnaires, which lack real-world behavioral data, limiting scalability and analytical depth. To address this, we assess the addiction status of short-video platform users using a standardized psychometric questionnaire, combined with platform behavioral data and interview responses to uncover features associated with addiction. Using feature-based modeling, we scale to a dataset of 10,111 addiction-labeled users and identify key indicators of addiction, including prolonged daily watch time, especially at night, and excessive video consumption, while also revealing that higher watch frequency is not fully correlated with addiction. Additionally, we find that addicted users tend to consume a narrower range of content, suggesting a filter bubble effect. Our large-scale analysis provides valuable insights for platform designers, policymakers, and mental health professionals seeking to promote healthier engagement and mitigate the risks of short-video addiction.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>Debiasing International Attitudes: LLM Agents for Simulating US-China Perception Changes</em> (2025), <strong>N Sukiennik</strong>, Yichuan Xu, Yuqing Kan, Jinghua Piao, Yuwei Yan, Chen Gao, Yong Li,
      preprint.
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">Large Language Models (LLMs) offer transformative opportunities to address the longstanding challenge of modeling opinion evolution in computational social science. This study investigates how media influences cross-border attitudes—a key driver of global polarization—by developing an LLM-agent framework to disentangle sources of bias and assess LLMs' capacity for human-like opinion formation in response to external information. We introduce an LLM-agent-based framework that models U.S. citizens' attitudes toward China from 2005 to 2025. Our approach integrates large-scale news data with social media profiles to initialize agent populations, which then undergo cognitive-aware reflection and opinion updating. We propose three debiasing mechanisms: (1) fact elicitation, extracting neutral events from subjectively framed news; (2) a devil's advocate agent that simulates critical contextualization; and (3) counterfactual exposure to surface inherent model biases. Simulations with two state-of-the-art LLMs (Qwen3-14b and GPT4o) reveal the expected negative attitudinal trend following media exposure. While all three mechanisms mitigate this trend to varying degrees, results indicate that subjective news framing contributes only modestly to negative attitudes, whereas the devil's advocate agent proves most effective overall, suggesting that intermediate analytical steps can produce more human-like agent opinions. Notably, the counterfactual study reveals contradictory findings across models, suggesting region-specific inherent biases tied to models' geographic origins. By advancing understanding of LLM-based opinion formation and debiasing methods, this study contributes to developing more objective models that better align with human cognitive tendencies.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>Simulating Filter Bubble on Short-video Recommender System with Large Language Model Agents</em> (2025), <strong>N Sukiennik</strong>, H Wang, Z Zeng, C Gao, Y Li,
      arXiv preprint.
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">An increasing reliance on recommender systems has led to concerns about the creation of filter bubbles on social media, especially on short video platforms like TikTok. However, their formation is still not entirely understood due to the complex dynamics between recommendation algorithms and user feedback. In this paper, we aim to shed light on these dynamics using a large language model-based simulation framework. Our work employs real-world short-video data containing rich video content information and detailed user-agents to realistically simulate the recommendation-feedback cycle. Through large-scale simulations, we demonstrate that LLMs can replicate real-world user-recommender interactions, uncovering key mechanisms driving filter bubble formation. We identify critical factors, such as demographic features and category attraction that exacerbate content homogenization. To mitigate this, we design and test interventions including various cold-start and feedback weighting strategies, showing measurable reductions in filter bubble effects. Our framework enables rapid prototyping of recommendation strategies, offering actionable solutions to enhance content diversity in real-world systems. Furthermore, we analyze how LLM-inherent biases may propagate through recommendations, proposing safeguards to promote equity for vulnerable groups, such as women and low-income populations. By examining the interplay between recommendation and LLM agents, this work advances a deeper understanding of algorithmic bias and provides practical tools to promote inclusive digital spaces.</span>
    </button>
  </li>
  <li class="publication">
    <span class="publication-text">
      <em>A Survey on LLMs from a Human-Centric Perspective</em> (2024), JY Wang, <strong>N Sukiennik</strong>, T Li, W Su, Q Hao, J Xu, Z Huang, F Xu, Y Li,
      arXiv preprint.
    </span>
    <button type="button" class="abstract-info" aria-label="Show abstract" aria-expanded="false">
      <span class="abstract-info-icon" aria-hidden="true">i</span>
      <span class="abstract-tooltip" role="tooltip">The rapid evolution of large language models (LLMs) and their capacity to simulate human cognition and behavior has given rise to LLM-based frameworks and tools that are evaluated and applied based on their ability to perform tasks traditionally performed by humans, namely those involving cognition, decision-making, and social interaction. This survey provides a comprehensive examination of such LLM applications in human-centered contexts, focusing on their performance in both individual tasks, where an LLM acts as a stand-in for a single human, and collective tasks, where multiple LLMs coordinate to mimic group dynamics. We first assess core competencies across perception, analysis, integration, execution, and social capabilities, each reflecting a distinct dimension of human-like skill. Then, we explore real-world applications of LLMs in human-centric domains such as behavioral science, political science, and sociology, assessing their effectiveness in replicating human behaviors and interactions. Finally, we identify challenges and future research directions, such as improving LLM adaptability, emotional intelligence, and cultural sensitivity, while addressing inherent biases and enhancing frameworks for human-AI collaboration. This survey aims to provide a foundational understanding of LLMs from a human-centric perspective, offering insights into their current capabilities and potential for future development.</span>
    </button>
  </li>
</ul>

<p>My master's thesis can be read <a href="https://repository.hkust.edu.hk/ir/Record/1783.1-107312">here</a>. The remnants of my master's thesis project can be found <a href="https://nicksukie.github.io/inflo/">here</a>.</p>

<h1>Side Projects</h1>

<h2><a href="https://github.com/nicksukie/BiliOCR">BILIOCR</a></h2>
<p>A real-time subtitle translation tool for mac using OCR, compatible with most popular LLM APIs (BYOkey).</p>

<h2><a href="https://www.globalthinkingcourse.com">Global Thinking Course</a></h2>
<p>An online course meant to impart the learnings I have obtained through my experiences living in various places around the world.</p>




<!--div class="content-list">

<p >
<ul>
<li>
Prior to starting my PhD, I attempted to summarize the learnings of my decade of travel and life (mostly) in Asia put into the context of the post-pandemic world, via an online course: <a href="https://www.globalthinkingcourse.com">Global Thinking in the 21st Century</a>. Along with this, I created a life/mindset coaching business where I would train students in the mindset set forth in my course: <a href="https://www.nicksnomadlife.com/">Global Thinking Nick</a>. This initiative also included a language learning component my own systemized immersion methods meant to propel one to fluency in <a href="https://nicksnomadlife.com/you-dont-need-to-be-in-china-to-learn-chinese/" >Mandarin Chinese</a>. </li>
<br>
<li>
During the pandemic, after my master's and prior to starting my PhD, I started <a href="https://www.nickstravelworld.com">travel blogging</a>, to make use of the time in which I and millions of others were (and perhaps, still are...?) unemployable due to a crippled economy, and in my case, the added perk of being a "fresh grad". Along with this, I started a <a href="/reflection-project">Reflection Project</a> involving photography and reflective/philosophical writing pieces (some of which later became inspiration for the content found in my course, linked above)</li>
<br>
<li>
I have also done a bit of volunteer and freelance work for a handful of startup and farms, the outcomes of which shall remain with me, and not to be used as CV fodder.</li>
<br>
<li>During my masters, from September 2017 to December 2019, I worked on a startup-slash-research project attempting to solve the problem of low-quality news and misinformation on social media. The remnants of that project can be found <a href="inflo">here</a>.</li>
<br>
<li>
 The purpose of this blog is to express myself in a non-technical context, as a hobby, whereas my _actual_ career will highly niche and technical.</li>


</p>
<br>
 I'm also passionate about learning languages and photography.
</div-->
</div>
</div>

{%- include pub-abstracts-script.html -%}
