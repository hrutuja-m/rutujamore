import "./App.css";

const projects = [
  {
    title: "CareerCopilot AI — Multi-Agent Job Assistant",
    stack: ["Python", "OpenAI API", "FAISS", "FastAPI", "n8n", "NLP"],
    description:
      "Built an AI-powered job assistant that classifies job emails, extracts role details, detects duplicates, matches resumes with job descriptions, and supports personalized outreach workflows.",
    github: "https://github.com/hrutuja-m/career_copilot_ai",
  },
  {
    title: "Twitter US Airline Sentiment Analysis",
    stack: ["AWS S3", "AWS Glue", "PySpark", "Athena", "QuickSight", "SQL"],
    description:
      "Built a serverless big data pipeline to analyze 4,000+ airline tweets, clean unstructured text, optimize query performance using Parquet, and visualize sentiment trends in QuickSight.",
    github: "https://github.com/hrutuja-m",
  },
  {
    title: "Smart Space Occupancy Monitoring",
    stack: ["Python", "YOLOv8", "OpenCV", "Firestore", "Computer Vision"],
    description:
      "Developed a computer vision system to detect and count room occupancy for HVAC and lighting automation, supporting energy-efficient smart building operations.",
    github: "https://github.com/hrutuja-m",
  },
  {
    title: "LLM Voice-Based RAG Chatbot",
    stack: ["OpenAI Whisper", "Pinecone", "RAG", "Python", "TTS"],
    description:
      "Created a voice-enabled chatbot that transcribes questions, retrieves relevant context from Pinecone, generates grounded answers, and responds using text-to-speech.",
    github: "https://github.com/hrutuja-m",
  },
  {
    title: "Network Anomaly Detection",
    stack: ["Python", "Autoencoder", "One-Class SVM", "Scapy", "Wireshark"],
    description:
      "Built machine learning models using benign network traffic baselines to detect abnormal behavior in live packet captures.",
    github: "https://github.com/hrutuja-m",
  },
  {
    title: "Self-Driving Car Perception Model",
    stack: ["Python", "YOLOv3", "MATLAB", "Deep Learning", "Computer Vision"],
    description:
      "Developed an autonomous vehicle perception prototype for real-time object detection and pedestrian intent prediction using deep learning and simulation-based testing.",
    github: "https://github.com/hrutuja-m",
  },
];

const skills = [
  "Python",
  "SQL",
  "PySpark",
  "AWS S3",
  "AWS Glue",
  "Athena",
  "QuickSight",
  "Machine Learning",
  "Deep Learning",
  "Computer Vision",
  "OpenCV",
  "YOLO",
  "LLMs",
  "RAG",
  "Pinecone",
  "FastAPI",
  "Git",
  "Streamlit",
];

function App() {
  return (
    <main className="app">
      <div className="scroll-bg">
        <div className="blob blob-one"></div>
        <div className="blob blob-two"></div>
        <div className="blob blob-three"></div>
      </div>

      <nav className="nav">
        <a href="#home" className="logo">RM.</a>
        <div>
          <a href="#projects">Projects</a>
          <a href="#skills">Skills</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>

      <section id="home" className="hero">
        <p className="eyebrow">Data Science Graduate Student @ UMass Dartmouth</p>
        <h1>
          Hi, I’m <span>Rutuja More.</span>
        </h1>
        <h2>AI/ML Engineer · Data Builder · Automation Thinker</h2>
        <p className="hero-text">
          I build AI, data, and automation projects using Python, AWS, machine learning,
          computer vision, and LLM workflows — with a focus on practical systems that solve real problems.
        </p>

        <div className="hero-actions">
          <a href="#projects" className="btn primary">View Projects</a>
          <a href="https://github.com/hrutuja-m" target="_blank" rel="noreferrer" className="btn secondary">
            GitHub
          </a>
          <a href="https://www.linkedin.com/" target="_blank" rel="noreferrer" className="btn secondary">
            LinkedIn
          </a>
        </div>
      </section>

      <section id="projects" className="section">
        <div className="section-heading">
          <p className="eyebrow">Selected Work</p>
          <h2>Featured Projects</h2>
        </div>

        <div className="project-grid">
          {projects.map((project) => (
            <article className="project-card" key={project.title}>
              <h3>{project.title}</h3>
              <p>{project.description}</p>
              <div className="tags">
                {project.stack.map((item) => (
                  <span key={item}>{item}</span>
                ))}
              </div>
              <a href={project.github} target="_blank" rel="noreferrer" className="project-link">
                View Project →
              </a>
            </article>
          ))}
        </div>
      </section>

      <section id="skills" className="section">
        <div className="section-heading">
          <p className="eyebrow">Technical Stack</p>
          <h2>Skills</h2>
        </div>

        <div className="skills">
          {skills.map((skill) => (
            <span key={skill}>{skill}</span>
          ))}
        </div>
      </section>

      <section id="contact" className="section contact">
        <p className="eyebrow">Let’s Connect</p>
        <h2>Open to AI, Data Science, Data Engineering, and ML internship roles.</h2>
        <div className="hero-actions">
          <a href="mailto:your-email-here@example.com" className="btn primary">Email Me</a>
          <a href="https://github.com/hrutuja-m" target="_blank" rel="noreferrer" className="btn secondary">
            GitHub
          </a>
        </div>
      </section>
    </main>
  );
}

export default App;
