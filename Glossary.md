# Glossary

## Discussion of Terms

Within xMentium, there are several terms that are used interchangeably or are more or less synonymous with common terms found outside of xMentium when discussing artificial intelligence and large language models. Below is a brief discussion of the terms and how they relate to one another.

Without getting into the specifics of the syntax behind the xMentium Automations (XADL, a custom YAML language), the following terms are used.

### "Prompt" and "Instruction"

These terms are used interchangeably. "Prompt" is a term that emerged early in general user engagement with platforms like ChatGPT where users would "prompt" the LLM to generate text in response to particular queries or instructions. My personal preference is to refer to the act of passing a prompt to the LLM as an instruction. This is because "prompt" seems, to me, to indicate that you're nudging something into an action whereas "instruction" indicates a higher level of control over the action the LLM takes to accomplish any given desired outcome.

### "Prompt Automation" and "Language Automation"

For all intents and purposes, these two things are also interchangeable. However, there is little reason (aside from potential brand considerations) to qualify "Automation" with any precursor. Automations are simply the compilation of inputs, actions, and functions contained with the XADL syntax that tell our platform from where to retrieve information, how to manipulate it, where the results should be stored, and in what format the outputs should be displayed. Using words like "prompt" or "language" before "automation" simply adds new opportunities to confuse and diverge the way we articulate our capabilities.

### "Tasks"

The simplest term to explain, tasks are simply how the xMentium platform queues automations. The "Task Monitor" watches the running automations and their progress to determine when/if they properly complete. "Tasks" could be used to refer to subcomponents of the XADL syntax. If an automation requires the completion of multiple loops/repeats or involves particular instructions being passed to the LLM for certain conditions, they could be used to refer to those specific instructions.