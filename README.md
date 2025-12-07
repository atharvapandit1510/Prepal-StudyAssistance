🎓 PrepPal - AI-Powered Smart Study Assistant

PrepPal is an intelligent web platform designed to streamline exam preparation for students. It takes raw study materials—like scanned question papers or PDFs—and uses Artificial Intelligence to extract text, identify key topics, and provide a personalized AI tutor that understands the context of your specific documents.

<!-- Ideally, add a screenshot here later -->

🚀 Key Features

1. 📄 Smart Document Processing: Upload multiple question papers (PDF, JPG, PNG). The system automatically digitizes them using OCR.

2. 🔍 Trending Topic Analysis: Advanced NLP algorithms analyze years of question papers to identify "Trending Topics"—concepts that appear most frequently.

2. 🤖 Context-Aware AI Chat: A built-in chatbot (powered by Google Gemini 1.5 Pro) that "reads" your uploaded documents. You can ask it to summarize papers, explain specific questions, or generate new practice problems based on your syllabus.

4. 📝 Question Extraction: Automatically identifies and separates individual questions from unstructured text.

5. 🔐 User Dashboard: Secure authentication, profile management, and a history log of all analyzed documents.


🛠️ Tech Stack

Frontend:

• EJS (Embedded JavaScript): Server-side rendering for fast initial load and SEO.

• CSS3 & JavaScript: Custom styling with a responsive, mobile-friendly UI.

• AJAX (Fetch API): For seamless, no-reload interactions in the AI Chat.

Backend:

• Node.js & Express.js: Main application server handling routing, auth, and API orchestration.

• MongoDB (Mongoose): NoSQL database for flexible storage of document metadata, extracted text, and chat history.

• Passport.js: For secure user authentication.

AI & Microservices:

• Python (Flask): A dedicated microservice for heavy computational tasks.

• Tesseract OCR: For extracting text from images and scanned PDFs.

• KeyBERT & Scikit-learn: For keyword extraction and topic modeling.

• Google Gemini API: For the generative AI chatbot and summarization logic.

Storage:

• Cloudinary: Cloud storage for hosting user-uploaded files.
