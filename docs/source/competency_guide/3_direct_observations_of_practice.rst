================================================================================
Limitations of Direct Observations of Practice for bioinformatics
================================================================================

Direct Observations of Practice (DOPs) are a well-established competency assessment
tool in clinical laboratories, widely used to document procedural competence and
accepted as valid evidence under ISO 15189 and ISO 17025. For conventional laboratory
procedures (where tasks are standardised, observable, and repeatable) they are a
well-suited and practical assessment method.

Bioinformatics work, however, does not share these characteristics. Pipeline
development and analysis is computational, iterative, and reliant on expert
judgement in ways that make DOPs rarely appropriate, except in a small number
of specific contexts. This page sets out where those exceptions lie and where
DOPs break down.

------------------------------------------------------------------------------------------

Where DOPs remain appropriate
------------------------------

DOPs are suitable where a task is procedural, the steps are fixed, and performance
can be directly observed against a defined standard. Within a bioinformatics context, examples include:

.. dropdown:: Example 1

    Add text

.. dropdown:: Example 2
    
    Add text

.. dropdown:: Example 3
    
    Add text

In these cases, a DOP provides meaningful competency evidence that is proportionate
to the task and straightforward to document for ISO 15189 and ISO 17025 purposes.

------------------------------------------------------------------------------------------

Where DOPs break down
----------------------

Beyond these procedural examples, several characteristics of bioinformatics work
make DOP-style assessment unsuitable:

.. grid:: 1
   :gutter: 3

   .. grid-item-card:: Iterative, non-linear workflows
        :class-card: sd-bg-light sd-text-dark

        Bioinformaticians loop through cycles of building, testing, and refinement. There is no single correct sequence of steps to observe or score.

   .. grid-item-card:: Cognitive, diagnostic reasoning
        :class-card: sd-bg-light sd-text-dark
        
        Debugging software, resolving dependency conflicts, and investigating unexpected results are mental processes — not observable procedural steps.

   .. grid-item-card:: Multiple valid approaches
        :class-card: sd-bg-light sd-text-dark

        Two bioinformaticians may solve the same problem using entirely different tools or strategies. DOPs assume a single standardised method that rarely exists in computational practice.

   .. grid-item-card:: Unpredictable failure modes
        :class-card: sd-bg-light sd-text-dark
        
        Technical issues (version mismatches, file corruption) and biological artefacts (contamination, low-quality data) require adaptive investigation that cannot be scripted in advance.

   .. grid-item-card:: Invisible decision-making
        :class-card: sd-bg-light sd-text-dark

        The most consequential decisions occur within code or in the analyst's reasoning process — neither of which is visible to an observer in real time.

.. warning::
    
    Applying DOPs to tasks where analyst judgement is central risks assessing superficial behaviours rather than genuine competence. It may also penalise bioinformaticians for taking valid alternative approaches, which is a poor basis for competency evidence under either standard.
