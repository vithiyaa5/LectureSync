# LectureSync
Automated Quiz & Study Note Generator
Turn any lecture video into smart notes & instant quizzes — in minutes.

 What is LectureSync?

LectureSync is an AI-powered educational tool that automatically converts lecture videos into:

 Concise study notes (PDF)

 Auto-generated quizzes (10 questions)

Designed for teachers, students, and ed-tech platforms, LectureSync removes the manual effort of summarizing lectures and creating assessments.

 Why LectureSync is Innovative

🔹 Upload a video or YouTube link
🔹 AI listens, understands, and extracts concepts
🔹 Generates structured notes + topic-specific quizzes
🔹 Fully automated — zero manual work

From a 1-hour lecture to revision-ready content in under 2 minutes.

 How It Works (AI Pipeline)
Lecture Video / YouTube Link
        ↓
Audio Extraction (PyTube)
        ↓
Speech-to-Text (OpenAI Whisper)
        ↓
Concept Identification (LangChain)
        ↓
LLM Processing (GPT-4o Mini / Llama 3)
        ↓
 PDF Study Notes +  Interactive Quiz
 Features

✅ Upload MP4 files or YouTube links
✅ Accurate speech-to-text transcription
✅ AI-powered key concept detection
✅ Summarized PDF notes for revision
✅ 10-question quiz (MCQs / short answers)
✅ Clean & simple Streamlit UI

 Tech Stack
 Audio Processing

OpenAI Whisper – Industry-standard speech-to-text

 Logic & AI Orchestration

LangChain – Prompt chaining & structured outputs

 Language Models

GPT-4o Mini / Llama 3 – Cost-effective & fast

 Frontend

Streamlit – Rapid UI development

 Libraries

PyTube – YouTube audio extraction

FPDF / ReportLab – PDF generation

 Project Structure
LectureSync/
│
├── app.py                 # Streamlit main app
├── transcription.py       # Whisper-based transcription
├── concept_extractor.py   # Key concept identification
├── quiz_generator.py      # AI quiz generation
├── pdf_generator.py       # Study notes PDF creator
├── requirements.txt       # Dependencies
├── README.md              # Project documentation
└── assets/                # Screenshots / demo files

 Demo Flow

1️⃣ Upload a lecture video or paste a YouTube link
2️⃣ Click Generate Content
3️⃣ Download PDF notes
4️⃣ Attempt the AI-generated quiz instantly

 Use Cases

 Teachers – Save hours of preparation time
 Students – Faster revision & self-testing
 Ed-Tech Platforms – Auto content generation

 Future Enhancements

 Bloom’s taxonomy-based quizzes
 Multi-language lecture support
 Difficulty-level quiz selection
 LMS integration (Moodle / Google Classroom)

🤝 Contributing

Pull requests are welcome! Feel free to fork and improve LectureSync.
