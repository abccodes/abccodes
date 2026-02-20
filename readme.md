#### Interests
My interests span Machine Learning, Software Engineering, Data Engineering, and Distributed Systems.

#### How I've Been Spending My Time
##### Winter 2026
- Working as a research assistant focusing on optimizing VLA models in Autonomous Driving using edge LLM optimization techniques such as quantization.
- Relevant Courses:
    - Graduate Big Data Systems
    - Graduate Reinforcement Learning

##### Fall 2025
- I started a Master's in Computer Science at [UCLA](https://www.cs.ucla.edu/)!
- Working as a grader for the upper-division course: Design and Use of Programming Languages. 
- Attended Calhacks, UC Berkeley's Hackathon. 
- Relevant Courses:
    - Graduate LLM Inference on Edge Devices. Relevant topics: LLM model compression (quantization, pruning, distillation), long-context inference (KV cache compression, state-space models, hierarchical memory transformers), and energy-efficient architectures such as sparse, linear, and flash attention, Mixture-of-Experts (MoE), speculative decoding, and hardware–software co-design for edge deployment.
    - Graduate Software Engineering. Relevant topics: automated software engineering techniques such as program differencing, code search, automated testing, and fuzzing (greybox, grammar-based, and stateful). Explored symbolic execution, statistical testing, debugging, and fault localization, with a focus on program representations like Abstract Syntax Trees (ASTs) and Control Flow Graphs (CFGs). Gained experience with AFL++, LLVM/LLVM-IR, Gramminator, and Evomaster for software analysis, automation, and fault detection.
          - [Fuzzing Project](https://github.com/abccodes/cs230): Implementations of selective coverage feedback suppression strategies built on AFL++, exploring whether full coverage guidance is necessary throughout an entire fuzzing campaign. We implement and evaluate two approaches: a stochastic method (LCF-S) that probabilistically suppresses coverage feedback on individual executions, and a temporal method (LCF-T) that disables feedback after a predefined point in time.
          - [LLM Edge Inference Project](https://github.com/abccodes/snapdragon-llm-edge): Exploration and evaluation of efficient large language model (LLM) inference on the Samsung S25+ edge device. Investigated system-level and model-level optimizations—including quantization strategies, KV-cache configurations, flash attention, hyperparameters (batch size, KV-Cache Size, Temperature etc.) and sliding window + attention sinks to examine trade-offs between throughput, accuracy, and energy efficiency under real deployment constraints using Llamabench, Longbench, and TruthfulQA as evaluation metrics.

##### Summer 2025
- I am interning as a Software Engineer at [Genentech](https://www.gene.com/).

##### Spring 2025
- Graduated from San Francisco State University with a B.S. in Computer Science and minor in Computing Applications!
- Instructional Teaching Assistant for Data Structures for Data Science Application Development.
- Collaborated with UCLA Design Media Arts to develop [Chat Wrapped](https://github.com/abccodes/gpt-wrapped).
- Relevant Courses:
    - Operating Systems. Relevant topics: Processes and threads, synchronization, CPU and memory management, file systems, device drivers, and real-time vs. multi-tasking systems. [Projects](https://github.com/abccodes/os-projects/tree/master):
        - File System: Working in a small team, I contributed to building a simple filesystem in C, implementing free-space tracking, core data structures, and directory initialization. We coordinated module boundaries and tested the full system together.
        - Device Driver: I built a Linux character device driver that performs Caesar-cipher encryption and decryption via standard read/write and ioctl calls. The module registers /dev/main, maintains an internal buffer, and allows users to change the shift and mode at runtime.
        - Buffered I/O Read: I implemented a custom buffered I/O system that reads files in fixed-size 512-byte blocks and manages its own internal buffer to reduce disk accesses. The project involved designing a file control block, implementing b_open, b_read, and b_close, and correctly handling block transitions, end-of-file conditions, and manual buffer management.
        - Multi-Threaded Data Processing: I wrote a multithreaded C program that parses fixed-length emergency event records (using a header-defined schema) and computes response-time statistics by event type and area. It uses pthreads, mutexes, batch file reads, and timestamp parsing to aggregate metrics and compare performance across different thread counts.
        - Shell with Pipes: I implemented a simple C shell that reads user input, tokenizes commands, and executes them using fork, execvp, and waitpid. It supports multi-stage pipelines with |, sets up pipes with dup2, and handles errors, EOF, and an exit command to terminate the shell.
    - Graduate Human Computer Interaction. Relevant topics: User-centered design, research methods, prototyping, and evaluation of usability.

##### Fall 2024
- Instructional teaching assistant for the courses an Interdisciplinary Approach to Computer Programming and Machine Learning and Data Science.
- Relevant Courses:
    - Database Systems: Studied relational database design and implementation, including ER/EER modeling, SQL, normalization, indexing, query optimization, transactions, and Java/JDBC integration.
        - Designed a social media relational SQL database with 50 entities covering users, posts, chats, and ads, incorporating performance, backup, and AES-256 security standards.
    - Software Engineering. Final Project:
        - [Review Platform](https://github.com/abccodes/review_platform): A full-stack web application for review, discovery, and exploration of game recommendations
    - Analysis of Algorithms. Relevant topics: Algorithm design and analysis, time and space complexity, recursion, divide and conquer, backtracking, dynamic programming, greedy algorithms, and graph algorithms.
    - Graduate Artificial Intelligence. Relevant topics: Artificial intelligence fundamentals, problem-solving methods, heuristic search, game playing, agent architectures, machine learning, knowledge representation, and neural networks.

##### Summer 2024
- I am working as a Machine Learning Clinical Imaging Intern at [Genentech](https://www.gene.com/)

##### Spring 2024
- I attended Treehacks, Stanfords hackathon. Me and my team built an [AI dermatologist platform](https://github.com/abccodes/Treehacks2024). Won first hackathon, 2nd for a prize track (Convex).
- Won 2nd place at San Francisco State Universty, [College of Computer Science and Engineering (COSE)](https://cose.sfsu.edu/student-project-showcase) annual research competition. Created a semantic segmentation algorithm for land cover using satellite imagery. 
- Relevant Courses:
    - Software Development. Relevant Topics: Modern software applications, object-oriented programming (encapsulation, inheritance, polymorphism), software design, debugging, testing, user interface design, and software maintenance.
    - Data Science for Image Analysis. Relevant Topics: Medical imaging, deep learning for image classification and segmentation, CNNs, transfer learning, model evaluation, loss functions, performance metrics, and hands-on ML implementation.
    - Software Engineering Ethics

##### 2023
- Recieved year-long [Genentech scholarship](https://pinc.sfsu.edu/GEN-PINC%20Scholarship%20Winners%202023-2024).
- Open-Source Internship at [Codeday](https://www.codeday.org/). Contributed to [The Open Energy Dashboard](https://github.com/OpenEnergyDashboard/OED).
- Attended hackathons at Stanford, Berkeley, and UCLA.
- Created a platform for an education business which connected students and tutors. Worked with databases, cloud functions, authentication, and storage using TypeScript and Firebase.
- Relevant Courses:
    - Machine Learning. Relevant topics: Supervised machine learning (decision trees, random forests, gradient-boosted trees, logistic regression, deep learning), model evaluation (accuracy, recall, Gini index, hyperparameter tuning), data preprocessing (one-hot encoding, handling missing data, feature engineering), Python implementation with pandas, matplotlib/plotnine, data visualization, and clustering.
    - Linear Algebra. Relevant topics: Solving linear systems, matrix operations, vector spaces, eigenvalues/eigenvectors, orthogonality and orthogonalization.
    - Probability and Statistics. Relevant topics: Data analysis, probability distributions, confidence intervals.
    - Programming Methodology. Went over advanced C++ data structures and algorithms.
    - Machine Structures. Relevant Topics: Fundamentals of digital logic, data representation, assembly programming, CPU organization, memory systems, and handling interrupts.
    - Software Web Development. Relevant topics: Client/server programming, user input processing, database integration, and building web applications.
    - Physics 2. Relevant topics: Electricity and magnetism, covering electric and magnetic fields, circuits (DC and AC), electromagnetic induction, waves, and Maxwell’s equations.

##### 2022
- My first Software Engineering Internship at a Web3 social media startup called Huddln.
- Attended every San Francisco blockchain developers club meeting in the city.
- Worked as a Software Engineer freelancer. The main project I worked on was full-stack development of a decentralized investment (DAO) platform. Relevant technology: Solidity, Firebase, React, and JavaScript.
- Relevant Courses:
    - Data Structures and Algorithms. Relevant topics: Lists, stacks, queues, trees, heaps, graphs, recursion, iteration, hash tables, and Big O analysis.
    - Discrete Mathmatics. Relevant topics: Fundamentals of set theory, logic, functions, permutations, proof techniques, graph theory, and infinite sets with applications in computer science.
    - Calculus 2. Relevant topics: Integration, analytic geometry, polar coordinates, vectors, improper integrals, and sequences and series.

##### 2021
- Started my B.S. in Computer Science at [San Francisco State University](https://www.sfsu.edu/)!
- Learned Javascript from online bootcamp.
- Did my first ever hackathon and created a recipe sharing app.



