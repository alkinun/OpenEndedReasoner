# OpenEndedReasoner: OpenEndedReasoner: Self-Improving Open-Ended Reasoning LLMs

### News:
- [Coming soon]: Full code, models, datasets, more r&d...
- [24/11/2024]: Uploaded paper to github repo.

### Absrtact:
In recent months, OpenAI o1 has shown promising progress in solving complex reasoning tasks by synthesizing chain-of-thoughts (CoT) before giving a final answer. This approach has demonstrated the potential to enhance performance on reasoning and coding tasks. However, existing methodologies remain limited by the need for human intervention, curated datasets, or grounded verifiers, especially the need for groundable topics such as mathematics, but a reinforcement learning (RL) approach has yet to be fully explored with open-ended reasoning tasks.

This paper introduces **OpenEndedReasoner**, a novel framework for enabling fully open-ended self-improvement in reasoning LLMs. By leveraging the diversity of data at both pretraining and post-training stages, **OpenEndedReasoner** iteratively generates and filters high-quality reasoning traces without requiring human intervention or seed data. The framework consists of two key components: \textbf{Question Synthesis}, which synthesizes diverse and steerable prompts, and \textbf{Response Synthesis}, which leverages a reward model that evaluates reasoning quality and selects optimal responses. Through these stages, the model refines its reasoning capabilities, producing reasoning-heavy data to improve itself continuously.

We demonstrate that **OpenEndedReasoner** achieves substantial improvements in reasoning tasks, validated by a 17.68-point gain on the GPQA benchmark across four iterations. This framework highlights the feasibility of building open-ended, self-improving reasoning systems capable of evolving their reasoning abilities.

### More testing, r&d, models, datasets, code coming soon!