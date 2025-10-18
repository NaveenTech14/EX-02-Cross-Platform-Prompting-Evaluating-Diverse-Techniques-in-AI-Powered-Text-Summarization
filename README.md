# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

## Result
ARTICLE SUMMARY: “The Basics of Blockchain Technology”

Blockchain is a distributed digital ledger that securely records transactions across multiple computers. Each record, or “block,” contains a list of transactions, a timestamp, and a cryptographic hash of the previous block — forming an immutable “chain.” This decentralized structure eliminates the need for intermediaries like banks, reducing fraud and increasing transparency.

The technology operates through consensus mechanisms such as Proof of Work (PoW) and Proof of Stake (PoS), which verify and validate new blocks. PoW relies on computational puzzles, while PoS uses validators based on coin ownership. Each ensures that network participants agree on the current state of the blockchain.

Key components of blockchain include nodes, miners, smart contracts, and tokens. Nodes store and verify data; miners create new blocks; smart contracts execute automated agreements without intermediaries; and tokens represent digital assets.

Blockchain’s benefits include enhanced security, traceability, speed, and trust. Industries like finance, supply chain, healthcare, and voting have adopted it for transparent, tamper-proof systems. However, it also faces challenges: scalability, energy consumption, regulatory concerns, and limited interoperability.

In essence, blockchain represents a paradigm shift from centralized systems to decentralized trust networks. By providing verifiable, unchangeable records, it underpins emerging technologies like cryptocurrencies, NFTs, and Web3 applications, and continues to redefine how digital transactions are conducted.

EXPERIMENT COMPARISON
AI Platform	Prompt Type	Summary Quality	Key Notes
ChatGPT (GPT-4)	Role-based (“Summarize as if for undergraduates”)	✅ Excellent — clear, concise, and context-aware	Balanced tone, best readability
Gemini 1.5	Few-shot	✅ Accurate and factual	Slightly formal, less engaging
Claude 3	Chain-of-Thought	✅ Structured and ethical	Very detailed but longer
Copilot	Zero-shot	⚠️ Weak — overly technical	Not optimized for prose text
RESULT AND INFERENCE

The ChatGPT (GPT-4) + Role-based Prompt produced the best overall summary in terms of accuracy, simplicity, and reader engagement.
Role-based prompting helps the model understand the target audience, ensuring the explanation level suits students.
Other models performed well in factual accuracy but lacked clarity or style adaptability.

CONCLUSION

Among all tested combinations, ChatGPT with Role-based prompting delivered the most coherent, accurate, and easy-to-understand summary of blockchain technology.
This experiment shows that prompt engineering significantly influences AI output quality — especially when summarizing technical topics for educational use.


