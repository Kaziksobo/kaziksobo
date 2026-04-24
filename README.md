## Hi there, I'm Kazik Sobotnicki

I am a student at **Birkbeck, University of London**, currently working toward my BSc in Data Science and Computing. I am in the second year of a roughly three-and-a-half-year course, with plans to finish my final two modules in my fourth year and graduate in the summer of 2028. My academic trajectory is focused heavily on research; following my undergraduate degree, I intend to complete a Master's program and eventually push into PhD-level research.

My primary technical interest lies in machine learning, specifically working with transformer models using **PyTorch** and **TensorFlow**. Rather than just implementing existing libraries, I spend a significant amount of time studying the underlying mathematics that make these models function. I focus heavily on linear algebra, general calculus, probability, statistics, and optimization algorithms. Alongside this, I have a deep interest in Natural Language Processing. To support my NLP work, I have been reading extensively about linguistics, aiming to build a solid theoretical understanding of language structure before applying it programmatically.

### Current Project: Gaffer's Clipboard
My primary development focus right now is **Gaffer's Clipboard**, a high-fidelity desktop companion application I am building for EA FC/FIFA Career Mode. As an avid football fan who enjoys highly realistic, in-depth sports simulations, I needed a robust way to handle the underlying data across long-term saves, store the data and then analyse it. 
To achieve this without tedious manual data entry, I developed a custom **OpenCV K-Nearest Neighbors (KNN)** OCR engine. This lightweight computer vision pipeline dynamically scales to different display resolutions and extracts team-level and specific player-level stats directly from screenshots in seconds, bypassing the need for heavy ML frameworks. 

I am currently building out the analytics engine for this data, implementing several advanced techniques:
* **Custom Match Ratings:** Utilizing a Principal Component Analysis (PCA) algorithm to assign weights to pre-processed stats, feeding into a weighted heuristic formula for transparent player ratings.
* **Form Scores:** Applying an Exponential Moving Average formula to the custom match ratings to track player momentum over time.
* **Win Condition Extraction:** Training a Random Forest model to identify key victory drivers through the model's feature importances.
* **Match & Opponent Grouping:** Utilizing K-means clustering to segment and analyze different types of fixtures.

The project acts as a practical bridge to my data science studies, heavily relying on rigorous data validation and architectural design. Once the raw pixels are extracted, the data is passed through strict **Pydantic V2** models to ensure every piece of extracted information is mathematically and logically sound before being committed to a JSON-backed local database. The application itself is built on **Python 3.13+** using a strict, interface-driven MVC architecture that completely decouples the modern **customtkinter** frontend from the data management and OCR services. It makes rigorous use of strict linting and type checking through **Ruff** and **Ty**.

### Focus Areas and What I Am Learning
Through my degree, I am currently working on understanding the mathematics behind machine learning algorithms. This includes studying optimization algorithms, probability distributions, statistical testing, and singular-value decomposition. These concepts help me understand machine learning model behavior on a fundamental level, instead of just treating them as black boxes.

Alongside this, I am expanding my knowledge in Natural Language Processing—a field I have been interested in since my A-levels. While I have solid practical knowledge of programmatic implementation (using transformers, analysis through Python modules like NLTK, and search algorithms like beam search), the theoretical linguistics side is less natively familiar to me. To bridge this gap, I am currently studying texts such as *The Linguistics Student's Handbook* by Laurie Bauer and *Quantitative Research in Linguistics* by Sebastian M. Rasinger. This helps me build a stronger foundation for how language structure translates into machine learning applications, balancing strict mathematical optimization with the nuanced rules of human language.

### What I am eager to discuss
As a part of my ongoing project and my wider interest in sports analytics, I am always open to conversations around how sports data can be modeled and how industry-standard analyses work. I am also highly receptive to ideas for new projects, specifically those involving mathematical optimization problems or practical applications of linguistics and NLP.

### Contact Me
If you have questions about any of my current projects, want to chat about any of the topics above, or anything else, you can reach out to me via:
* **Email**: Kaziksobo@outlook.com
* **LinkedIn**: https://www.linkedin.com/in/kazik-sobotnicki/
