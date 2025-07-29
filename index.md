---
layout:     page
title:
permalink:  /
---

<!-- SEO Meta Tags -->
<meta name="title" content="Gautham Vasan | Robotics & Artificial Intelligence & Reinforcement Learning" />
<meta name="description" content="Gautham Vasan's research in robot learning, reinforcement learning, and real-time AI. Publications, talks, and professional activities." />
<meta name="keywords" content="Gautham Vasan, robot learning, reinforcement learning, AI, publications, talks, research, University of Alberta, NIT Trichy, deep learning, deep RL" />
<meta name="author" content="Gautham Vasan" />
<meta property="og:title" content="Gautham Vasan | Robot Learning & Reinforcement Learning" />
<meta property="og:description" content="Research, publications, and talks by Gautham Vasan in robot learning and reinforcement learning." />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://gauthamvasan.github.io/" />
<meta property="og:image" content="https://gauthamvasan.github.io/img/Profile/icml25_headshot.jpg" />
---

<div id="intro">
    <div id="intro-text">
        <h1>Gautham Vasan</h1>
        <p align="justify">
            I'm a PhD candidate in Computing Science at the <a href="https://www.ualberta.ca/en/index.html" target="_blank">University of Alberta</a>, advised by <a href="https://armahmood.github.io/" target="_blank">Dr. Rupam Mahmood</a>.
            My research focuses on enabling robots to learn from experience in real time using reinforcement learning.
            <!-- I’ve worked on asynchronous and distributed learning systems, reward design, and streaming reinforcement learning methods suited for real-world applications. -->
            <br><br>
            Previously, I deployed deep reinforcement learning to a fleet of warehouse robots used by Gap at <a href="https://ocadointelligentautomation.com/systems/robotic-sort-putwall" target="_blank">Kindred AI</a>. I’ve also worked on robot learning during internships at <a href="https://www.sanctuary.ai/" target="_blank">Sanctuary AI</a> and the <a href="https://nr.informatik.uni-freiburg.de/" target="_blank">University of Freiburg</a>. During my M.Sc, I worked with <a href="https://pilarski.github.io/" target="_blank">Dr. Patrick Pilarski</a> to develop learning from demonstration techniques that amputees can use to teach their own prosthetic arms. Long before that, I studied Instrumentation and Control Engineering at <a href="https://nitt.edu/" target="_blank">NIT Trichy</a>, India.    
            <br><br>
            📢 <b>I will be on the job market starting January 2026.</b> Feel free to <a href="mailto:gauthamv.529@gmail.com" target="_blank">reach out</a> if you think I’d be a good fit for your research position! 
            <br><br> 
            <a href="Resume.pdf" target="_blank">CV</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://scholar.google.ca/citations?user=4qMs0zMAAAAJ&hl=en&oi=ao" target="_blank">Google Scholar</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://github.com/gauthamvasan" target="_blank">GitHub</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://www.linkedin.com/in/gauthamvasan/" target="_blank">LinkedIn</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://www.goodreads.com/user/show/29446357-gautham-vasan" target="_blank">Goodreads</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="mailto:gauthamv.529@gmail.com" target="_blank">Email</a>
        </p>
    </div>
    <div id="intro-image">
        <img src="/img/Profile/icml25_headshot.jpg">
    </div>
</div>

<div id="filters" class="button-group">
    <!-- <button class="button is-checked" data-filter=".research">Highlights</button> -->
    <button class="button" data-filter=".research">Research</button>
    <button class="button" data-filter=".publication">Publications</button>
    <button class="button" data-filter=".talk">Talks</button>
    <button class="button" data-filter=".service">Service</button>
</div>

<div class="grid">
<style>
  .talks-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2em;
    margin-bottom: 2em;
  }
  .talks-grid .talk {
    box-sizing: border-box;
    padding: 1em;
    border: 1px solid #eee;
    border-radius: 8px;
    background: #fafbfc;
    margin-bottom: 0;
  }
  @media (max-width: 1200px) {
    .talks-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }
  @media (max-width: 900px) {
    .talks-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
    <!-- Research -->
    <div class="list-item research-project research" data-category="research">
        <a href="https://www.youtube.com/watch?v=yr3JZ4ujiqA" class="research-thumbnail">
            <video controls poster="/img/AVG_poster.jpg">
                <source src="/img/AVG.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </a>
        <div class="research-description">
            <h3>Streaming Deep Reinforcement Learning</h3>
            <p>Streaming learning is about learning from a stream of experience: <br> 
            •  as soon as they arrive <br>
            •  using the most recent sample <br>
            •  without storing past experience in raw form.<br><br>
            Our algorithms: <a href="https://arxiv.org/abs/2411.15370" target="_blank">Action Value Gradient (AVG)</a> & <a href="https://arxiv.org/abs/2410.14606" target="_blank">Stream-X</a>
            </p>
        </div>
    </div>
    <div class="list-item research-project research" data-category="research">
        <a href="https://www.stateof.ai/2021" class="research-thumbnail">
            <video controls poster="/img/Sort_poster.jpg">
                <source src="/img/Sort.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </a>
        <div class="research-description">
            <h3> RLScan: Learning to Scan Apparel Barcodes</h3>
            <p>
            <!-- •  Deep reinforcement learning in production to scan barcodes on apparel. <br> -->
            An RL policy is trained end-to-end directly in production, learning from a fleet of robots across multiple production sites.<br><br>
            <a href="https://www.youtube.com/watch?v=MYU5aVxg-AU" target="_blank">Kindred SORT at Gap Inc</a>, <a href="https://www.stateof.ai/2021" target="_blank">State of AI Report (2021)</a>
            </p>
        </div>
    </div>
    <div class="list-item research-project research" data-category="research">
        <a href="https://arxiv.org/abs/2210.02317" class="research-thumbnail">
            <video controls poster="/img/Create-Reacher_poster.jpg">
                <source src="/img/Create-Reacher.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </a>
        <div class="research-description">
            <h3>Reward Design in Reinforcement Learning</h3>
            <p>
            Using -1 every timestep until termination as the reward can lead to superior learned behaviors. Here's the <a href="https://arxiv.org/abs/2407.00324" target="_blank">paper</a> that explains why. 
            </p>
        </div>
    </div>
    <div class="list-item research-project research" data-category="research">
        <a href="https://arxiv.org/abs/2210.02317" class="research-thumbnail">
            <video controls poster="/img/UR5-VisualReacher_poster.jpg">
                <source src="/img/UR5-VisualReacher.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </a>
        <div class="research-description">
            <h3>Computational Frameworks for Real-Time Robot Learning</h3>
            <p> Concurrent processing for low latency sensorimotor interaction and asynchronous learning implementations for reliable real-time reinforcement learning on physical systems:
            <a href="https://github.com/kindredresearch/SenseAct" target="_blank">SenseAct</a> &
            <a href="https://github.com/rlai-lab/relod" target="_blank">ReLoD</a>
            </p>
        </div>
    </div>
    <div class="list-item research-project research" data-category="research">
        <a href="https://arxiv.org/abs/2312.15339" class="research-thumbnail">
            <video controls poster="/img/LfD_trials_poster.jpg">
                <source src="/img/LfD_trials.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </a>
        <div class="research-description">
            <h3>Learning From Demonstration for Prosthetic Arms</h3>
            <p>
                Teaching a Powered Prosthetic Arm with an Intact Arm Using Reinforcement Learning. <br>
                <i> M.Sc Outstanding <a href="https://era.library.ualberta.ca/items/4f922d51-0679-41f5-b362-12dd224b3a79" target="_blank">Thesis</a> Award in Computing Science </i> <br>
            </p>
        </div>
    </div>
    <!-- -->
    <!-- Publications -->
    <!-- -->
    <div class="list-item publication" data-category="publication">
        <a href="https://openreview.net/forum?id=DX5GUwMFFb" class="thumbnail">
            <img src="/img/AVG_thumbnail.png" alt="AVG paper thumbnail" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/pdf/2411.15370">Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</a></h3>
            <p>
                <b>Gautham Vasan</b>, Mohamed Elsayed, Alireza Azimi, Jiamin He, Fahim Shahriar, Colin Bellinger, Martha White, A. Rupam Mahmood<br>
                <i>NeurIPS 2024</i><br>
                <a href="https://arxiv.org/pdf/2411.15370">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/gauthamvasan/avg">Code</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://colab.research.google.com/drive/1j4ONR062WQ_Fqs0yt07uBdm9zz7HGbte?usp=sharing">Colab</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/cwwuN6Hyew0">Video Demo</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.youtube.com/watch?v=mQc4ETehniI">Cohere4AI Talk</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2410.14606" class="thumbnail">
             <img src="/img/streaming-deep-rl.png">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2410.14606">Streaming Deep Reinforcement Learning Finally Works</a></h3>
            <p>
                Mohamed Elsayed, <b>Gautham Vasan</b>, A. Rupam Mahmood<br>
                <i>Pre-Print, NeurIPS FitML Workshop 2024</i><br>
                <a href="https://arxiv.org/abs/2410.14606">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/mohmdelsayed/streaming-drl">Code</a>
            </p>
        </div>
    </div>
     <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2407.00324" class="thumbnail">
             <img src="/img/franka_reacher.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2407.00324">Revisiting Sparse Rewards for Goal-Reaching Reinforcement Learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Yan Wang, Fahim Shahriar, James Bergstra, Martin Jagersand, A. Rupam Mahmood<br>
                <i>RLC 2024</i><br>
                <a href="https://arxiv.org/abs/2407.00324">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/a6zlVUuKzBc">Demo</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/gauthamvasan/rl_suite">Code</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://openreview.net/pdf?id=TgXIkK8WPQ" class="thumbnail">
             <img src="/img/RL_Chemist_Setup.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://openreview.net/pdf?id=TgXIkK8WPQ">Versatile and Generalizable Manipulation via Goal-Conditioned Reinforcement Learning with Grounded Object Detection</a></h3>
            <p>
                Huiyi Wang, Fahim Shahriar, Alireza Azimi, <b>Gautham Vasan</b>, A. Rupam Mahmood, Colin Bellinger<br>
                <i>CoRL MRM-D Workshop 2024</i><br>
                <a href="https://openreview.net/pdf?id=TgXIkK8WPQ">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf" class="thumbnail">
             <img src="/img/vector_charger_detector.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf">Autonomous Skill Acquisition for Robots Using Graduated Learning</a></h3>
            <p>
                <b>Gautham Vasan</b><br>
                <i>AAMAS Doctoral Consortium 2024</i><br>
                <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2312.15339" class="thumbnail">
             <img src="/img/madi_setup.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2312.15339">MaDi: Learning to Mask Distractions for Generalization in Visual Deep Reinforcement Learning</a></h3>
            <p>
                Bram Grooten, Tristan Tomilin, <b>Gautham Vasan</b>, Matthew E Taylor, A Rupam Mahmood, Meng Fang, Mykola Pechenizkiy, Decebal Constantin Mocanu<br>
                <i>AAMAS 2024</i><br>
                <a href="https://arxiv.org/abs/2312.15339">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/2oImF0h1k48">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://proceedings.mlr.press/v202/che23c.html" class="thumbnail">
             <img src="/img/discount_correction.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://proceedings.mlr.press/v202/che23c.html">Correcting Discount-Factor Mismatch in On-Policy Policy Gradient Methods</a></h3>
            <p>
                Fengdi Che, <b>Gautham Vasan</b>, A. Rupam Mahmood<br>
                <i>ICML 2023</i><br>
                <a href="https://proceedings.mlr.press/v202/che23c.html">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2210.02317" class="thumbnail">
             <img src="/img/relod.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2210.02317">Real-Time Reinforcement Learning for Vision-Based Robotics Utilizing Local and Remote Computers</a></h3>
            <p>
                Yan Wang*, <b>Gautham Vasan*</b>, A. Rupam Mahmood<br>
                <i>ICRA 2023</i><br>
                <a href="https://arxiv.org/abs/2210.02317">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/7iZKryi1xSY">Video</a>
            </p>
        </div>
    </div>  
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1903.11524" class="thumbnail">
            <img src="/img/ARP/ARP_Blog3.png" alt="ARP Blog3" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1903.11524">Autoregressive policies for continuous control deep reinforcement learning</a></h3>
            <p>
                Dmytro Korenkevych, A Rupam Mahmood, <b>Gautham Vasan</b>, James Bergstra<br>
                <i>IJCAI 2019</i><br>
                <a href="https://arxiv.org/abs/1903.11524">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/introducing-autoregressive-policies-for-temporally-coherent-exploration-in-continuous-control-reinforcement-learning">Post</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/NCpyXBNqNmw">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1809.07731" class="thumbnail">
            <img src="/img/SenseAct/ur-reacher-2-trpo.gif" alt="UR-Reacher-2" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1809.07731">Benchmarking reinforcement learning algorithms on real-world robots</a></h3>
            <p>
                A Rupam Mahmood, Dmytro Korenkevych, <b>Gautham Vasan</b>, William Ma, James Bergstra<br>
                <i>CoRL 2018</i><br>
                <a href="https://arxiv.org/abs/1809.07731">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/benchmarking-reinforcement-learning-algorithms-on-real-world-robots">Post</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/ovDfhvjpQd8">Video</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://www.kindred.ai/blog/introducing-a-framework-and-benchmark-tasks-for-reproducible-reinforcement-learning-research-on-real-robots">SenseAct</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf" class="thumbnail">
            <img src="/img/BioRob_2018/contextual_lfd_trial.jpg" alt="Contextual LfD Trial" />
        </a>
        <div class="project-description">
            <h3><a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf">Context-Aware Learning from Demonstration: Using Camera Data to Support the Synergistic Control of a Multi-Joint Prosthetic Arm</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>BioRob 2018</i><br>
                <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2018_BioRob_preprint.pdf">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://docs.google.com/presentation/d/1gKY5LgBuBRYCs3NW5iyfrGNq6xCAxeg3zoM00j9C_Sw/edit?usp=sharing">Poster</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf" class="thumbnail">
            <img src="/img/ICORR_2017/Lfd_amputee.png" alt="LfD Amputee" />
        </a>
        <div class="project-description">
            <h3><a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf">Learning from demonstration: Teaching a myoelectric prosthesis with an intact limb via reinforcement learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>ICORR 2017</i><br>
                Spotlight presentation at Rehabweek 2017.<br>
                <a href="https://sites.ualberta.ca/~pilarski/docs/papers/Vasan_2017_ICORR_preprint.pdf">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://drive.google.com/drive/folders/0B8-iXsaYqsxmUWJnTkpvMkplMXM?usp=sharing">Video & Metadata</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="#" class="thumbnail">
            <img src="/img/ICORR_2017/bentoarm.jpg" alt="Bento Arm" />
        </a>
        <div class="project-description">
            <h3><a href="#">Mirrored Bilateral Training of a Myoelectric Prosthesis with a non-amputated arm via Actor-Critic Reinforcement Learning</a></h3>
            <p>
                <b>Gautham Vasan</b>, Patrick M Pilarski<br>
                <i>RLDM 2017</i><br>
                Spotlight presentation (20min)<br>
                <a href="https://docs.google.com/presentation/d/1xd4nhI-4XbSqV0v_7MCv3qOl5pUkkaOPfkQobLNZlL0/edit?usp=sharing">Poster</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://docs.google.com/presentation/d/1H19Mm8-aJNWyDSRAB-bmE11M29-23pB_zIlH72iSkQA/edit?usp=sharing">Slides</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/pdf/1604.07097.pdf" class="thumbnail">
            <img src="/img/NeuroHex/hexboard.png" alt="NeuroHex Board" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/pdf/1604.07097.pdf">Neurohex: A Deep Q-Learning Hex Agent</a></h3>
            <p>
                Kenny Young, <b>Gautham Vasan</b>, Ryan Hayward<br>
                <i>Computer Games Workshop at IJCAI 2016</i><br>
                <a href="https://arxiv.org/pdf/1604.07097.pdf">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://ieeexplore.ieee.org/abstract/document/7414792" class="thumbnail">
            <img src="/img/ardrone.jpg" alt="Quadrotor" />
        </a>
        <div class="project-description">
            <h3><a href="https://ieeexplore.ieee.org/abstract/document/7414792">Autonomous Visual Tracking and Landing of a Quadrotor on a Moving Platform</a></h3>
            <p>
                Juhi Ajmera, PR Siddharthan, KM Ramaravind, <b>Gautham Vasan</b>, Naresh Balaji, V Sankaranarayanan<br>
                <i>IEEE ICIIP 2015</i><br>
                <a href="https://ieeexplore.ieee.org/abstract/document/7414792">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://drive.google.com/file/d/0B78EAxFuk2RLWUsyOWdTMTdYak0/view?usp=sharing">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/1412.0591" class="thumbnail">
            <img src="/img/TI/robot_1.png" alt="TI Robot 1" />
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/1412.0591">A Control Strategy for an Autonomous Robotic Vacuum Cleaner for Solar Panels</a></h3>
            <p>
                <b>Gautham Vasan</b>, G Aravind, TSB Gowtham Kumar, R Naresh Balaji, G Saravana Ilango<br>
                <i>IEEE Texas Instruments India Educators Conference 2014</i><br>
                Phase-I Winners and finalists (top 19 among 2000+ teams)<br>
                <a href="https://arxiv.org/abs/1412.0591">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/qiCRSVuftFQ">Video</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/B_-TnMiD76M">Presentation</a>
            </p>
        </div>
    </div>
    <!-- Talks -->
    <!-- -->
<div class="talks-grid">
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/mQc4ETehniI?si=xG6ZJeOiRRymrDiv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Two Issues of Autonomous Robot Learning</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/QO0mmHMJvRQ?si=KGif_tvrkIN06zo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>Reward (Mis-)Specification in Reinforcement Learning</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/yqeiXpbDoKg?si=NuWSQoWizPiLL8Ic&amp;start=517" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
      <div class="list-item talk" data-category="talk">
        <h3 style="margin-top:0;"><b>natChat: Neurotech in Artificial Intelligence (2023)</b></h3>
        <iframe width="100%" height="315" src="https://www.youtube.com/embed/kkJ8-k-_CPQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="margin-top:1em;"></iframe>
      </div>
    </div>
    <!-- -->
    <!-- Community Service -->
    <!-- -->
    <div class="list-item service" data-category="service">
        <h3>Community Service & Professional Activities</h3><br>
        <ul style="list-style-type: disc; margin-left: 1.5em;">
            <li style="margin-bottom: 0.75em;">Workflow Chair for AAAI 2026</li>
            <li style="margin-bottom: 0.75em;">Reviewing at IROS, NeurIPS, ICML, ICLR and RLC</li>
            <li style="margin-bottom: 0.75em;">Research volunteer with The Hospital for Sick Children (<a href="https://www.sickkids.ca/">SickKids</a>, 2019)</li>
            <li style="margin-bottom: 0.75em;">Cerebral Palsy and Spasticity Trials: Worked with doctors on a study assessing functional gain in patients affected by stroke or spasticity using assistive robots.</li>
        </ul>
    </div>
</div>

<div id="footer">
    ©Gautham Vasan  | Design inspired by <a href="https://abhishekdas.com/">Abhishek Das</a> & <a href="https://andyzeng.github.io/">Andy Zeng</a>.
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var researchBtn = document.querySelector('button[data-filter=".research"]');
  if (researchBtn) {
    researchBtn.click();
  }
});
</script>


[RL-wiki]: https://en.wikipedia.org/wiki/Reinforcement_learning
