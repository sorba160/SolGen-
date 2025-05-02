# SolGen-: Secure Smart Contract Code Generation Using Large Language Models Via Masked Prompting
Owing to the swift advancement of technology and the unfamiliarity of the execution environment, the development of
Solidity smart contracts from scratch often results in significant vulnerabilities. In contrast, automated code generation
enhances productivity, minimizes development time, and
enables developers to focus on high-level tasks and fundamental logic. In consideration of these two viewpoints,
this paper examines the utilization of large language models (LLMs) for the automatic generation of Solidity smart
contracts based on specified criteria, while simultaneously
ensuring the elimination of vulnerabilities through a novel
masking strategy. To achieve this, we propose SolGen, a
framework for generating secure Solidity smart contract
code using LLMs. We assess the performance of existing
LLMs (i.e. ChatGPT and Meta AI) for secure Solidity code
generation. Our research indicates that ChatGPT outperforms Meta AI in performance, yielding a greater percentage
of syntactically accurate and secure code. Additionally, we
examine the impact of temperature adjustment on the security of generated contracts using an open-source LLM,
Llama3. Our findings suggest that a temperature setting of
0.7 is optimal for the generation of Solidity code, considerably exceeding the performance of both lower and higher
settings (0.1 and 1.2), especially with regard to the compilability of the code.
