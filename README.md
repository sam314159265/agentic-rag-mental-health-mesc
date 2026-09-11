# agentic-rag-mental-health-mesc

Mental-health-oriented conversational systems require
more than fluent language generation; they must produce
responses that are empathetic, context-aware, and grounded in
relevant prior examples. This paper proposes an agentic retrievalaugmented
generation (RAG) framework for mental health
response generation using the Multimodal Emotional Support
Conversation (MESC) benchmark in a text-only setting. The
system follows a modular pipeline consisting of a Planner Agent,
Retriever Tool, Answer Agent, and Critic Agent arranged in an
iterative refinement loop. The Planner Agent reformulates the
user query for effective retrieval, the Retriever identifies semantically
similar benchmark instances, the Answer Agent generates
a grounded supportive response, and the Critic Agent evaluates
and refines the output based on multiple quality dimensions.
To complement qualitative assessment, the framework incorporates
benchmark-oriented metrics including BLEU, ROUGEL,
BERTScore, perplexity, and strategy accuracy. Experimental
results demonstrate that the proposed approach improves both
semantic quality and strategy alignment compared to baseline
models. This work highlights the effectiveness of combining structured
prompting, retrieval grounding, and iterative refinement
for building more reliable mental health support systems
