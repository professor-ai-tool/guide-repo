# AI Engineer Take-Home Task: Development of a Document-Enriched AI Chatbot

## Objective

Develop a console-based AI chatbot that utilizes generative AI techniques for accurate and informative responses, with a focus on mitigating hallucinations. The chatbot should leverage external PDF documents and vector database searches to verify information and enhance response reliability.

## Requirements

### 1. Chatbot Framework

- Implement a basic console chatbot interface capable of accepting user queries and returning responses.
- Utilize a pre-trained language model (e.g., GPT-4) for generating responses.

### 2. Document Handling

- Integrate a PDF parser to extract text from provided PDF documents, serving as a trusted knowledge base.
- Implement functionality to search these documents based on user queries for relevant information.

### 3. Vector Database Integration

- Create or integrate a vector database for efficient information storage and retrieval, indexing the PDF document contents.
- Use vector search techniques to find the most relevant document sections in response to user queries, aiding in response validation.

### 4. Hallucination Mitigation

- Develop a mechanism to detect potential inaccuracies in the chatbot's responses.
- Cross-reference generated responses with the knowledge base (PDF documents) and vector database for fact verification before presenting to the user.

### 5. Testing and Evaluation

- Provide a set of test queries and document the chatbot's performance, focusing on accuracy, response time, and hallucination mitigation.
- Include an evaluation of document and vector database integration's effectiveness in improving response reliability.

## Deliverables

- **Source Code:** Complete source code for the chatbot, including all dependencies and setup instructions.
- **Knowledge Base:** A small collection of PDF documents to serve as the initial knowledge base.
- **Documentation:** Detailed system architecture documentation, instructions for running the bot, and an overview of the hallucination mitigation strategy.
- **Testing Report:** A summary of the testing methodology, results, and insights or challenges encountered during development.

## Evaluation Criteria

- **Functionality:** Operation of the chatbot, effectiveness in handling queries, and integration of external data sources.
- **Innovation:** Novel approaches or technologies used in the chatbot's development.
- **Code Quality:** Organization, commenting, and adherence to best practices in the code.
- **Performance:** Effectiveness in mitigating hallucinations and overall response quality.
- **Documentation:** Clarity and completeness of provided documentation and reports.

## Timeline: 3 Days
