---
layout: essay
type: essay
title: "Reflection on AI: Thank You"
# All dates must be YYYY-MM-DD format!
date: 2025-08-05
published: true
labels:
  - Artificial Intelligence
  - Reflection
  - ICS314
---

<img class="img-fluid" src="../img/AI_Shark.jpeg">

## Introduction

Artificial intelligence (AI) is transforming many fields, and education is no exception. In software engineering, AI serves as a powerful tool to streamline development processes and enhance learning. Its relevance is growing as AI-powered tools are now integrated into many professional and academic environments. This integration provides students with new ways to understand complex concepts, write code more efficiently, and debug problems.

The primary AI tool I have used in general and in ICS 314 is Google Gemini.

## Personal Experience with AI

1. Experience WODs e.g. E18

    For a WOD on functional programming, I used Gemini with the prompt: “Write a function using underscore to implement the following       instructions:Create a variable called testdata and set it equal to the example data above."

2. In-class Practice WODs

    I intentionally avoided using Gemini for these. My goal was to test my own understanding and problem-solving skills in real-time,       just like the exam. However, I used the videos that professor provided to review them. 

3. In-class WODs

    For in-class WODs I used Gemini to give me an easier time to make functions. I used Gemini with a prompt: "Add a component to my        NextJS project that will add a login button on the top."

4. Essays

    I used Gemini extensively for my essays. For example, when writing about a technical concept, I would use a prompt like: “Explain       the concept of common mistakes in software engineering.

5. Final project

    I used Gemini sparingly for the final project, mainly for generating boilerplate code or for troubleshooting specific errors. For       example, I might use a prompt like: “Give an example of a React component that fetches data from an API and displays it in a table.”

6. Learning a concept / tutorial

    I also used Gemini for this, mainly toward the end when I tried to do my final project. I would use a prompt like: “Explain the         concept of APIs in simple terms and provide a code example in JavaScript.” 

7. Answering a question in class or in Discord

    I generally avoided using Gemini for these. I didn't think there is a need to use AI because being genuine is much nicer than being     fake and professional with your classmates.

8. Asking or answering a smart-question

    I also didn't use Gemini for these because I didn't really ask for a smart question. There were a lot of resources already so I         didn't think there was a need. 

9. Coding example e.g. “give an example of using Underscore .pluck”

    I used Gemini for this often. A prompt like "Give an example of using the .map method in JavaScript, explaining what it does and        showing a sample input and output."

10. Explaining code

    I used Gemini to help me understand complex code snippets. For example, I would copy a piece of code I didn't understand and use        the prompt: “Explain what the following JavaScript code does, line by line:
    "
    try {
            setLoading(true);
            const response = await api.notifications.getAll();
            const fetchedNotifications = Array.isArray(response.notifications) ? response.notifications : [];
            setNotifications(fetchedNotifications);
            setUnreadCount(fetchedNotifications.filter(n => !n.isRead).length);
    "
    This was extremely useful for deconstructing complex functions or methods and understanding their purpose.

11. Writing code

    I used Gemini for writing small, repetitive pieces of code or boilerplate. The benefit was saving time on tedious tasks. However,       the costs were significant. For example, I used Gemini to write me code on my component parts of my final project.

12. Documenting code

    This was a fantastic use of Gemini. I would copy a function I had written and use the prompt: “Write JSDoc comments for the             following JavaScript function:
    "
    try {
            setLoading(true);
            const response = await api.notifications.getAll();
            const fetchedNotifications = Array.isArray(response.notifications) ? response.notifications : [];
            setNotifications(fetchedNotifications);
            setUnreadCount(fetchedNotifications.filter(n => !n.isRead).length);
    "

13. Quality assurance

    I found Gemini to be very useful for this. A prompt like “Fix the ESLint errors in the following code: const yes = 1; (space)"          would often provide an immediate and correct solution.

14. Other uses in ICS 314 not listed

    I sometimes used Gemini to generate commit messages for my Git commits. A prompt like: 
    “
    Write a good commit message for the following changes: 
    const AnalyticsTab = () => (
        <div style={{ display: 'flex', flexDirection: 'column', gap: '1.5rem' }}>
          <h3 style={{ fontSize: '1.25rem', fontWeight: '600' }}>Platform Analytics</h3>
    ” 
    This was a minor but helpful use for maintaining good version control habits.

## Impact on Learning and Understanding

The incorporation of AI has had a mixed but ultimately positive impact on my learning experience. For example, when learning about asynchronous programming, I could get a concise analogy and a simple code example from Gemini, which was a great starting point for my understanding.

## Practical Applications

Outside of ICS 314, I've applied AI to a real-world project by developing a Personal Knowledge Tracker + Smart Note Recommender. This web application serves as a personal dashboard that tracks daily learning (notes, links, summaries) and then uses natural language processing (NLP) to suggest review items or related concepts, effectively functioning as my own AI-powered "second brain."

In addressing real-world software engineering challenges, this AI application has been highly effective. It automates the organization and retrieval of information, a common challenge in personal knowledge management. The intelligent recommendation system helps combat information overload and improves learning retention by prioritizing relevant content for review. This project demonstrates how AI can be leveraged to create personalized, adaptive tools that enhance productivity and learning beyond traditional methods.


## Challenges and Opportunities

A major challenge I faced was the potential for AI hallucinations. Gemini would sometimes provide confident but incorrect code or explanations, which was both misleading and frustrating to debug. Additionally, the code it generated was often generic and lacked context. It rarely followed the specific architectural patterns or style guides of a project, which meant I had to spend a lot of time manually refining it.


## Comparitive Analysis

Traditional teaching methods in software engineering, such as lectures, textbook readings, and manual coding assignments, focus heavily on building a fundamental, deep understanding of concepts from the ground up. This approach can be slow and sometimes less engaging, but it builds a strong foundation.

AI-enhanced approaches, by contrast, offer a more accelerated and personalized learning experience. AI tools can provide instant feedback, generate examples, and automate tedious tasks, which can boost engagement and make the learning process more efficient.


## Future Considerations

The future role of AI in software engineering education is likely to be one of deep integration and collaboration. AI will become less of a separate tool and more of an embedded feature within IDEs and learning platforms. I foresee an era of AI-powered learning assistants that can not only provide code but also act as intelligent tutors, guiding students through complex projects and offering personalized learning paths based on their progress. We must teach future software engineers to use AI responsibly and to understand its limitations, so they can harness its power without becoming dependent on it.


## Conclusion

My experience with AI in ICS 314 has shown me its immense potential as a powerful educational tool. It has been particularly effective for tasks like documenting code, explaining complex concepts, and generating boilerplate code, allowing me to focus on the more challenging and creative aspects of software engineering.

However, I've also learned the importance of balancing AI use with independent, critical thinking. Relying too heavily on AI can hinder the development of fundamental problem-solving skills. My main recommendation for future courses would be to formally integrate AI into the curriculum, not as a replacement for traditional methods, but as a supplementary tool.
