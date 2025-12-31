# AI-Email-Generator
Developed a Chrome extension that integrates seamlessly with Gmail to generate AI-powered email replies using the Google Gemini API. The extension detects Gmail compose windows in real time using a MutationObserver and injects an “AI Reply” button into the Gmail toolbar.

When the button is clicked, the extension extracts the email content from the current thread and sends it to a Spring Boot REST API along with the selected tone (professional, casual, or friendly). The backend formats the request according to the Gemini API schema, sends it to Gemini for content generation, extracts the AI-generated text from the response, and returns it as plain text.

The generated reply is then automatically inserted into the Gmail compose box, enabling users to draft high-quality responses instantly without leaving Gmail.

This project demonstrates hands-on experience with Chrome Extension development, Gmail DOM manipulation, JavaScript, Spring Boot REST APIs, Gemini API integration, and end-to-end frontend–backend communication.
