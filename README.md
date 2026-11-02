## EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization
## AIM
To analyze and compare the performance of various prompting techniques (Zero-Shot, Few-Shot, Chain-of-Thought and Role-Based Prompting) across different AI platforms (ChatGPT, Gemini, Claude AI and Microsoft Copilot) for the purpose of text summarization.
## Scenario
You are a member of a content development team for an online learning platform that delivers simplified summaries of research articles to undergraduate students.
The objective is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting methods.
The generated summaries are assessed based on these factors:
- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience
## Abstract
Artificial Intelligence platforms are widely used to summarise technical articles and research papers. However, the quality of a summary depends on both the AI platform and the prompting technique used.

This experiment focuses on summarising a 500-word technical article titled "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies. Different prompting techniques, including Zero-Shot Prompting, Few-Shot Prompting, Role-Based Prompting and Chain-of-Thought Prompting, are considered.

The generated summaries are evaluated based on five criteria: Accuracy, Coherence, Simplicity, Speed and User Experience.

The main objective is to identify which combination of AI platform and prompting technique produces the most accurate, clear and student-friendly summary.
## Objectives
1. To understand the basics of Blockchain Technology.</br>
2. To study different AI platforms used for summarisation.</br>
3. To understand various prompting techniques.</br>
4. To generate summaries using different AI platforms.</br>
5. To compare the results based on accuracy, coherence, simplicity, speed and user experience.</br>
6. To identify the most effective platform and prompting technique.</br>
7. To understand the importance of prompt engineering in AI-based summarisation.</br>

## Introduction
1. What is Blockchain Technology?</br>
Blockchain is a decentralised digital ledger technology used to record and store transactions securely across multiple computers in a network.
Information is stored in groups called blocks. Each block contains transaction data, a timestamp and a cryptographic hash that connects it to the previous block.
Once a block is validated and added to the blockchain, changing its information becomes extremely difficult because the connected blocks would also need to be altered.</br>

Example: Bitcoin uses blockchain technology to record cryptocurrency transactions without requiring a central bank to maintain the transaction ledger.</br>

2. Main Features of Blockchain </br>
1. Decentralisation: Data is maintained across multiple computers rather than one central authority.</br>
2. Transparency: Participants with appropriate access can verify recorded transactions.</br>
3. Security: Cryptographic techniques help protect blockchain records.</br>
4. Immutability: Recorded information is difficult to modify without detection.</br>
5. Distributed Ledger: Multiple network participants maintain copies of the ledger.</br>
6. Consensus Mechanism: Network participants follow agreed rules to validate transactions.</br>

3. Blockchain Architecture</br>

<img width="996" height="502" alt="image" src="https://github.com/user-attachments/assets/bb49f9ec-0428-4ac0-aab8-dc410a7b0045" />

Explanation:</br>
- Each block contains transaction information.</br>
- Every block has its own cryptographic hash.</br>
- The previous block's hash connects the blocks.</br>
- The first block is called the Genesis Block.</br>
- Multiple computers maintain and verify the distributed ledger.</br>
4. AI Platforms Used for the Experiment</br>
The following AI platforms are selected for comparison.</br>


## ChatGPT
Used to generate structured, understandable and detailed summaries of technical articles.</br>
Website: ChatGPT</br>

## Google Gemini
Used to summarise technical information and explain complex concepts in simple language.</br>
Website: Google Gemini</br>

## Claude AI

Used to generate coherent summaries with clear explanations and logical organisation.</br>
Website: Claude</br>

## Microsoft Copilot

Used to produce concise summaries and simplified explanations.</br>
Website: Microsoft Copilot</br>


## Prompting Techniques Used
Prompt engineering is the process of designing instructions to guide an AI model towards producing the desired output.
# 1. Zero-Shot Prompting
Zero-Shot Prompting means asking an AI model to perform a task without providing any examples.</br>

Prompt:</br>

"Summarise the following 500-word article on Blockchain Technology in 150 words. Use simple English and include the important concepts."</br>

Advantages:</br>
- Easy to use.</br>
- Requires less preparation.</br>
- Produces quick results.</br>
Limitation: The summary may miss some important technical details.</br>

# 2. Few-Shot Prompting</br>
Few-Shot Prompting provides a small number of examples to guide the AI model.</br>
Prompt:</br>
"Summarise the following article using this example format.</br>
Example:</br>
Input: Artificial Intelligence enables machines to perform intelligent tasks.</br>

Output: AI allows computers to perform tasks that normally require human intelligence.</br>

Now summarise the article on Blockchain Technology in approximately 150 words using the same simple style and format."</br>

Advantages:</br>
- Helps maintain a consistent output format.</br>
- Provides better guidance.</br>
- Useful for educational summaries.</br>
Limitation: Requires additional examples and prompt preparation.</br>

# 3. Role-Based Prompting
Role-Based Prompting assigns a specific role to the AI model before asking it to perform a task.</br>

Prompt:</br>

"Act as an experienced Computer Science professor. Summarise the following article on Blockchain Technology for second-year engineering students. Explain technical terms in simple English and include the key concepts, advantages and applications."</br>

Advantages:</br>
- Produces audience-focused explanations.</br>
- Encourages simple language.</br>
- Helps organise the content.</br>
Limitation: Assigning a role does not guarantee factual accuracy.</br>

# 4. Chain-of-Thought Prompting
Chain-of-Thought Prompting encourages structured reasoning through intermediate steps. For this summarisation task, ask the model to analyse the main ideas before presenting only the final summary.</br>

Prompt:</br>

"Analyse the following article on Blockchain Technology. First identify the main concepts, technical terms, working principles and applications. Check that the important information is preserved. Then provide a concise, well-organised summary in simple English within 150 words."</br>

Advantages:</br>
- Encourages systematic analysis.</br>
- Helps organise complex information.</br>
- Can reduce the chance of omitting important concepts.</br>
Limitation: May require more processing time and does not automatically guarantee correctness.</br>

## 5 Comparison of Prompting Techniques
Technique	Main purpose	Advantage	Limitation
Zero-Shot	Direct instructions	Fast and simple	Less control
Few-Shot	Uses examples	Consistent output	Requires examples
Role-Based	Assigns a role	Audience-focused	Role alone cannot ensure accuracy
Chain-of-Thought	Structured analysis	Organised output	May take longer

## 6. Experimental Methodology

The experiment follows these steps:
1. Select a 500-word technical article on Blockchain Technology.
2. Select four AI platforms.
3. Prepare four prompting techniques.
4. Enter the same article into each platform.
5. Apply the selected prompts.
6. Collect the generated summaries.
7. Evaluate the outputs using five evaluation criteria.
8. Compare the results.
9. Identify the best-performing combination.

<img width="773" height="590" alt="image" src="https://github.com/user-attachments/assets/7e24ceb5-52ed-4776-8b0f-3177f9dbdf7c" />

6.2 Experimental Design
Parameter	Description
Input	500-word blockchain article
AI platforms	ChatGPT, Gemini, Claude, Copilot
Prompting methods	Zero-Shot, Few-Shot, Role-Based, Chain-of-Thought
Output	Approximately 150-word summary
Evaluation	Five quality criteria
Final objective	Select the best platform and prompt combination

A fair comparison requires using the same article, equivalent instructions, similar output length and consistent evaluation standards.
## 7. Sample Input Article
Title: The Basics of Blockchain Technology

Blockchain is a distributed digital ledger technology that stores information in a secure and transparent manner. It consists of a series of blocks connected using cryptographic hashes. Each block contains transaction data, a timestamp and the hash of the previous block.

Unlike traditional databases, blockchain does not depend on a single central authority. Instead, information is maintained across multiple computers called nodes. Every participant in the network can maintain a copy of the ledger.

Blockchain uses consensus mechanisms such as Proof of Work (PoW) and Proof of Stake (PoS) to validate transactions and maintain agreement among network participants. Cryptography protects transaction records and helps prevent unauthorised changes.

Smart contracts are programs stored on a blockchain that automatically execute predefined conditions. They are useful in applications such as financial services, supply chain management and digital agreements.

Blockchain technology is widely used in cryptocurrencies such as Bitcoin and Ethereum. It also supports applications in healthcare, banking, logistics and identity management.

The major advantages of blockchain include decentralisation, transparency, security and traceability. However, it also has limitations such as scalability challenges, energy consumption in some consensus systems, regulatory uncertainty and implementation costs.

Blockchain technology continues to develop and has the potential to improve the security, efficiency and transparency of digital transactions.
## 8. Sample Generated Summary
The following is an example of the expected summary format.

The Basics of Blockchain Technology – Summary

Blockchain is a decentralised digital ledger that stores transaction information in connected blocks. Each block contains transaction data, a timestamp and a cryptographic hash linking it to the previous block. Multiple computers called nodes maintain copies of the ledger, reducing dependence on a central authority.

Blockchain uses consensus mechanisms such as Proof of Work and Proof of Stake to validate transactions. Smart contracts automatically execute predefined conditions. Its applications include cryptocurrency, banking, healthcare and supply chain management.

The main advantages of blockchain are security, transparency, decentralisation and traceability. However, it faces challenges such as scalability, energy consumption in some systems, regulatory uncertainty and implementation 


## 9. Evaluation Criteria
The generated summaries are evaluated using the following five criteria.
9.1 Accuracy
Measures whether the summary correctly represents the original article without introducing false information.
9.2 Coherence
Measures whether the summary is logically organised and the sentences connect smoothly.
9.3 Simplicity
Measures whether undergraduate students can understand the summary easily.
9.4 Speed
Measures how quickly the AI platform generates the requested summary.
9.5 User Experience
Measures the ease of interacting with the AI platform, including its interface, readability and usefulness.



<img width="1007" height="517" alt="image" src="https://github.com/user-attachments/assets/59d55358-5fec-4825-aae3-46be5e7dbd7c" />

## 10. Comparative Analysis of AI Platforms
The following table provides an illustrative evaluation for the experiment. These are example assessment scores, not actual measured benchmark results. Replace them with scores from your own platform tests.

Scoring scale: 1 = Poor, 2 = Average, 3 = Good, 4 = Very Good, 5 = Excellent.
Evaluation criteria	ChatGPT	Gemini	Claude	Copilot
Accuracy	5	4	5	4
Coherence	5	4	5	4
Simplicity	5	5	5	4
Speed	4	5	4	5
User Experience	5	4	5	4
Total	24	22	24	25


10.2 Analysis
- ChatGPT: Provides structured explanations and simple technical summaries.
- Gemini: Useful for quick summaries and straightforward explanations.
- Claude: Can produce well-organised summaries with coherent writing.
- Copilot: Provides convenient summarisation and integration with Microsoft's ecosystem.
Based on the illustrative scores, ChatGPT and Claude receive the highest overall scores.
11. Comparative Analysis of Prompting Techniques
The following are illustrative scores for the prompting strategies.
Criteria	Zero-Shot	Few-Shot	Role-Based	Chain-of-Thought
Accuracy	4	4	4	5
Coherence	3	5	5	5
Simplicity	4	5	5	4
Speed	5	3	4	3
User Experience	4	4	5	4
Total	20	21	23	21

11.1 Visual Comparison Chart
Prompting Technique Comparison
Illustrative scores out of 25.


06.2512.518.7525Zero-ShotFew-ShotRole-BasedChain-of-Thought














Figure 6: Comparison of prompting techniques based on total evaluation scores.
11.2 Analysis
- Zero-Shot Prompting is suitable for quick summarisation.
- Few-Shot Prompting helps maintain consistent structure and style.
- Role-Based Prompting is effective for producing student-friendly explanations.
- Chain-of-Thought Prompting encourages systematic analysis but can take more time.
Based on the illustrative scores, Role-Based Prompting performs best overall.
12. Best Combination of Platform and Prompting Technique
Based on the example evaluations, the recommended combination is:
Illustrative recommendation



Reasons:
- Provides well-structured summaries.
- Explains technical concepts in simple English.
- Supports audience-specific instructions.
- Helps maintain clarity and logical organisation.
- Offers a convenient conversational interface.

## Recommended Final Prompt
"Act as an experienced Computer Science professor and educational content writer. Read the following 500-word technical article on Blockchain Technology and prepare a concise summary of approximately 150 words for undergraduate engineering students.

Include the definition, working principle, important components, key features, applications, advantages and limitations.

Use simple English, short sentences and technically accurate explanations. Preserve all important facts from the original article. Do not add information that is not supported by the article. Organise the summary logically and make it easy for students to understand and revise."
12.1 Recommended Evaluation Process
To establish the actual best combination, test the four prompting techniques on all four platforms using the same input article.

This gives 16 experimental combinations.



## 13. Advantages of AI-Based Article Summarisation
1. Saves time when reading lengthy research papers.
2. Helps students understand technical topics.
3. Extracts important information.
4. Improves learning and revision.
5. Makes complex information easier to understand.
6. Supports different summary formats.
7. Improves productivity in educational platforms.
14. Limitations and Challenges
1. AI may generate incorrect information.
2. Important technical details may be omitted.
3. Different platforms may produce different results.
4. Some prompts may generate unnecessarily long summaries.
5. Response speed depends on the model and network conditions.
6. AI may misunderstand technical terminology.
7. Human verification is necessary before publishing summaries.
15. Future Improvements
1. Develop automated evaluation systems for summary accuracy.
2. Use domain-specific prompts for technical subjects.
3. Combine AI summarisation with fact-checking tools.
4. Support summaries in multiple languages.
5. Generate diagrams automatically from technical articles.
6. Develop personalised summaries for different student levels.
7. Use human feedback to improve educational content.
## 16. Conclusion
This experiment demonstrates the importance of selecting suitable AI platforms and prompting techniques for summarising technical research articles.

Four AI platforms, namely ChatGPT, Gemini, Claude and Microsoft Copilot, were considered along with four prompting strategies: Zero-Shot, Few-Shot, Role-Based and Chain-of-Thought Prompting.

The summaries were evaluated using five criteria: Accuracy, Coherence, Simplicity, Speed and User Experience.

The illustrative evaluation indicates that ChatGPT and Claude achieve the highest platform scores, while Role-Based Prompting achieves the highest prompting-technique score.

Therefore, ChatGPT combined with Role-Based Prompting is selected as the recommended starting combination for generating simple, structured and student-friendly blockchain summaries. However, the final winner must be confirmed through actual testing of all 16 combinations using identical conditions.

The experiment highlights that prompt engineering plays an important role in improving the usefulness of Generative AI in educational content creation.
## 17. Result
The comparative study of AI platforms and prompting techniques for summarising "The Basics of Blockchain Technology" was completed.Different prompting methods and AI platforms were examined, and their performance was compared based on accuracy, coherence, simplicity, speed and user experience.

The study identified ChatGPT with Role-Based Prompting as the recommended combination based on the illustrative evaluation. The experiment demonstrates how appropriate prompt design can improve AI-generated educational summaries.
