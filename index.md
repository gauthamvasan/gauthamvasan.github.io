---
layout:     page
title:
permalink:  /
---

<div id="intro">
    <div id="intro-text">
        <h1>Gautham Vasan</h1>
        <p>
            I'm a final-year PhD candidate in Computing Science at the University of Alberta, advised by <a href="https://armahmood.github.io/">Dr. Rupam Mahmood</a>. My research  interested in building intelligent agents that can continually learn, adapt, develop, and improve throughout their lives. To this end, I've designed and developed deep reinforcement learning algorithms and real-time learning systems for real-world robots. 
            <br><br>
            📢 <b>I am on the job market for Winter 2026.</b> Feel free to reach out if you think I’d be a good fit for your research position. 
            <br><br> 
            <a href="https://scholar.google.ca/citations?user=4qMs0zMAAAAJ&hl=en&oi=ao">Google Scholar</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://github.com/gauthamvasan">GitHub</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://www.linkedin.com/in/gauthamvasan/">LinkedIn</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="https://www.goodreads.com/user/show/29446357-gautham-vasan">Goodreads</a>&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="mailto:gauthamv.529@gmail.com">Email</a>
        </p>
    </div>
    <div id="intro-image">
        <img src="/img/Gautham_brown_jacket_2023.jpg">
    </div>
</div>

<div id="filters" class="button-group">
    <button class="button is-checked" data-filter=".research">Research</button>
    <button class="button" data-filter=".publication">Publications</button>
    <button class="button" data-filter=".talk">Talks</button>
    <button class="button" data-filter=".misc">Misc</button>
</div>

<div class="grid">
    <!-- Research -->
    <div class="list-item research-project" data-category="research">
        <h3>Continual Reinforcement Learning</h3>
        <a href="https://www.youtube.com/watch?v=QO0mmHMJvRQ"><img src="/img/madi_robot.png" alt="Continual Reinforcement Learning" /></a>
        <p>How can we build agents that continually learn and adapt in the real world? My work explores using reinforcement learning to allow robots to acquire skills autonomously and in real-time. See my talk <a href="https://www.youtube.com/watch?v=QO0mmHMJvRQ">here</a>.</p>
    </div>
    <div class="list-item research-project" data-category="research">
        <h3>Efficient Deep RL Algorithms</h3>
        <a href="https://openreview.net/forum?id=DX5GUwMFFb"><img src="/img/avg-replay-buffer.png" alt="Efficient Deep RL" /></a>
        <p>Modern deep RL often relies on large replay buffers and batch updates, making them inefficient. I'm developing new algorithms that learn from a single stream of data, without replay buffers or target networks. <a href="https://openreview.net/forum?id=DX5GUwMFFb">Read the paper</a>.</p>
    </div>
    <div class="list-item research-project" data-category="research">
        <h3>Robotics and Real-Time Learning</h3>
        <a href="https://arxiv.org/abs/2210.02317"><img src="/img/ardrone.jpg" alt="Robotics and Real-Time Learning" /></a>
        <p>Applying RL to real robots is challenging. I've developed systems that enable vision-based robots to learn in real-time by distributing computation between local and remote resources. <a href="https://arxiv.org/abs/2210.02317">Find out more</a>.</p>
    </div>
    <div class="list-item research-project" data-category="research">
        <h3>Sample-Efficient Generalization</h3>
        <a href="https://arxiv.org/abs/2312.15339"><img src="/img/madi.png" alt="Sample-Efficient Generalization" /></a>
        <p>How can agents generalize from limited experience? My work on Masked Distractions (MaDi) shows how agents can learn to ignore irrelevant parts of their visual input to generalize better. <a href="https://arxiv.org/abs/2312.15339">Check out the paper</a>.</p>
    </div>

    <!-- Publications -->
    <div class="list-item publication" data-category="publication">
        <a href="https://openreview.net/forum?id=DX5GUwMFFb" class="thumbnail">
            <img src="/img/avg-replay-buffer.png" alt="AVG paper thumbnail" />
        </a>
        <div class="project-description">
            <h3><a href="https://openreview.net/forum?id=DX5GUwMFFb">Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</a></h3>
            <p>
                Gautham Vasan, Mohamed Elsayed, Alireza Azimi*, Jiamin He*, Fahim Shahriar, Colin Bellinger, Martha White, A. Rupam Mahmood<br>
                <i>NeurIPS 2024</i><br>
                <a href="https://openreview.net/forum?id=DX5GUwMFFb">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://github.com/gauthamvasan/avg">Code</a>
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
                Mohamed Elsayed, Gautham Vasan, A. Rupam Mahmood<br>
                <i>Pre-Print, NeurIPS FitML Workshop 2024</i><br>
                <a href="https://arxiv.org/abs/2410.14606">Paper</a>
            </p>
        </div>
    </div>
     <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2407.00324" class="thumbnail">
             <img src="/img/min-time-overlay.png">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2407.00324">Revisiting Sparse Rewards for Goal-Reaching Reinforcement Learning</a></h3>
            <p>
                Gautham Vasan, Yan Wang, Fahim Shahriar, James Bergstra, Martin Jagersand, A. Rupam Mahmood<br>
                <i>RLC 2024</i><br>
                <a href="https://arxiv.org/abs/2407.00324">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/a6zlVUuKzBc">Demo</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://openreview.net/pdf?id=TgXIkK8WPQ" class="thumbnail">
             <img src="/img/RL_Chemist_Setup.png">
        </a>
        <div class="project-description">
            <h3><a href="https://openreview.net/pdf?id=TgXIkK8WPQ">Versatile and Generalizable Manipulation via Goal-Conditioned Reinforcement Learning with Grounded Object Detection</a></h3>
            <p>
                Huiyi Wang, Fahim Shahriar, Alireza Azimi, Gautham Vasan, A. Rupam Mahmood, Colin Bellinger<br>
                <i>CoRL MRM-D Workshop 2024</i><br>
                <a href="https://openreview.net/pdf?id=TgXIkK8WPQ">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf" class="thumbnail">
             <img src="/img/calvin_hobbes_starry_night.jpg">
        </a>
        <div class="project-description">
            <h3><a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf">Autonomous Skill Acquisition for Robots Using Graduated Learning</a></h3>
            <p>
                Gautham Vasan<br>
                <i>AAMAS Doctoral Consortium 2024</i><br>
                <a href="https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2785.pdf">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2312.15339" class="thumbnail">
             <img src="/img/madi.png">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2312.15339">MaDi: Learning to Mask Distractions for Generalization in Visual Deep Reinforcement Learning</a></h3>
            <p>
                Bram Grooten, Tristan Tomilin, Gautham Vasan, Matthew E Taylor, A Rupam Mahmood, Meng Fang, Mykola Pechenizkiy, Decebal Constantin Mocanu<br>
                <i>AAMAS 2024</i><br>
                <a href="https://arxiv.org/abs/2312.15339">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/2oImF0h1k48">Video</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://proceedings.mlr.press/v202/che23c.html" class="thumbnail">
             <img src="/img/discount_correction.png">
        </a>
        <div class="project-description">
            <h3><a href="https://proceedings.mlr.press/v202/che23c.html">Correcting Discount-Factor Mismatch in On-Policy Policy Gradient Methods</a></h3>
            <p>
                Fengdi Che, Gautham Vasan, A. Rupam Mahmood<br>
                <i>ICML 2023</i><br>
                <a href="https://proceedings.mlr.press/v202/che23c.html">Paper</a>
            </p>
        </div>
    </div>
    <div class="list-item publication" data-category="publication">
        <a href="https://arxiv.org/abs/2210.02317" class="thumbnail">
             <img src="/img/relod.png">
        </a>
        <div class="project-description">
            <h3><a href="https://arxiv.org/abs/2210.02317">Real-Time Reinforcement Learning for Vision-Based Robotics Utilizing Local and Remote Computers</a></h3>
            <p>
                Yan Wang*, Gautham Vasan*, A. Rupam Mahmood<br>
                <i>ICRA 2023</i><br>
                <a href="https://arxiv.org/abs/2210.02317">Paper</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;
                <a href="https://youtu.be/7iZKryi1xSY">Video</a>
            </p>
        </div>
    </div>

    <!-- Talks -->
    <div class="list-item talk" data-category="talk">
        <h3>Deep Policy Gradient Methods Without Batch Updates, Target Networks, or Replay Buffers</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/mQc4ETehniI?si=xG6ZJeOiRRymrDiv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <div class="list-item talk" data-category="talk">
        <h3>Two Issues of Autonomous Robot Learning</h3>
        <p>I discuss some practical, oft-ignored challenges in continual learning on real-world robots. More specifically I address two research questions: (i) How to specify reinforcement learning tasks?, and (ii) How to set up a real-time learning agent?</p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/QO0mmHMJvRQ?si=KGif_tvrkIN06zo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <div class="list-item talk" data-category="talk">
        <h3>Tea Time Talks: Reward (Mis-)Specification in Reinforcement Learning</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/yqeiXpbDoKg?si=NuWSQoWizPiLL8Ic&amp;start=517" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <div class="list-item talk" data-category="talk">
        <h3>natChat: Neurotech in Artificial Intelligence (2023)</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/kkJ8-k-_CPQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>

    <!-- Misc -->
    <div class="list-item misc" data-category="misc">
        <h3>Miscellaneous Stuff I'm Proud To Have Been A Part Of</h3>
        <ul>
            <li>A short stint as a research volunteer with The Hospital for Sick Children (<b><a href="https://www.sickkids.ca/">SickKids</a></b>).</li>
            <li><b>Cerebral Palsy and Spasticity Trials</b>. I had the pleasure of working with medical doctors on a study assessing functional gain in patients affected by stroke or spasticity using assistive robots.</li>
            <li><b>Festember</b>, the annual International cultural festival of NIT Trichy. I was the <i>Treasurer</i> of <i>Festember 2014</i>, handling the finances of the festival (~INR 20 Million).</li>
            <li><b>Spider</b>, an R&D club at NIT Trichy. We conducted tech talks and workshops focusing on microcontrollers and embedded programming.</li>
            <li><b>Pragyan</b>, the annual technical festival of NIT Trichy. Personal highlights: helping moderate a panel discussion on "Failing educational institutions?" and having <a href="https://en.wikipedia.org/wiki/Jamie_Hyneman">Jamie Hyneman</a> of Mythbusters as a guest lecturer.</li>
        </ul>
    </div>
</div>

<div id="footer">
    ©Gautham Vasan  | Design inspired by <a href="https://abhishekdas.com/">Abhishek Das</a> & <a href="https://andyzeng.github.io/">Andy Zeng</a>.
</div>


[RL-wiki]: https://en.wikipedia.org/wiki/Reinforcement_learning
