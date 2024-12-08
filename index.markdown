---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="(M)LLM-based OS Agents for General Computing Devices Control: A Survey">
  <meta name="keywords" content="InfiCoder-Eval, code-generation, large-language-model, benchmark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>(M)LLM-based OS Agents for General Computing Devices Control: A Survey</title>

  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">

  <link rel="stylesheet" href="./static/css/bulma.min.css">
  <link rel="stylesheet" href="./static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./static/css/fontawesome.all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./static/css/index.css">

  <link rel="stylesheet" href="./bower_components/bootstrap/dist/css/bootstrap.table.min.css">
  <!--  <link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.min.css">-->
  <link rel="stylesheet" href="./stylesheets/layout.css">
  <link rel="stylesheet" href="./stylesheets/index.css">

  <!-- for print the table -->
  <script type="text/javascript" charset="utf8" src="https://code.jquery.com/jquery-3.6.0.slim.min.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/jquery.dataTables.css">
  <script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/dataTables.bootstrap5.min.css">
  <script src="https://cdn.datatables.net/1.11.3/js/dataTables.bootstrap5.min.js"></script>

  <link rel="icon" href="./static/images/survey_title_log.jpeg">

  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>
</head>

<body>

  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div class="navbar-menu">
      <div class="navbar-start" style="flex-grow: 1; justify-content: center;">
        <a class="navbar-item" href="https://github.com/infi-coder">
          <span class="icon">
            <i class="fas fa-home"></i>
          </span>
        </a>

	<!-- 修改团队主页 -->
 
        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>
          <div class="navbar-dropdown">
            <a class="navbar-item" href="https://github.com/infi-coder">
              OS Agents Survey Team
            </a>
          </div>
        </div>
      </div>
    
    </div>
  </nav>

  <div class="container">
    <div class="column has-text-centered">
      <img style="max-width: 200px; margin-bottom: -50px;" src="static/images/survey_title_log.jpeg">
    </div>
  </div>

  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title">(M)LLM-based OS Agents for General Computing Devices Control: A Survey
            </h1>
            <div class="is-size-5 publication-authors">
              <span class="author-block">
                OS Agents Survey Team
              </span>
              <br>
              <!-- <span class="author-block">
                Main Maintainer: <a href="mailto:xxxxx">xxxxx</a>
              </span> -->
              <!-- <span class="author-block">
                <a href="https://xxx.github.io/">xxxxxx</a><sup>1</sup></span>
			        <br/> -->
            </div>

            <div class="is-size-5 publication-authors">
              <!-- <span class="author-block"><sup>1</sup>Caption of Quận 5, Ho Chi Minh City, Vietnam</span> -->
              <!-- <span class="author-block"><sup>2</sup>Peking University,</span> -->
            </div>
    
            <div class="column has-text-centered">
              <div class="publication-links">
                <!-- PDF Link. -->
                <span class="link-block">
                  <a href="https://arxiv.org/abs/2404.07940"
                    class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="ai ai-arxiv"></i>
                    </span>
                    <span>Report</span>
                  </a>
                </span>
                <!-- Dataset Link. -->
                <span class="link-block">
                  <a href="https://github.com/YuanDaoze/OS-Agent-Survey-test"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Code</span>
                  </a>
                  <!-- <a href="https://github.com/infi-coder/inficoder-eval-framework"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Evaluation Repo</span>
                  </a> -->
                </span>
                <!-- Twitter Link. -->
                <!-- <span class="link-block">
                  <a href="https://twitter.com/taoyds/status/1595086401309388801"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                      <i class="fab fa-twitter"></i>
                    </span>
                    <span>Twitter</span>
                  </a>
                </span> -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="hero teaser">
    <div class="container is-max-desktop">
      <div class="hero-body">
        <h2 class="subtitle">
          This is the website for <a href="xxxxx" target="_blank">(M)LLM-based OS Agents for General Computing Devices Control: A Survey</a>. The survey consolidates the state of OS Agents research, providing insights to guide both academic inquiry and industrial development. In this repository, we have listed relevant papers related to our work in four areas: Foundation Models, Agent Frameworks, Evaluation & Benchmark, and Safety & Privacy and this collection will be continuously updated. You can easily access comprehensive knowledge on the OS Agent field and quickly familiarize yourself with this research direction.
        </h2>
<!--         <img src="static/images/inficoder-eval-main.png"> -->
      </div>
    </div>
  </section>

<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3" id='table-of-contents'>Table of Contents</h2>
        <div class="content has-text-justified">
          <ul>
              <li><p><a href='#overview-of-survey' style="font-size: 1.5rem;" >Overview of Survey</a></p>
              </li>
              <li><p><a href='#papers' style="font-size: 1.5rem;" >Papers</a></p>
                  <ul>
                      <li><a href='#foundation-models' style="font-size: 1.5rem;" >Foundation Models</a></li>
                      <li><a href='#agent-frameworks' style="font-size: 1.5rem;" >Agent Frameworks</a></li>
                      <li><a href='#evaluation--benchmark' style="font-size: 1.5rem;" >Evaluation &amp; Benchmark</a></li>
                      <li><a href='#safety--privacy' style="font-size: 1.5rem;" >Safety &amp; Privacy</a></li>
                  </ul>
              </li>
              <li><p><a href='#contact' style="font-size: 1.5rem;" >Contact</a></p>
              </li>
              <li><p><a href='#acknowledgement' style="font-size: 1.5rem;" >Acknowledgement</a></p>
              </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

  <section class="section">
    <div class="container is-max-desktop">
      <!-- Abstract. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='overview-of-xxx'>Overview of Survey</h2>
          <div class="content has-text-justified">
            <p>
 		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/teaser_os_agent_page.jpg">
		This survey aims to make contributions to the research and development of OS Agents by providing readers with a comprehensive understanding of their essential capabilities, offering insights into methodologies for building OS Agents based on (M)LLMs, and highlighting the latest research trends, challenges and future in this field. Recognizing that OS Agents are still in their early stages of development, we acknowledge the rapid advancements that continue to introduce novel methodologies and applications. Through this work, we aspire to inspire further innovation, driving progress in both academic research and industrial applications of OS Agents.
  
            </p>
          </div>
        </div>
      </div>
      <!--/ Abstract. -->
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3 id='papers'">Papers</h2>
          <div class="content has-text-justified">
            <h3 id='foundation-models'>Foundation Models</h3>
              <ol start='' >
              <li>[2024/10/31] AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents[<a href='https://arxiv.org/abs/2410.24024'>paper</a>]</li>
              <li>[2024/10/30] OS-ATLAS: A Foundation Action Model for Generalist GUI Agents[<a href='https://arxiv.org/abs/2410.23218'>paper</a>]</li>
              <li>[2024/10/28] AutoGLM: Autonomous Foundation Agents for GUIs[<a href='https://arxiv.org/abs/2411.00820'>paper</a>]</li>
              <li>[2024/10/25] EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data[<a href='https://arxiv.org/abs/2410.19461'>paper</a>]</li>
              <li>[2024/10/24] Ferret-UI One: Mastering Universal User Interface Understanding Across Platforms[<a href='https://arxiv.org/abs/2410.18967'>paper</a>]</li>
              <li>[2024/10/22] ShowUI: One Vision-Language-Action Model for Generalist GUI Agent[<a href='https://openreview.net/forum?id=UXdxYnkJtX'>paper</a>]</li>
              <li>[2024/10/17] Harnessing Webpage UIs for Text-Rich Visual Understanding[<a href='https://arxiv.org/abs/2410.13824'>paper</a>]</li>
              <li>[2024/10/09] TinyClick: Single-Turn Agent for Empowering GUI Automation[<a href='https://arxiv.org/abs/2410.11871'>paper</a>]</li>
              <li>[2024/10/07] Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents[<a href='https://arxiv.org/abs/2410.05243'>paper</a>]</li>
              <li>[2024/10/07] Navigating The Digital World As Humans Do: Universal Visual Grounding For Gui Agents[<a href='https://arxiv.org/abs/2410.05243'>paper</a>]</li>
              <li>[2024/10/03] NNetscape Navigator: Complex Demonstrations for Web Agents Without a Demonstrator[<a href='https://arxiv.org/abs/2410.02907'>paper</a>]</li>
              <li>[2024/09/30] MM1.5: Methods, Analysis &amp; Insights from Multimodal LLM Fine-tuning[<a href='https://arxiv.org/abs/2409.20566'>paper</a>]</li>
              <li>[2024/09/24] Synatra: Turning indirect knowledge into direct demonstrations for digital agents at scale[<a href='https://arxiv.org/abs/2409.15637'>paper</a>]</li>
              <li>[2024/09/23] MobileVLM: A Vision-Language Model for Better Intra- and Inter-UI Understanding[<a href='https://arxiv.org/abs/2409.14818'>paper</a>]</li>
              <li>[2024/09/22] MobileViews: A Large-Scale Mobile GUI Dataset[<a href='https://arxiv.org/abs/2409.14337'>paper</a>]</li>
              <li>[2024/08/30] UI-Hawk: Unleashing the screen stream understanding for gui agents[<a href='https://www.preprints.org/manuscript/202408.2137'>paper</a>]</li>
              <li>[2024/07/19] GUI Action Narrator: Where and When Did That Action Take Place?[<a href='https://arxiv.org/abs/2406.13719'>paper</a>]</li>
              <li>[2024/07/05] MobileFlow: A Multimodal LLM for Mobile GUI Agent[<a href='https://arxiv.org/abs/2407.04346'>paper</a>]</li>
              <li>[2024/06/20] VGA: Vision GUI Assistant - Minimizing Hallucinations through Image-Centric Fine-Tuning[<a href='https://arxiv.org/abs/2406.14056'>paper</a>]</li>
              <li>[2024/06/12] GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices[<a href='https://arxiv.org/abs/2406.08451'>paper</a>]</li>
              <li>[2024/06/12] Tell Me What&#39;s Next: Textual Foresight for Generic UI Representations[<a href='https://arxiv.org/abs/2406.07822'>paper</a>]</li>
              <li>[2024/05/29] ReALM: Reference Resolution As Language Modeling[<a href='https://arxiv.org/abs/2403.20329'>paper</a>]</li>
              <li>[2024/05/08] Visual Grounding for User Interfaces[<a href='https://aclanthology.org/2024.naacl-industry.9/'>paper</a>]</li>
              <li>[2024/05/05] Visual grounding for desktop graphical user interfaces[<a href='https://arxiv.org/abs/2407.01558'>paper</a>]</li>
              <li>[2024/05/05] Android in the Zoo：Chain-of-Action-Thought for GUI Agents[<a href='https://arxiv.org/abs/2403.02713'>paper</a>]</li>
              <li>[2024/05/01] Navigating WebAI: Training Agents to Complete Web Tasks with Large Language Models and Reinforcement Learning[<a href='https://arxiv.org/abs/2405.00516'>paper</a>]</li>
              <li>[2024/04/16] Search Beyond Queries: Training Smaller Language Models for Web Interactions via Reinforcement Learning[<a href='https://arxiv.org/abs/2404.10887'>paper</a>]</li>
              <li>[2024/04/12] Training a Vision Language Model as Smartphone Assistant[<a href='https://arxiv.org/abs/2404.08755'>paper</a>]</li>
              <li>[2024/04/09] Autonomous Evaluation and Refinement of Web Agents[<a href='https://arxiv.org/abs/2404.06474'>paper</a>]</li>
              <li>[2024/04/08] Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs[<a href='https://arxiv.org/abs/2404.05719'>paper</a>]</li>
              <li>[2024/04/04] AutoWebGLM: A Large Language Model-based Web Navigating Agent[<a href='https://arxiv.org/abs/2404.03648'>paper</a>]</li>
              <li>[2024/04/04] AutoWebGLM: A Large Language Model-based Web Navigating Agent[<a href='https://arxiv.org/abs/2404.03648'>paper</a>]</li>
              <li>[2024/04/02] Octopus v2: On-device language model for super agent[<a href='https://arxiv.org/abs/2404.01744'>paper</a>]</li>
              <li>[2024/03/30] Large Language Models Can Self-Improve At Web Agent Tasks[<a href='https://arxiv.org/abs/2405.20309v2'>paper</a>]</li>
              <li>[2024/02/08] WebLINX: Real-World website navigation with Multi-Turn dialogue[<a href='https://arxiv.org/abs/2402.05930'>paper</a>]</li>
              <li>[2024/02/07] ScreenAI: A Vision-Language Model for UI and Infographics Understanding[<a href='https://arxiv.org/abs/2402.04615'>paper</a>]</li>
              <li>[2024/02/06] Dual-View Visual Contextualization for Web Navigation[<a href='https://arxiv.org/abs/2402.04476'>paper</a>]</li>
              <li>[2024/01/20] E-ANT: A Large-Scale Dataset for Efficient Automatic GUI NavigaTion[<a href='https://arxiv.org/abs/2406.14250'>paper</a>]</li>
              <li>[2024/01/17] SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents[<a href='https://arxiv.org/abs/2401.10935'>paper</a>]</li>
              <li>[2024/01/17] GUICourse: From General Vision Language Models to Versatile GUI Agents[<a href='https://arxiv.org/abs/2406.11317'>paper</a>]</li>
              <li>[2023/12/25] WebVLN: Vision-and-Language Navigation on Websites[<a href='https://arxiv.org/abs/2312.15820'>paper</a>]</li>
              <li>[2023/12/25] UINav: A Practical Approach to Train On-Device Automation Agents[<a href='https://aclanthology.org/2024.naacl-industry.4/'>paper</a>]</li>
              <li>[2023/12/14] CogAgent: A Visual Language Model for GUI Agents[<a href='https://arxiv.org/abs/2312.08914'>paper</a>]</li>
              <li>[2023/12/04] Intelligent Virtual Assistants with LLM-based Process Automation[<a href='https://arxiv.org/abs/2312.06677'>paper</a>]</li>
              <li>[2023/11/30] Exposing Limitations of Language Model Agents in Sequential-Task Compositions on the Web[<a href='https://arxiv.org/abs/2311.18751'>paper</a>]</li>
              <li>[2023/10/27] Android in the wild: A large-scale dataset for android device control[<a href='https://arxiv.org/abs/2307.10088'>paper</a>]</li>
              <li>[2023/10/08] UReader: Universal OCR-free Visually-situated Language Understanding with Multimodal Large Language Model[<a href='https://arxiv.org/abs/2310.05126'>paper</a>]</li>
              <li>[2023/10/07] ILuvUI: Instruction-tuned Language-Vision modeling of UIs from Machine Conversations[<a href='https://arxiv.org/abs/2310.04869'>paper</a>]</li>
              <li>[2023/10/07] Reinforced UI Instruction Grounding: Towards a Generic UI Task Automation API[<a href='https://arxiv.org/abs/2310.04716'>paper</a>]</li>
              <li>[2023/07/24] A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis[<a href='https://arxiv.org/abs/2307.12856'>paper</a>]</li>
              <li>[2023/05/31] From pixels to UI actions: Learning to follow instructions via graphical user interfaces[<a href='https://arxiv.org/abs/2306.00245'>paper</a>]</li>
              <li>[2023/05/19] Multimodal Web Navigation with Instruction-Finetuned Foundation Models[<a href='https://arxiv.org/abs/2305.11854'>paper</a>]</li>
              <li>[2023/01/30] WebUI: A Dataset for Enhancing Visual UI Understanding with Web Semantics[<a href='https://arxiv.org/abs/2301.13280'>paper</a>]</li>
              <li>[2023/01/23] Lexi: Self-Supervised Learning of the UI Language[<a href='https://arxiv.org/abs/2301.10165'>paper</a>]</li>
              <li>[2022/10/06] Towards Better Semantic Understanding of Mobile Interfaces[<a href='https://arxiv.org/abs/2210.02663'>paper</a>]</li>
              <li>[2022/09/29] Spotlight: Mobile UI Understanding using Vision-Language Models with a Focus[<a href='https://arxiv.org/abs/2209.14927'>paper</a>]</li>
              <li>[2022/07/04] WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents[<a href='https://arxiv.org/abs/2207.01206'>paper</a>]</li>
              <li>[2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui[<a href='https://arxiv.org/abs/2205.11029'>paper</a>]</li>
              <li>[2022/02/16] A data-driven approach for learning to control computers[<a href='https://arxiv.org/abs/2202.08137'>paper</a>]</li>

              </ol>
            <h3 id='agent-frameworks'>Agent Frameworks</h3>
              <ol start='' >
              <li>[2024/11/10] Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents[<a href='https://arxiv.org/abs/2411.06559'>paper</a>]</li>
              <li>[2024/11/01] WebOlympus: An Open Platform for Web Agents on Live Websites[<a href='https://aclanthology.org/2024.emnlp-demo.20/'>paper</a>]</li>
              <li>[2024/10/29] Auto-Intent: Automated Intent Discovery and Self-Exploration for Large Language Model Web Agents[<a href='https://arxiv.org/abs/2410.22552'>paper</a>]</li>
              <li>[2024/10/25] OpenWebVoyager: Building Multimodal Web Agents via Iterative Real-World Exploration, Feedback and Optimization[<a href='https://arxiv.org/abs/2410.19609'>paper</a>]</li>
              <li>[2024/10/24] OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning[<a href='https://arxiv.org/abs/2410.18963'>paper</a>]</li>
              <li>[2024/10/24] AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant[<a href='https://arxiv.org/abs/2410.18603'>paper</a>]</li>
              <li>[2024/10/24] Infogent: An Agent-Based Framework for Web Information Aggregation[<a href='https://arxiv.org/abs/2410.19054'>paper</a>]</li>
              <li>[2024/10/22] Large Language Models Empowered Personalized Web Agents[<a href='https://arxiv.org/abs/2410.17236'>paper</a>]</li>
              <li>[2024/10/21] Beyond Browsing: API-Based Web Agents[<a href='https://arxiv.org/abs/2410.16464'>paper</a>]</li>
              <li>[2024/10/17] AgentOccam: A Simple Yet Strong Baseline for LLM-Based Web Agents[<a href='https://arxiv.org/abs/2410.13825'>paper</a>]</li>
              <li>[2024/10/17] MobA: A Two-Level Agent System for Efficient Mobile Task Automation[<a href='https://arxiv.org/abs/2410.13757'>paper</a>]</li>
              <li>[2024/10/11] VisionTasker: Mobile Task Automation Using Vision Based UI Understanding and LLM Task Planning[<a href='https://dl.acm.org/doi/abs/10.1145/3654777.3676386'>paper</a>]</li>
              <li>[2024/10/10] Agent S: An Open Agentic Framework that Uses Computers Like a Human[<a href='https://arxiv.org/abs/2410.08164'>paper</a>]</li>
              <li>[2024/10/09] ClickAgent: Enhancing UI Location Capabilities of Autonomous Agents[<a href='https://arxiv.org/abs/2410.11872'>paper</a>]</li>
              <li>[2024/10/01] Dynamic Planning for LLM-based Graphical User Interface Automation[<a href='https://arxiv.org/abs/2410.00467'>paper</a>]</li>
              <li>[2024/10/01] Multimodal Auto Validation For Self-Refinement in Web Agents[<a href='https://arxiv.org/abs/2410.00689'>paper</a>]</li>
              <li>[2024/09/25] Turn Every Application into an Agent: Towards Efficient Human-Agent-Computer Interaction with API-First LLM-Based Agents[<a href='https://arxiv.org/abs/2409.17140'>paper</a>]</li>
              <li>[2024/09/23] From Commands to Prompts: LLM-based Semantic File System for AIOS[<a href='https://arxiv.org/abs/2410.11843'>paper</a>]</li>
              <li>[2024/09/23] Steward: Natural Language Web Automation[<a href='https://arxiv.org/abs/2409.15441'>paper</a>]</li>
              <li>[2024/09/16] NaviQAte: Functionality-Guided Web Application Navigation[<a href='https://arxiv.org/abs/2409.10741'>paper</a>]</li>
              <li>[2024/09/14] PeriGuru: A Peripheral Robotic Mobile App Operation Assistant based on GUI Image Understanding and Prompting with LLM[<a href='https://arxiv.org/abs/2409.09354'>paper</a>]</li>
              <li>[2024/09/12] Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale[<a href='https://arxiv.org/abs/2409.08264'>paper</a>]</li>
              <li>[2024/09/11] Agent Workflow Memory[<a href='https://arxiv.org/abs/2409.07429'>paper</a>]</li>
              <li>[2024/08/28] Webpilot: A versatile and autonomous multi-agent system for web task execution with strategic exploration[<a href='https://arxiv.org/abs/2408.15978'>paper</a>]</li>
              <li>[2024/08/24] AutoWebGLM: A Large Language Model-based Web Navigating Agent[<a href='https://dl.acm.org/doi/abs/10.1145/3637528.3671620'>paper</a>]</li>
              <li>[2024/08/24] Intelligent Agents with LLM-based Process Automation[<a href='https://dl.acm.org/doi/abs/10.1145/3637528.3671646'>paper</a>]</li>
              <li>[2024/08/01] OpenWebAgent: An Open Toolkit to Enable Web Agents on Large Language Models[<a href='https://aclanthology.org/2024.acl-demos.8/'>paper</a>]</li>
              <li>[2024/08/01] Omniparser for pure vision based gui agent[<a href='https://arxiv.org/abs/2408.00203'>paper</a>]</li>
              <li>[2024/07/21] Towards LLMCI: Multimodal AI for LLM-Vision UI Operation[<a href='https://doi.org/10.21203/rs.3.rs-4653823/v1'>paper</a>]</li>
              <li>[2024/07/17] Agent-e: From autonomous web navigation to foundational design principles in agentic systems[<a href='https://arxiv.org/abs/2407.13032'>paper</a>]</li>
              <li>[2024/07/04] MobileExperts: A Dynamic Tool-Enabled Agent Team in Mobile Devices[<a href='https://arxiv.org/abs/2407.03913'>paper</a>]</li>
              <li>[2024/07/01] Tree Search for Language Model Agents[<a href='https://arxiv.org/abs/2407.01476'>paper</a>]</li>
              <li>[2024/06/27] Read anywhere pointed: Layout-aware gui screen reading with tree-of-lens grounding[<a href='https://arxiv.org/abs/2406.19263'>paper</a>]</li>
              <li>[2024/06/11] CAAP: Context-Aware Action Planning Prompting to Solve Computer Tasks with Front-End UI Only[<a href='https://arxiv.org/abs/2406.06947'>paper</a>]</li>
              <li>[2024/06/03] Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration[<a href='https://arxiv.org/abs/2406.01014'>paper</a>]</li>
              <li>[2024/05/23] AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents[<a href='https://arxiv.org/abs/2405.14573'>paper</a>]</li>
              <li>[2024/05/17] Latent State Estimation Helps UI Agents to Reason[<a href='https://arxiv.org/abs/2405.11120'>paper</a>]</li>
              <li>[2024/04/28] MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot[<a href='https://arxiv.org/abs/2404.18074'>paper</a>]</li>
              <li>[2024/04/09] Autonomous Evaluation and Refinement of Web Agents[<a href='https://arxiv.org/abs/2404.06474'>paper</a>]</li>
              <li>[2024/04/03] PromptRPA: Generating Robotic Process Automation on Smartphones from Textual Prompts[<a href='https://arxiv.org/abs/2404.02475'>paper</a>]</li>
              <li>[2024/03/25] AIOS: LLM Agent Operating System[<a href='https://arxiv.org/abs/2403.16971v3'>paper</a>]</li>
              <li>[2024/03/05] Android in the zoo: Chain-of-action-thought for gui agents[<a href='https://arxiv.org/abs/2403.02713'>paper</a>]</li>
              <li>[2024/03/05] Cradle: Empowering Foundation Agents Towards General Computer Control[<a href='https://arxiv.org/abs/2403.03186v3'>paper</a>]</li>
              <li>[2024/02/23] On the Multi-turn Instruction Following for Conversational Web Agents[<a href='https://arxiv.org/abs/2402.15057'>paper</a>]</li>
              <li>[2024/02/19] CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation[<a href='https://arxiv.org/abs/2402.11941'>paper</a>]</li>
              <li>[2024/02/12] OS-Copilot: Towards Generalist Computer Agents with Self-Improvement[<a href='https://arxiv.org/abs/2402.07456'>paper</a>]</li>
              <li>[2024/02/09] ScreenAgent: A Vision Language Model-driven Computer Control Agent[<a href='https://arxiv.org/abs/2402.07945'>paper</a>]</li>
              <li>[2024/02/08] Ufo: A ui-focused agent for windows os interaction[<a href='https://arxiv.org/abs/2402.07939'>paper</a>]</li>
              <li>[2024/02/06] Dual-View Visual Contextualization for Web Navigation[<a href='https://arxiv.org/abs/2402.04476'>paper</a>]</li>
              <li>[2024/01/29] Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception[<a href='https://arxiv.org/abs/2401.16158'>paper</a>]</li>
              <li>[2024/01/25] WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models[<a href='https://arxiv.org/abs/2401.13919'>paper</a>]</li>
              <li>[2024/01/17] Seeclick: Harnessing gui grounding for advanced visual gui agents[<a href='https://arxiv.org/abs/2401.10935'>paper</a>]</li>
              <li>[2024/01/04] MobileAgent: enhancing mobile control via human-machine interaction and SOP integration[<a href='https://arxiv.org/abs/2401.04124'>paper</a>]</li>
              <li>[2024/01/03] GPT-4V(ision) is a Generalist Web Agent, if Grounded[<a href='https://arxiv.org/abs/2401.01614'>paper</a>]</li>
              <li>[2023/12/21] AppAgent: Multimodal Agents as Smartphone Users[<a href='https://arxiv.org/abs/2312.13771'>paper</a>]</li>
              <li>[2023/12/20] Assistgui: Task-oriented desktop graphical user interface automation[<a href='https://arxiv.org/abs/2312.13108'>paper</a>]</li>
              <li>[2023/12/04] MobileGPT: Augmenting LLM with Human-like App Memory for Mobile Task Automation[<a href='https://arxiv.org/abs/2312.03003v3'>paper</a>]</li>
              <li>[2023/12/04] Intelligent Virtual Assistants with LLM-based Process Automation[<a href='https://arxiv.org/abs/2312.06677'>paper</a>]</li>
              <li>[2023/11/13] GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation[<a href='https://arxiv.org/abs/2311.07562'>paper</a>]</li>
              <li>[2023/10/24] WebWISE: Web Interface Control and Sequential Exploration with Large Language Models[<a href='https://arxiv.org/abs/2310.16042'>paper</a>]</li>
              <li>[2023/10/12] A Zero-Shot Language Agent for Computer Control with Structured Reflection[<a href='https://arxiv.org/abs/2310.08740'>paper</a>]</li>
              <li>[2023/09/20] You only look at screens: Multimodal chain-of-action agents[<a href='https://arxiv.org/abs/2309.11436'>paper</a>]</li>
              <li>[2023/09/15] Laser: Llm agent with state-space exploration for web navigation[<a href='https://arxiv.org/abs/2309.08172'>paper</a>]</li>
              <li>[2023/08/29] AutoDroid: LLM-powered Task Automation in Android[<a href='https://arxiv.org/abs/2308.15272'>paper</a>]</li>
              <li>[2023/07/24] A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis[<a href='https://arxiv.org/abs/2307.12856'>paper</a>]</li>
              <li>[2023/06/14] Synapse: Trajectory-as-Exemplar Prompting with Memory for Computer Control[<a href='https://arxiv.org/abs/2306.07863'>paper</a>]</li>
              <li>[2023/06/09] Mind2Web: Towards a Generalist Agent for the Web[<a href='https://arxiv.org/abs/2306.06070'>paper</a>]</li>
              <li>[2023/05/30] Sheetcopilot: Bringing software productivity to the next level through large language models[<a href='https://arxiv.org/abs/2305.19308'>paper</a>]</li>
              <li>[2023/05/23] Hierarchical prompting assists large language model on web navigation[<a href='https://arxiv.org/abs/2305.14257'>paper</a>]</li>
              <li>[2023/05/09] InternGPT: Solving Vision-Centric Tasks by Interacting with ChatGPT Beyond Language[<a href='https://arxiv.org/abs/2305.05662'>paper</a>]</li>
              <li>[2023/03/30] Language Models can Solve Computer Tasks[<a href='https://arxiv.org/abs/2303.17491'>paper</a>]</li>
              <li>[2022/09/19] Enabling conversational interaction with mobile ui using large language models[<a href='https://arxiv.org/abs/2209.08655'>paper</a>]</li>
              <li>[2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui[<a href='https://arxiv.org/abs/2205.11029'>paper</a>]</li>
    
              </ol>
            <h3 id='evaluation--benchmark'>Evaluation &amp; Benchmark</h3>
              <ol start='' >
              <li>[2024/10/31] AndroidLab: Training and Systematic Benchmarking of Android Autonomous Agents[<a href='https://arxiv.org/abs/2410.24024'>paper</a>]</li>
              <li>[2024/10/28] AssistEditor: Multi-Agent Collaboration for GUI Workflow Automation in Video Creation[<a href='https://dl.acm.org/doi/abs/10.1145/3664647.3684998'>paper</a>]</li>
              <li>[2024/10/28] Shopping MMLU: A Massive Multi-Task Online Shopping Benchmark for Large Language Models[<a href='https://arxiv.org/abs/2410.20745'>paper</a>]</li>
              <li>[2024/10/28] MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI[<a href='https://arxiv.org/abs/2404.16006'>paper</a>]</li>
              <li>[2024/10/24] VideoWebArena: Evaluating Long Context Multimodal Agents with Video Understanding Web Tasks[<a href='https://arxiv.org/abs/2410.19100'>paper</a>]</li>
              <li>[2024/10/22] Large Language Models Empowered Personalized Web Agents[<a href='https://arxiv.org/abs/2410.17236'>paper</a>]</li>
              <li>[2024/10/19] SPA-Bench: A Comprehensive Benchmark for SmartPhone Agent Evaluation[<a href='https://arxiv.org/abs/2410.15164'>paper</a>]</li>
              <li>[2024/10/17] MobA: A Two-Level Agent System for Efficient Mobile Task Automation[<a href='https://arxiv.org/abs/2410.13757'>paper</a>]</li>
              <li>[2024/10/07] Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents[<a href='https://arxiv.org/abs/2410.05243'>paper</a>]</li>
              <li>[2024/09/22] MobileViews: A Large-Scale Mobile GUI Dataset[<a href='https://arxiv.org/abs/2409.14337'>paper</a>]</li>
              <li>[2024/09/12] Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale[<a href='https://arxiv.org/abs/2409.08264'>paper</a>]</li>
              <li>[2024/09/06] WebQuest: A Benchmark for Multimodal QA on Web Page Sequences[<a href='https://arxiv.org/abs/2409.13711'>paper</a>]</li>
              <li>[2024/08/01] Omniparser for pure vision based gui agent[<a href='https://arxiv.org/abs/2408.00203'>paper</a>]</li>
              <li>[2024/07/26] OfficeBench: Benchmarking Language Agents across Multiple Applications for Office Automation[<a href='https://arxiv.org/abs/2407.19056'>paper</a>]</li>
              <li>[2024/07/22] AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?[<a href='https://arxiv.org/abs/2407.15711'>paper</a>]</li>
              <li>[2024/07/15] Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?[<a href='https://arxiv.org/abs/2407.10956'>paper</a>]</li>
              <li>[2024/07/13] RealWeb: A Benchmark for Universal Instruction Following in Realistic Web Services Navigation[<a href='https://ieeexplore.ieee.org/abstract/document/10707522'>paper</a>]</li>
              <li>[2024/07/11] UICrit: Enhancing Automated Design Evaluation with a UI Critique Dataset[<a href='https://arxiv.org/abs/2407.08850'>paper</a>]</li>
              <li>[2024/07/07] WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks[<a href='https://arxiv.org/abs/2407.05291'>paper</a>]</li>
              <li>[2024/07/04] MobileExperts: A Dynamic Tool-Enabled Agent Team in Mobile Devices[<a href='https://arxiv.org/abs/2407.03913'>paper</a>]</li>
              <li>[2024/07/03] Amex: Android multi-annotation expo dataset for mobile gui agents[<a href='https://arxiv.org/abs/2407.17490'>paper</a>]</li>
              <li>[2024/07/01] CRAB: Cross-environment Agent Benchmark for Multimodal Language Model Agents[<a href='https://arxiv.org/abs/2407.01511'>paper</a>]</li>
              <li>[2024/07/01] Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents[<a href='https://arxiv.org/abs/2407.00993'>paper</a>]</li>
              <li>[2024/06/27] Read Anywhere Pointed: Layout-aware GUI Screen Reading with Tree-of-Lens Grounding[<a href='https://arxiv.org/abs/2406.19263'>paper</a>]</li>
              <li>[2024/06/20] E-ANT: A Large-Scale Dataset for Efficient Automatic GUI NavigaTion[<a href='https://arxiv.org/abs/2406.14250'>paper</a>]</li>
              <li>[2024/06/20] Identifying User Goals from UI Trajectories[<a href='https://arxiv.org/abs/2406.14314'>paper</a>]</li>
              <li>[2024/06/19] GUI Action Narrator: Where and When Did That Action Take Place?[<a href='https://arxiv.org/abs/2406.13719'>paper</a>]</li>
              <li>[2024/06/18] WebCanvas: Benchmarking Web Agents in Online Environments[<a href='https://arxiv.org/abs/2406.12373'>paper</a>]</li>
              <li>[2024/06/17] GUICourse: From General Vision Language Models to Versatile GUI Agents[<a href='https://arxiv.org/abs/2406.11317'>paper</a>]</li>
              <li>[2024/06/14] VideoGUI: A Benchmark f om Instructional Videos[<a href='https://arxiv.org/abs/2406.10227'>paper</a>]</li>
              <li>[2024/06/12] GUI Odyssey: A Comprehensive Dataset for Cross-App GUI Navigation on Mobile Devices[<a href='https://arxiv.org/abs/2406.08451'>paper</a>]</li>
              <li>[2024/06/12] GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents[<a href='https://arxiv.org/abs/2406.10819'>paper</a>]</li>
              <li>[2024/06/12] MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents[<a href='https://arxiv.org/abs/2406.08184'>paper</a>]</li>
              <li>[2024/06/06] On the effects of data scale on computer control agents[<a href='https://arxiv.org/abs/2406.03679'>paper</a>]</li>
              <li>[2024/06/06] On the Effects of Data Scale on UI Control Agents[<a href='https://arxiv.org/abs/2406.03679'>paper</a>]</li>
              <li>[2024/06/05] WebOlympus: An Open Platform for Web Agents on Live Websites[<a href='https://aclanthology.org/2024.emnlp-demo.20/'>paper</a>]</li>
              <li>[2024/06/05] UGIF-DataSet: A New Dataset for Cross-lingual, Cross-modal Sequential actions on the UI[<a href='https://aclanthology.org/2024.findings-naacl.89/'>paper</a>]</li>
              <li>[2024/06/01] WebSuite: Systematically Evaluating Why Web Agents Fail[<a href='https://arxiv.org/abs/2406.01623'>paper</a>]</li>
              <li>[2024/05/23] AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents[<a href='https://arxiv.org/abs/2405.14573'>paper</a>]</li>
              <li>[2024/05/23] AGILE: A Novel Reinforcement Learning Framework of LLM Agents[<a href='https://arxiv.org/abs/2405.14751'>paper</a>]</li>
              <li>[2024/05/17] Latent state estimation helps ui agents to reason[<a href='https://arxiv.org/abs/2405.11120'>paper</a>]</li>
              <li>[2024/05/07] Mapping natural language instructions to mobile UI action sequences[<a href='https://arxiv.org/abs/2005.03776'>paper</a>]</li>
              <li>[2024/05/05] Visual grounding for desktop graphical user interfaces[<a href='https://arxiv.org/abs/2407.01558'>paper</a>]</li>
              <li>[2024/04/28] MMAC-Copilot: Multi-modal Agent Collaboration Operating System Copilot[<a href='https://arxiv.org/abs/2404.18074'>paper</a>]</li>
              <li>[2024/04/25] Benchmarking mobile device control agents across diverse configurations[<a href='https://arxiv.org/abs/2404.16660'>paper</a>]</li>
              <li>[2024/04/15] MMInA: Benchmarking multihop multimodal internet agents[<a href='https://arxiv.org/abs/2404.09992'>paper</a>]</li>
              <li>[2024/04/12] Llamatouch: A faithful and scalable testbed for mobile ui task automation[<a href='https://arxiv.org/abs/2404.16054'>paper</a>]</li>
              <li>[2024/04/11] OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments[<a href='https://arxiv.org/abs/2404.07972'>paper</a>]</li>
              <li>[2024/04/09] VisualWebBench: How Far Have Multimodal LLMs Evolved in Web Page Understanding and Grounding?[<a href='https://arxiv.org/abs/2404.05955'>paper</a>]</li>
              <li>[2024/04/09] GUIDE: Graphical User Interface Data for Execution[<a href='https://arxiv.org/abs/2404.16048'>paper</a>]</li>
              <li>[2024/04/08] Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs[<a href='https://arxiv.org/abs/2404.05719'>paper</a>]</li>
              <li>[2024/04/04] Autowebglm: Bootstrap and reinforce a large language model-based web navigating agent[<a href='https://arxiv.org/abs/2404.03648'>paper</a>]</li>
              <li>[2024/03/29] Evaluating language model agents on realistic autonomous tasks[<a href='https://arxiv.org/abs/2312.11671'>paper</a>]</li>
              <li>[2024/03/29] Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want[<a href='https://arxiv.org/abs/2403.20271'>paper</a>]</li>
              <li>[2024/03/26] AgentStudio: A Toolkit for Building General Virtual Agents[<a href='https://arxiv.org/abs/2403.17918'>paper</a>]</li>
              <li>[2024/03/18] Tur[k]ingBench: A Challenge Benchmark for Web Agents[<a href='https://arxiv.org/abs/2403.11905'>paper</a>]</li>
              <li>[2024/03/15] Computer User Interface Understanding. A New Dataset and a Learning Framework[<a href='https://arxiv.org/abs/2403.10170'>paper</a>]</li>
              <li>[2024/03/12] Workarena: How capable are web agents at solving common knowledge work tasks?[<a href='https://arxiv.org/abs/2403.07718'>paper</a>]</li>
              <li>[2024/03/06] PPTC-R benchmark: Towards Evaluating the Robustness of Large Language Models for PowerPoint Task Completion[<a href='https://arxiv.org/abs/2403.03788'>paper</a>]</li>
              <li>[2024/03/05] Android in the Zoo:Chain-of-Action-Thought for GUI Agents[<a href='https://arxiv.org/abs/2403.02713'>paper</a>]</li>
              <li>[2024/02/27] Omniact: A dataset and benchmark for enabling multimodal generalist autonomous agents for desktop and web[<a href='https://arxiv.org/abs/2402.17553'>paper</a>]</li>
              <li>[2024/02/23] On the Multi-turn Instruction Following for Conversational Web Agents[<a href='https://arxiv.org/abs/2402.15057'>paper</a>]</li>
              <li>[2024/02/09] Understanding the weakness of large language model agents within a complex android environment[<a href='https://arxiv.org/abs/2402.06596'>paper</a>]</li>
              <li>[2024/02/09] Understanding the weakness of large language model agents within a complex android environment[<a href='https://arxiv.org/abs/2402.06596'>paper</a>]</li>
              <li>[2024/02/08] WebLINX: Real-World website navigation with Multi-Turn dialogue[<a href='https://arxiv.org/abs/2402.05930'>paper</a>]</li>
              <li>[2024/01/29] Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception[<a href='https://arxiv.org/abs/2401.16158'>paper</a>]</li>
              <li>[2024/01/25] Webvoyager: Building an end-to-end web agent with large multimodal models[<a href='https://arxiv.org/abs/2401.13919'>paper</a>]</li>
              <li>[2024/01/25] GPTVoiceTasker: Advancing Multi-step Mobile Task Efficiency Through Dynamic Interface Exploration and Learning[<a href='https://arxiv.org/abs/2401.14268'>paper</a>]</li>
              <li>[2024/01/24] Visualwebarena: Evaluating multimodal agents on realistic visual web tasks[<a href='https://arxiv.org/abs/2401.13649'>paper</a>]</li>
              <li>[2024/01/24] Agentboard: An analytical evaluation board of multi-turn llm agents[<a href='https://arxiv.org/abs/2401.13178'>paper</a>]</li>
              <li>[2024/01/24] Agentboard: An analytical evaluation board of multiturn LLM agents[<a href='https://arxiv.org/abs/2401.13178'>paper</a>]</li>
              <li>[2024/01/17] Seeclick: Harnessing gui grounding for advanced visual gui agents[<a href='https://arxiv.org/abs/2401.10935'>paper</a>]</li>
              <li>[2023/12/26] AutoTask: Executing Arbitrary Voice Commands by Exploring and Learning from Mobile GUI[<a href='https://arxiv.org/abs/2312.16062'>paper</a>]</li>
              <li>[2023/12/25] WebVLN: Vision-and-Language Navigation on Websites[<a href='https://arxiv.org/abs/2312.15820'>paper</a>]</li>
              <li>[2023/12/20] ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation[<a href='https://arxiv.org/abs/2312.13108'>paper</a>]</li>
              <li>[2023/11/30] Exposing Limitations of Language Model Agents in Sequential-Task Compositions on the Web[<a href='https://arxiv.org/abs/2311.18751'>paper</a>]</li>
              <li>[2023/11/21] GAIA: a benchmark for general AI assistants[<a href='https://arxiv.org/abs/2311.12983'>paper</a>]</li>
              <li>[2023/11/13] GPT-4V in wonderland: Large multimodal models for Zero-Shot smartphone GUI navigation[<a href='https://arxiv.org/abs/2311.07562'>paper</a>]</li>
              <li>[2023/11/03] Pptc benchmark: Evaluating large language models for powerpoint task completion[<a href='https://arxiv.org/abs/2311.01767'>paper</a>]</li>
              <li>[2023/10/16] OpenAgents: An Open Platform for Language Agents in the Wild[<a href='https://arxiv.org/abs/2310.10634'>paper</a>]</li>
              <li>[2023/09/20] You Only Look at Screens:Multimodal Chain-of-Action Agents[<a href='https://arxiv.org/abs/2309.11436'>paper</a>]</li>
              <li>[2023/08/29] AutoDroid: LLM-powered Task Automation in Android[<a href='https://arxiv.org/abs/2308.15272'>paper</a>]</li>
              <li>[2023/08/07] Agentbench: Evaluating llms as agents[<a href='https://arxiv.org/abs/2308.03688'>paper</a>]</li>
              <li>[2023/07/25] Webarena: A realistic web environment for building autonomous agents[<a href='https://arxiv.org/abs/2307.13854'>paper</a>]</li>
              <li>[2023/07/19] Android in the wild: A large-scale dataset for android device control[<a href='https://arxiv.org/abs/2307.10088'>paper</a>]</li>
              <li>[2023/06/09] Mind2Web: Towards a Generalist Agent for the Web[<a href='https://arxiv.org/abs/2306.06070'>paper</a>]</li>
              <li>[2023/05/30] Sheetcopilot: Bringing software productivity to the next level through large language models[<a href='https://arxiv.org/abs/2305.19308'>paper</a>]</li>
              <li>[2023/05/25] On the tool manipulation capability of open-source large language models[<a href='https://arxiv.org/abs/2305.16504'>paper</a>]</li>
              <li>[2023/05/14] Mobile-env: A universal platform for training and evaluation of mobile interaction[<a href='https://arxiv.org/abs/2305.08144v1'>paper</a>]</li>
              <li>[2023/05/14] Mobile-env: Building qualified evaluation benchmarks for llm-gui interaction[<a href='https://arxiv.org/abs/2305.08144'>paper</a>]</li>
              <li>[2023/04/14] Droidbot-gpt: Gpt-powered ui automation for android[<a href='https://arxiv.org/abs/2304.07061'>paper</a>]</li>
              <li>[2023/04/10] OpenAGI: When LLM Meets Domain Experts[<a href='https://arxiv.org/abs/2304.04370'>paper</a>]</li>
              <li>[2023/03/13] Vision-Language models as success detectors[<a href='https://arxiv.org/abs/2303.07280'>paper</a>]</li>
              <li>[2022/11/14] Ugif: Ui grounded instruction following[<a href='https://arxiv.org/abs/2211.07615'>paper</a>]</li>
              <li>[2022/10/08] Understanding html with large language models[<a href='https://arxiv.org/abs/2210.03945'>paper</a>]</li>
              <li>[2022/09/29] MUG: Interactive Multimodal Grounding on User Interfaces[<a href='https://arxiv.org/abs/2209.15099'>paper</a>]</li>
              <li>[2022/09/16] ScreenQA: Large-Scale Question-Answer Pairs over Mobile App Screenshots[<a href='https://arxiv.org/abs/2209.08199'>paper</a>]</li>
              <li>[2022/07/04] Webshop: Towards scalable real-world web interaction with grounded language agents[<a href='https://arxiv.org/abs/2207.01206'>paper</a>]</li>
              <li>[2022/05/23] Meta-gui: Towards multi-modal conversational agents on mobile gui[<a href='https://arxiv.org/abs/2205.11029'>paper</a>]</li>
              <li>[2022/02/04] A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility[<a href='https://arxiv.org/abs/2202.02312'>paper</a>]</li>
              <li>[2021/04/17] Mobile app tasks with iterative feedback (motif): Addressing task feasibility in interactive visual environments[<a href='https://arxiv.org/abs/2104.08560'>paper</a>]</li>
              <li>[2021/01/23] Websrc: A dataset for web-based structural reading comprehension[<a href='https://arxiv.org/abs/2101.09465'>paper</a>]</li>
              <li>[2018/08/28] Mapping natural language commands to web elements[<a href='https://arxiv.org/abs/1808.09132'>paper</a>]</li>
              <li>[2017/11/06] Building natural language interfaces to web apis[<a href='https://dl.acm.org/doi/10.1145/3132847.3133009'>paper</a>]</li>
              <li>[2017/08/06] World of bits: An open-domain platform for web-based agents[<a href='https://dl.acm.org/doi/10.5555/3305890.3306005'>paper</a>]</li>
    
              </ol>
            <h3 id='safety--privacy'>Safety &amp; Privacy</h3>
              <ol start='' >
              <li>[2024/11/04] Attacking Vision-Language Computer Agents via Pop-ups[<a href='https://arxiv.org/abs/2411.02391'>paper</a>]</li>
              <li>[2024/10/23] MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control[<a href='https://arxiv.org/abs/2410.17520'>paper</a>]</li>
              <li>[2024/10/22] Advweb: Controllable black-box attacks on vlm-powered web agents[<a href='https://arxiv.org/abs/2410.17401'>paper</a>]</li>
              <li>[2024/10/11] Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents[<a href='https://arxiv.org/abs/2410.13886'>paper</a>]</li>
              <li>[2024/10/09] ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents[<a href='https://arxiv.org/abs/2410.06703'>paper</a>]</li>
              <li>[2024/09/17] Eia: Environmental injection attack on generalist web agents for privacy leakage[<a href='https://arxiv.org/abs/2409.11295'>paper</a>]</li>
              <li>[2024/08/05] Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions[<a href='https://arxiv.org/abs/2408.02544'>paper</a>]</li>
              <li>[2024/07/12] Security Matrix for Multimodal Agents on Mobile Devices: A Systematic and Proof of Concept Study[<a href='https://arxiv.org/abs/2407.09295'>paper</a>]</li>
              <li>[2024/06/18] Adversarial Attacks on Multimodal Agents[<a href='https://arxiv.org/abs/2406.12814'>paper</a>]</li>
              <li>[2024/02/26] WIPI: A New Web Threat for LLM-Driven Web Agents[<a href='https://arxiv.org/abs/2402.16965'>paper</a>]</li>
              <li>[2023/08/03] From Prompt Injections to SQL Injection Attacks: How Protected is Your LLM-Integrated Web Application?[<a href='https://arxiv.org/abs/2308.01990'>paper</a>]</li>
    
              </ol>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="section">
    <div class="container is-max-desktop">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='contact'>Contact</h2>
          <div class="content has-text-justified">
            <p>
              Please let us know if you find out a mistake or are interested in contributing by e-mail: <a href='mailto:huxueyu.zju@gmail.com' target='_blank' class='url'>huxueyu.zju@gmail.com</a>.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='acknowledgement'>Acknowledgement</h2>
          <p>

          </p>
        </div>
      </div>
    </div>
  </section>
  

  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <a class="icon-link" href="https://arxiv.org/abs/2404.07940">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/infi-coder" class="external-link" disabled>
          <i class="fab fa-github" style="color:white"></i>
        </a>
      </div>
      <div class="columns is-centered">
        <div class="column is-8">
          <div class="content">
            <p>
              This website is adapted from <a href="https://ds1000-code-gen.github.io/">ds1000-code-gen.github.io</a> and is licensed under a <a rel="license"
                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
                Commons Attribution-ShareAlike 4.0 International License</a>.
            </p>
            <p>
              This means you are free to borrow the <a href="https://github.com/infi-coder/infibench">source
                code</a> of this website,
              we just ask that you link back to this page in the footer.
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>

  <script>
    $(document).ready( function () {
      $('.mainTable').DataTable({ordering: true, order: [[4, 'desc']], columns: [{ "type": "num" },{ "type": "html" },{ "type": "num" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "html", "orderable": false }]});
    } );
  </script>

</body>

</html>
