---
layout: home
---

## Hi, I'm Ann Xiao 👋🏼

##### [-> Download Résumé](/assets/resume.pdf)

I recently completed my M.S. in Computer Science at NYU (2025) and hold a B.S. in Computer Science & Data Science from UW–Madison (2023).

My interests span systems programming, databases, parallel computing, and applied AI. I’ve built projects ranging from a Unix shell and distributed transaction manager to GPU performance prediction and visual language model distillation.

I’m a self-motivated engineer who enjoys tackling complex problems, learning new technologies quickly, and collaborating across teams to deliver impactful solutions.

I’m actively seeking new graduate Software Engineer opportunities to apply my skills and grow as an engineer, and avilable to start immediately. Please see some of my featured projects below!

---

## 🔸 Certifications

| ---------------------------------------------------------- | ------------ |
| CodePath Advanced Software Engineering                     | Jun–Aug 2022 |
| AWS Machine Learning Foundations                           | Jun–Aug 2022 |
| Google UX Design Professional                              | Jul–Aug 2024 |

---

## 🔸 Featured Projects

### Systems

> #### <span class="project-title">Distributed Transaction Management System</span> &nbsp;&nbsp;&nbsp;[🔗](https://gist.github.com/AX1ao/ccfd0601fe7435405b9a55e4f97dc6f7)
> - Replicated DB system with transaction lifecycle management (begin, read, write, commit).  
> - Concurrency control with cycle detection for consistency.  
> - Fault-tolerance via site failure simulation + automated recovery.  

> #### <span class="project-title">System Programming</span> &nbsp;&nbsp;&nbsp;[🔗](https://gist.github.com/AX1ao/cb1b9134f032f88e0f610145aa6f8649)
> - Unix shell with job control, I/O redirection, and multi-pipe support.  
> - Multithreaded run-length encoder with thread pool + synchronization.  
> - FAT32-like filesystem with recovery tools.  

> #### <span class="project-title">Comparing OpenMP and Rust</span> &nbsp;&nbsp;&nbsp;[🔗](https://github.com/AX1ao/OpenMPnRust)
> - Benchmarked 9 workloads on 64-core machine.  
> - OpenMP excelled in compute-heavy loops; Rust (Rayon) scaled better for irregular tasks.  
> - Analyzed tradeoffs between low-level performance and safety/maintainability.  

> #### <span class="project-title">Parallel 2-Opt for TSP</span> &nbsp;&nbsp;&nbsp;[🔗](https://github.com/AX1ao/TSP_2OPT_Parallelism)
> - Implemented sequential, batched, multithreaded, and GA-hybrid heuristics in Rust.  
> - Benchmarked TSP instances up to 10k cities.  
> - Found GA+2-opt most effective for large cases.  

### AI / Machine Learning

> #### <span class="project-title">Predicting CUDA Kernel Performance</span> &nbsp;&nbsp;&nbsp;[📄](/assets/PredictingCUDAKernelPerformance.pdf)
> - Profiled 11 CUDA kernels, analyzed CGMA ratio, shared memory, and occupancy.  
> - Trained Random Forest regressor (R² = 0.93) to predict kernel speedups without profiling.  
> - Reduced profiling overhead for memory-bound GPU applications.  

> #### <span class="project-title">Visual Language Model Distillation</span> &nbsp;&nbsp;&nbsp;[📄](/assets/VisualLanguageModelDistillation.pdf)
> - Designed six distillation strategies for CLIP, BLIP, DINO, and BEiT.  
> - Ran large-scale experiments (Tiny ImageNet, MS COCO).  
> - Produced lightweight student models with strong accuracy–efficiency tradeoffs.  

> #### <span class="project-title">Structured Reasoning in VLMs</span> &nbsp;&nbsp;&nbsp;[🔗](https://github.com/AX1ao/ExplainIt)
> - Evaluated Chain-of-Thought prompting formats on chemistry reasoning tasks.  
> - Benchmarked three VLMs, showing Explanation-first/Stepwise prompts improved accuracy.  
> - Demonstrated prompt-task alignment as key for interpretability.  

> #### <span class="project-title">Cancer–Dementia Association Analysis</span> &nbsp;&nbsp;&nbsp;[📄](/assets/CancerDementiaAssociationAnalysis.pdf)
> - Processed 120k+ CDC records (2019–2022) for dementia risk analysis.  
> - Applied tree-based ML models, key predictors: age, depression, diabetes.  
> - Improved precision from 0.07 → 0.30 and recall to 0.47 with SMOTE + undersampling.  

### Data Analysis

> #### <span class="project-title">Web A/B Testing Platform</span>
> - Flask-based app with e-commerce flows (homepage, browse, donate, signup).  
> - Deployed variants to test UI changes on conversions.  
> - Built logging + chi-square significance testing pipeline.  

> #### <span class="project-title">Geographic Loan Data Analysis</span>
> - Processed mortgage loan data with Python + SQLite.  
> - Designed BST index for fast queries on interest rates & profiles.  
> - Generated demographic + financial insights via visualizations.  

### Applications

> #### <span class="project-title">Student Assistant Platform</span>
> - Full-stack platform (Vue.js + Spring Boot + Redis) serving 3,000+ students.  
> - Implemented caching + performance optimizations.  
> - Delivered reliable workflows for student operations.  

> #### <span class="project-title">Unity 2D Platformer</span> &nbsp;&nbsp;&nbsp;[🔗](https://ax1ao.github.io/TileVania_demo/)
> - Built 2D platformer with physics (gravity, friction) and level design.  
> - Implemented enemy AI + collision detection in C#.  
> - Improved responsiveness and gameplay balance.  
