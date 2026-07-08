=========================================================
Competency frameworks: an alternative for bioinformatics
=========================================================

Why competency frameworks suit bioinformatics
----------------------------------------------

Competency frameworks offer a structured way to define the skills, knowledge, and behaviours required for effective performance in a role. They are particularly well-suited to bioinformatics, where work is analytical, iterative, and difficult to assess through direct observation of a single standardised procedure. Rather than focusing on visible tasks, competency frameworks capture the broader capabilities that underpin real-world practice such as troubleshooting, data interpretation, pipeline development, and analytical reasoning.

A competency framework breaks a role into key areas of practice and describes how individuals progress from beginner to expert. Many frameworks draw on established educational models including the :ref:`Dreyfus Model of Skill Acquisition <dreyfus-model>` and :ref:`Bloom's taxonomy <bloom-taxonomy>` to articulate levels of expertise and the cognitive complexity of tasks. This allows organisations to express not only what a clinical bioinformatician should be able to do, but how their capability is expected to develop over time.

For bioinformatics teams operating under ISO 15189 or ISO 17025, competency frameworks provide:

- A common structure for describing skills across staff with diverse backgrounds
- A realistic way to capture competencies that are not directly observable
- Clear progression pathways for staff development (from beginner to expert)
- A practical mechanism for demonstrating compliance with accreditation competency requirements

.. _dreyfus-model:

.. dropdown:: Dreyfus Model of Skill Acquisition

    The Dreyfus Model of Skill Acquisition describes how individuals progress through stages of learning and skill development, ranging from novice to expert, and provides a framework for understanding how people acquire and refine skills over time. The model emphasises the importance of experience, context, and intuition in developing expertise, and is widely used in education, training, and professional development.

    While the original model defined five stages (novice, advanced beginner, competent, proficient, expert), for the purposes of assessing bioinformatics competency we suggest a simplified version of the model, which focuses on four levels:

    .. raw:: html

       <style>
       .flip-grid {
         display: grid;
         grid-template-columns: 1fr 1fr;
         gap: 16px;
         margin: 1.5rem 0;
       }
       .flip-card {
         height: 160px;
         perspective: 1000px;
         cursor: pointer;
       }
       .flip-card-inner {
         position: relative;
         width: 100%;
         height: 100%;
         transition: transform 0.5s ease;
         transform-style: preserve-3d;
       }
       .flip-card.flipped .flip-card-inner {
         transform: rotateY(180deg);
       }
       .flip-card-front,
       .flip-card-back {
         position: absolute;
         width: 100%;
         height: 100%;
         backface-visibility: hidden;
         -webkit-backface-visibility: hidden;
         border-radius: 8px;
         padding: 1rem 1.25rem;
         box-sizing: border-box;
         border: 0.5px solid #D3D1C7;
       }
       .flip-card-front {
         background: #F8F8F6;
         display: flex;
         flex-direction: column;
         justify-content: center;
         align-items: center;
         text-align: center;
       }
       .flip-card-back {
         transform: rotateY(180deg);
         display: flex;
         flex-direction: column;
         justify-content: center;
       }
       .flip-card-front .card-title {
         font-weight: 700;
         font-size: 16px;
         color: #1a1a1a;
         margin: 0 0 0.75rem;
       }
       .flip-card-back .card-body {
         font-size: 13px;
         color: #FFFFFF;
         line-height: 1.5;
         margin: 0;
       }
       .flip-hint {
         font-size: 11px;
         color: #888;
         margin-top: 0.5rem;
         text-align: center;
       }

       /* Level-specific back panel colours, matching Bloom's/competency palette */
       .flip-card-back.back-beginner {
         background: #37474F;
       }
       .flip-card-back.back-competent {
         background: #2E7D32;
       }
       .flip-card-back.back-proficient {
         background: #6A3FA0;
       }
       .flip-card-back.back-expert {
         background: #E0398C;
       }
       </style>

       <script>
       function flipCard(card) {
         const allCards = document.querySelectorAll('.flip-card');
         allCards.forEach(function(c) {
           if (c !== card) {
             c.classList.remove('flipped');
           }
         });
         card.classList.toggle('flipped');
       }
       </script>

    .. raw:: html

       <div class="flip-grid">

         <div class="flip-card" onclick="flipCard(this)">
           <div class="flip-card-inner">
             <div class="flip-card-front">
               <p class="card-title">Beginner</p>
               <p class="flip-hint">click for more detail</p>
             </div>
             <div class="flip-card-back back-beginner">
               <p class="card-body">Learners at this level have limited experience
               and require guidance and supervision to perform tasks. They are
               developing foundational knowledge and skills but may struggle with
               complex or unfamiliar situations.</p>
             </div>
           </div>
         </div>

         <div class="flip-card" onclick="flipCard(this)">
           <div class="flip-card-inner">
             <div class="flip-card-front">
               <p class="card-title">Competent</p>
               <p class="flip-hint">click for more detail</p>
             </div>
             <div class="flip-card-back back-competent">
               <p class="card-body">Individuals at this level have a solid
               understanding of the domain and can perform tasks with minimal
               supervision. They are able to apply their knowledge to solve
               problems and make decisions, but may still require support for
               more complex or novel situations.</p>
             </div>
           </div>
         </div>

         <div class="flip-card" onclick="flipCard(this)">
           <div class="flip-card-inner">
             <div class="flip-card-front">
               <p class="card-title">Proficient</p>
               <p class="flip-hint">click for more detail</p>
             </div>
             <div class="flip-card-back back-proficient">
               <p class="card-body">Individuals at this level have developed a
               high degree of skill and can perform tasks independently. They are
               able to handle complex and novel situations effectively, drawing
               on their experience and intuition.</p>
             </div>
           </div>
         </div>

         <div class="flip-card" onclick="flipCard(this)">
           <div class="flip-card-inner">
             <div class="flip-card-front">
               <p class="card-title">Expert</p>
               <p class="flip-hint">click for more detail</p>
             </div>
             <div class="flip-card-back back-expert">
               <p class="card-body">Experts possess a deep understanding of the
               domain and can innovate and lead in their field. They are able to
               guide others, make strategic decisions, and contribute to the
               advancement of the discipline.</p>
             </div>
           </div>
         </div>

       </div>

.. _bloom-taxonomy:

.. dropdown:: Bloom's taxonomy

    Bloom's taxonomy is a hierarchical framework for categorising educational objectives and learning outcomes. It classifies cognitive skills into six levels, from lower-order thinking skills (remembering, understanding) to higher-order thinking skills (applying, analysing, evaluating, creating). Bloom's taxonomy is widely used in curriculum design, assessment, and instructional planning to promote critical thinking and deeper learning.

    When defining competency levels within our proposed bioinformatics competency framework, we have tried to incorporate Bloom's levels of cognitive complexity into how each competency level is defined. Remember maps to Beginner, reflecting basic recall of facts and concepts. Understand and Apply both map to Competent, reflecting the ability to explain ideas and use information in new situations with minimal supervision. Analyse and Evaluate both map to Proficient, reflecting the ability to draw connections among ideas and justify decisions independently. Create maps to Expert, reflecting the ability to produce new or original work by synthesising knowledge.

    .. figure:: ../_static/blooms_taxonomy.png
        :align: center
        :width: 650px

        Bloom's taxonomy and mapping to competency levels

------------------------------------------------------

What this guide introduces
---------------------------

This guide sets out the core components needed to implement a competency-based
approach for bioinformatics:

.. grid:: 1
    :gutter: 3

    .. grid-item-card:: Competency framework
        :class-card: sd-bg-light sd-text-dark
        :link: 5_bioinformatics_skills_framework
        :link-type: doc

        A structured set of domains and skill levels tailored to bioinformatics, defining what staff at each level should know and be able to do.

    .. grid-item-card:: Assessment framework
        :class-card: sd-bg-light sd-text-dark
        :link: 6_assessing_bioinformatics_competency
        :link-type: doc

        A description of how staff demonstrate capability, what evidence is required, and how that evidence is reviewed and recorded.

    .. grid-item-card:: Training framework
        :class-card: sd-bg-light sd-text-dark
        :link: 8_training_development
        :link-type: doc

        An outline of how staff can develop the skills required to progress through the competency levels, including suggested learning activities and resources.