## Language Intelligence Tasks (Text Summerization, Chat Completion, Sentiment Analysis)

**Project Link:**<a href="https://github.com/dilruu89/GENAI/tree/main/30-day-genai/chatbot-01" target="_blank">Meeting insights chatbot</a>

**Project Description:** 

Modern teams generate a lot of unstructured information in meetings—often in the form of transcripts or notes. Reviewing and distilling key insights from this text is time-consuming and inconsistent. SmartMinutes solves this problem by turning raw meeting notes or transcripts into:

- A clear summary of discussions,
- A list of actionable items (with responsibilities),
- Key themes or topics discussed, and
- An assessment of the meeting’s overall sentiment.
- 
This helps teams stay aligned, follow up faster, and capture outcomes with less effort.

### Technologies 
1. Python: For backend logic and API interaction.
2. OpenAI API (GPT-4/GPT-3.5): To extract structured insights from free-text meeting data using prompt engineering.
3. Streamlit: To build a lightweight, interactive web app that users can easily access without any setup.

### How I Designed the Prompt

The core of SmartMinutes is an engineered prompt that guides the AI to extract exactly what users need. I followed these prompt design principles:

- ** Role-based framing **: The assistant was instructed to behave like a professional meeting summarizer ("You are SmartMinutes, an AI assistant...").
- ** Explicit structure ** : I defined clear output sections—Summary, Action Items, Themes, Sentiment—to ensure predictable, parseable results.
- ** Context awareness ** : The prompt includes the entire transcript so the AI can extract relationships and intent across paragraphs.
- ** Instructional clarity ** : I used direct, numbered instructions in the prompt to minimize ambiguity and hallucination.

The prompt will be tested and refined iteratively based on edge cases (e.g., vague notes, informal language, multiple speakers).

