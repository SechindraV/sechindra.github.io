---
title: "Teaching"
summary: "Courses and teaching philosophy"
type: landing

sections:
  - block: markdown
    id: philosophy
    design:
      spacing:
        padding: ["0rem","0","0.4rem","0"]   # trims top whitespace
    content:
      title: ""
      text: |
        <div class="teaching-scope">

          <!-- Image ABOVE the text (like your research pages) -->
          <figure class="teach-hero">
            <img src=teach.jpg loading="lazy">
          </figure>

          <p class="teach-philosophy">
          My teaching reflects the same interdisciplinary approach that guides my research: environmental challenges cannot be understood or solved through a single lens. Across all of my courses, my goal is to equip students with the disciplinary skills needed to analyze environmental problems rigorously, while also cultivating the interdisciplinary perspective required to navigate the complexities of adaptation, resilience, and sustainability. I strive to create a classroom environment that is inclusive, participatory, and attentive to the equity dimensions of environmental decision-making, preparing students to not only understand environmental challenges but also engage with them as scholars, practitioners, and citizens.
          </p>

          <div class="courses-caption">Courses I teach and have taught (click to expand):</div>

          <section class="course-accordions">

          <details>
            <summary>Environmental Policy &amp; Natural Resource Management (University of Georgia)</summary>
            <div>
              <p>This course introduces students to the complex ways societies govern environmental resources and respond to sustainability challenges. It explores how laws, markets, and institutions shape decisions about land, water, energy, and climate, drawing on both U.S. and international examples. Students engage deeply with questions of equity, justice, and governance, examining who benefits, who bears costs, and how policies can be designed more fairly and effectively. Drawing on institutional and environmental economics, human geography, and political science, students analyze real-world case studies, review key books in the field, and work on projects that connect theory to practice.</p>
            </div>
          </details>

          <details>
            <summary>Introduction to Agent-based Modeling (University of Georgia)</summary>
            <div>
              <p>This graduate seminar introduces students to agent-based modeling as a tool for understanding how individual decisions and interactions give rise to large-scale patterns in social–ecological systems. The course emphasizes complexity, feedbacks, and interdependencies across human and environmental systems. Drawing on models from human ecology, complexity science, and the social–ecological systems literature, students learn the principles of individual-based modeling, practice coding in NetLogo, and develop their own models to investigate questions from their research. Through hands-on labs, collaborative projects, and a final research-based project, students gain both technical skills and a deeper understanding of how ABMs can illuminate sustainability challenges.</p>
            </div>
          </details>

          <details>
            <summary>Ecological Basis of Environmental Issues (University of Georgia)</summary>
            <div>
              <p>This online introductory course introduces students to the principles of ecology and their application to pressing environmental challenges. It examines how natural systems function at the organismal, population, community, and ecosystem levels, and how these processes connect to issues such as population growth, biodiversity loss, climate change, pollution, and environmental ethics. Drawing on case studies from Georgia and around the world, students learn to critically evaluate environmental problems, apply ecological concepts, and explore strategies for sustainability.</p>
            </div>
          </details>

          <details>
            <summary>Perspectives on Integrative Conservation &amp; Sustainability (University of Georgia)</summary>
            <div>
              <p>This graduate seminar exposes students to the breadth of conservation and sustainability through a series of talks by scholars and practitioners from diverse disciplines and career paths. It fulfills core requirements for the Integrative Conservation programs at UGA. Students attend seminars, engage with invited speakers, and write reflections connecting presentations to broader themes in conservation and to their own research. By emphasizing multiple perspectives and career trajectories, the course cultivates critical thinking about the challenges and opportunities of integrative conservation.</p>
            </div>
          </details>

          <details>
            <summary>Economics of Sustainability (Arizona State University)</summary>
            <div>
              <p>This course applies economic principles to the study of environmental and sustainability challenges. Students learn how markets allocate environmental goods and services, why markets sometimes fail, and what policy instruments—such as standards, taxes, subsidies, and cap-and-trade—can address these failures. Topics include externalities, public goods, benefit–cost analysis, and the economics of natural resource use. By the end of the course, students gain an understanding of efficiency, equity, and policy design in sustainability contexts.</p>
            </div>
          </details>

          <details>
            <summary>Introduction to Applied Mathematics for the Life and Social Sciences (Arizona State University)</summary>
            <div>
              <p>This course introduces students to quantitative tools for analyzing sustainability challenges. Topics include data visualization, probability, exponential and logistic growth, predator–prey dynamics, and infectious disease modeling. Students learn to apply these concepts using Excel, connecting mathematical techniques to real-world issues such as population growth, ecological footprints, and resource use. By the end of the course, students gain practical skills in quantitative reasoning and a deeper appreciation of how mathematics informs sustainability science.</p>
            </div>
          </details>

          </section>

          <style>
          /* ===== Teaching page — scoped styles ===== */
          .teaching-scope { font-family: inherit; }

          /* Hero image above text */
          .teaching-scope .teach-hero {
            margin: 0 0 0.75rem 0;
          }
          .teaching-scope .teach-hero img {
            width: 100%; height: auto; display: block;
            border-radius: 14px;
            box-shadow: 0 1px 8px rgba(0,0,0,0.06);
          }

          /* Philosophy text */
          .teaching-scope .teach-philosophy {
            margin: 0 0 0.8rem 0;
            font-size: 1rem;        /* same as body */
            line-height: 1.65;
            color: inherit;
          }

          /* Caption: SAME font & size as body, just colored */
          .teaching-scope .courses-caption {
            margin: 0.6rem 0 0.3rem 0;
            font-size: 1rem;        /* match body size */
            line-height: 1.65;
            color: #d95f0e;         /* subtle accent */
          }

          /* Accordions */
          .teaching-scope .course-accordions { margin-top: 0.15rem; }
          .teaching-scope .course-accordions details {
            border: 1px solid #e6e8eb;
            border-radius: 10px;
            margin: 0.35rem 0;
            padding: 0.12rem 0.6rem;
            background: #e5f5f9;     /* faint card */
            box-shadow: 0 1px 2px rgba(0,0,0,0.03);
          }
          .teaching-scope .course-accordions summary {
            cursor: pointer; list-style: none;
            font-weight: 600;
            font-size: 1.02rem;
            padding: 0.32rem 0;
            color: #2c7fb8;          /* calm accent when closed */
          }
          .teaching-scope .course-accordions details[open] summary { color: #0f172a; }
          .teaching-scope .course-accordions summary:hover { color: #0a5f8d; }
          .teaching-scope .course-accordions summary:focus {
            outline: none;
            box-shadow: 0 0 0 2px rgba(14,165,233,0.2);
            border-radius: 6px;
          }
          .teaching-scope .course-accordions summary::-webkit-details-marker { display: none; }
          .teaching-scope .course-accordions summary::before {
            content: "+";
            display: inline-block;
            width: 1.25rem;
            margin-right: 0.25rem;
            text-align: center;
            font-weight: 700;
            color: #3aa0e6;          /* soft blue symbol */
            filter: blur(0.2px);
          }
          .teaching-scope .course-accordions details[open] summary::before { content: "−"; }
          .teaching-scope .course-accordions details > div {
            padding: 0.12rem 0.6rem 0.55rem 0.6rem;
            font-size: 0.98rem; line-height: 1.6; color: inherit;
          }
          /* tighten space before footer */
          .teaching-scope .course-accordions { margin-bottom: 0.2rem; }
          .teaching-scope .course-accordions details { margin: 0.3rem 0; }
          .teaching-scope .course-accordions details:last-of-type { margin-bottom: 0.1rem; }

          </style>

        </div>
---
