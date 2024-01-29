\documentclass[letterpaper,11pt]{article}
\usepackage{xcolor}
\definecolor{myColor1}{HTML}{3F00FF}
\definecolor{myColor2}{HTML}{180062}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
%\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}
\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]
\pdfgentounicode=1
%-------------------------
\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\classesList}[4]{\item\small{{#1 #2 #3 #4 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}
%-------------------------------------------
\begin{document}
\begin{center}
    {\Huge \scshape \textcolor{myColor1}{Ram Kadiyala}} \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ \textcolor{myColor2}{240-756-8427} ~ \href{mailto:rkadiyal@umd.edu}{\raisebox{-0.2\height}\faEnvelope\  \underline{\textcolor{myColor2}{rkadiyal@umd.edu}}} ~ 
    \href{https://linkedin.com/in/1024-m/}{\raisebox{-0.2\height}\faLinkedin\ \underline{\textcolor{myColor2}{linkedin.com/in/1024-m}}}  ~
    \href{https://github.com/1024-m}{\raisebox{-0.2\height}\faGithub\ \underline{\textcolor{myColor2}{github.com/1024-m}}} ~
    \href{http://rkadiyala.com}{\raisebox{-0.2\height}\faGlobe\ \underline{\textcolor{myColor2}{rkadiyala.com}}}
    \vspace{-10pt}
\end{center}
%-----------EDUCATION-----------
\section{\textcolor{myColor1}{Education}}
  \resumeSubHeadingListStart
    \resumeSubheading
      {\textcolor{myColor2}{University of Maryland , College Park}}{\textcolor{myColor2}{Aug 2022 -- May 2024}}
      {Masters in Machine Learning}{College Park, MD}\vspace{-4pt}
    \resumeSubheading
      {\textcolor{myColor2}{University of Maryland , College Park}}{\textcolor{myColor2}{Aug 2022 -- May 2023}}
      {Graduate Certificate in Data Science}{College Park, MD}\vspace{-4pt}
    \resumeSubheading
      {\textcolor{myColor2}{R.V.R \& J.C College of Engineering}}{\textcolor{myColor2}{Aug 2018 -- May 2022}}
      {Bachelors in Computer Science and Engineering}{Guntur, AP}\vspace{-4pt}
  \resumeSubHeadingListEnd
  \vspace{-15pt}
%------RELEVANT COURSEWORK-------
\section{\textcolor{myColor1}{Relevant Coursework}}
    %\resumeSubHeadingListStart
        \begin{multicols}{3}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Probability and Statistics
                \item Principles of Data Science
                \item Principles of Machine Learning
                \item Convex Optimization
                \item Data Interpretation and Modelling
                \item Algorithms in Machine Learning
                \item Natural Language Processing
                \item Cloud Computing
                \item Robotics
                \item Big Data Analytics
                \item Artificial Intelligence
                \item Computing Systems
                \item Data Engineering
                \item Software Engineering
                \item Social Networks
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
%-----------WORK EXPERIENCE-----------
%    \resumeSubheading
%      {Electronics Company}{May 2020 -- August 2020}
%      {Software Engineer Intern}{City, State}
\section{\textcolor{myColor1}{Work Experience}}
  \resumeSubHeadingListStart
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Research Assistant}} $|$ \emph{\textcolor{myColor2}{VVIT}} \hfill \textbf{\textcolor{myColor2}{Aug 2023 -- Dec 2023}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Assisting in a research project on end-to-end detection system of glaucoma by leveraging multiple datasets annotated by optometrists and other medical experts. My role involves data collection, pre-processing, and the development of machine learning models to identify optical disk and optical cup regions, aiding in the accurate diagnosis of glaucoma. This research aims to advance the field of ophthalmic diagnostics through data-driven methodologies.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Volunteer Intern}} $|$ \emph{\textcolor{myColor2}{Common Purpose}} \hfill \textbf{\textcolor{myColor2}{Dec 2022 -- Jan 2023}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Developed a scalable framework aimed at providing accessible and affordable education to underserved communities in underdeveloped regions, leveraging local resources and innovative delivery methods to bridge the educational divide.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Research Assistant}} $|$ \emph{\textcolor{myColor2}{RVR\&JC}} \hfill \textbf{\textcolor{myColor2}{Aug 2022 -- Dec 2022}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Assisted in data collection and building models for a Natural Language Processing project focused on bias detection in Telugu news articles from newspapers and websites. The ongoing research leverages NLP techniques to develop a classification model aimed at identifying and analyzing bias in regional media landscapes for usage in AI systems to understand reliability of each news source in each domain}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Full Stack Intern}} $|$ \emph{\textcolor{myColor2}{Wipro}} \hfill \textbf{\textcolor{myColor2}{Mar 2022 -- May 2022}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Worked on full-stack development of applications, gaining practical experience in the software development lifecycle.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{IoT \& ML Intern}} $|$ \emph{\textcolor{myColor2}{Bolt IOT}} \hfill \textbf{\textcolor{myColor2}{Feb 2021 -- Apr 2021}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Gained exposure to industrial IoT projects through hands-on experience with Arduino and hardware equipment. Contributed to smart humidity and temperature management project.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Founder and Mentor}} $|$ \emph{\textcolor{myColor2}{Black Ops Esports}} \hfill \textbf{\textcolor{myColor2}{Nov 2019 -- Feb 2022}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Established and led an Esports organization for 3 years, mentoring teams across 5 games, managing the social handles and finances.}\vspace{-4pt}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
%-----------TEACHING EXPERIENCE-----------
\section{\textcolor{myColor1}{Teaching Experience}}
  \resumeSubHeadingListStart
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Academic Tutor}} $|$ \emph{\textcolor{myColor2}{University of Maryland}} \hfill \textbf{\textcolor{myColor2}{Aug 2023 -- Present}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Tutoring undergrad students in the "Operating Systems (CMSC 412)" course. Helping students understand course materials and work through the course projects.}\vspace{-6pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Academic Tutor \& Mentor}} $|$ \emph{\textcolor{myColor2}{VHS}} \hfill \textbf{\textcolor{myColor2}{Aug 2011 -- Aug 2014}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Served as an academic tutor and mentor during school days, aiding juniors in preparation for math Olympiads.}\vspace{-6pt}
      \resumeItemListEnd
  \resumeSubHeadingListEnd
%-----------PROGRAMMING SKILLS-----------
\section{\textcolor{myColor1}{Technical Skills}}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\textcolor{myColor2}{Languages}}{: Python, C, HTML/CSS, JavaScript, SQL, R} \\
     \textbf{\textcolor{myColor2}{Cloud Platforms}}{: Google Cloud Platform, Amazon Web Services} \\
     \textbf{\textcolor{myColor2}{Editing / Creative}}{: PhotoshopCC , AlightMotion, AutoCAD, Figma, Google Sketchup} \\
     \textbf{\textcolor{myColor2}{Other}}{: Gradio, Folium, Squarespace, StableDiffusion, Prompt Engineering}
    }}
 \end{itemize}
 \vspace{-16pt}  
%-----------CERTIFICATIONS-----------
\section{\textcolor{myColor1}{Certifications}}
        \begin{multicols}{2}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small \textcolor{myColor2}{Accelrated Computing with CUDA} | \emph{Nvidia}
                \item \textcolor{myColor2}{Data Analytics Specialization} | \emph{Google}
                \item \textcolor{myColor2}{AWS Cloud essentials} | \emph{Amazon}
                \item \textcolor{myColor2}{MTA Python} | \emph{Microsoft}
                \item \textcolor{myColor2}{Project management} | \emph{CBRE}
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep} 
%-----------PUBLICATIONS-----------
\section{\textcolor{myColor1}{Publications}}
  \resumeSubHeadingListStart
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{RoBERTa-Based Emotion Classification of Essays}} \hfill\textbf{\textcolor{myColor2}{ACL 2023}}\\
      \emph{\textcolor{myColor2}{Tensorflow, Transformers, Google Cloud}} \hfill\emph{\textcolor{myColor2}{Published}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Collaborative research for the WASSA 2023 event, part of the ACL 2023 conference. Devised a solution for detecting multi-class emotions from user essays on highly imbalanced data using a model based on RoBERTa large.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Black-Box Monolingual Machine-Generated Text Detection}} \hfill\textbf{\textcolor{myColor2}{NAACL 2024}}\\
      \emph{\textcolor{myColor2}{PyTorch, Transformers, AWS}}\hfill\emph{\textcolor{myColor2}{In a Publishable state}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Developing models to detect machine generated text using M4 dataset, by training on a set of domains and generators and testing on unseen domains and generators, the aim is to build widely applicable models for real world scenarios.}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Multilingual Black-Box Machine Generated Text Detection}} \hfill\textbf{\textcolor{myColor2}{NAACL 2024}}\\
      \emph{\textcolor{myColor2}{PyTorch, Transformers, AWS}}\hfill\emph{\textcolor{myColor2}{In a Publishable state}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Expanding the black-box detection techniques to work effectively across multiple languages. By training on a few languages and testing on unseen languages , the aim is to build a model applicable to even less popular languages}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Multi-Way Machine Generated Text Classification}} \hfill\textbf{\textcolor{myColor2}{NAACL 2024}}\\
      \emph{\textcolor{myColor2}{Scipy, Spark, Transformers, AWS}}\hfill\emph{\textcolor{myColor2}{In a Publishable state}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Developing models to classify the given text as human written or what LLM was used to generate it. Extendable to differentiating writing styles of multiple sources}\vspace{-4pt}
      \resumeItemListEnd
    \resumeSubItem
      {\textbf{\textcolor{myColor2}{Text Boundary Identification in Mixed Texts}} \hfill\textbf{\textcolor{myColor2}{NAACL 2024}}\\
      \emph{\textcolor{myColor2}{Pytorch, CRF, Transformers, Google Cloud}}\hfill\emph{\textcolor{myColor2}{In a Publishable state}}}\vspace{-3pt}
      \resumeItemListStart
        \resumeItem{Developing models to identify text boundary in mixed texts where a part is human written and rest is machine generated. While existing work does this on a sentence level , the current model does it at a word level with a better accuracy than existing proprietary systems like GPTZero, ZeroGPT, etc..}\vspace{-4pt}
      \resumeItemListEnd
  \resumeSubHeadingListEnd  
%-----------PROJECTS-----------
\section{\textcolor{myColor1}{Other Projects}}
    \vspace{-8pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{\textcolor{myColor2}{Tuneable Generative Image AI}} $|$ \emph{\textcolor{myColor2}{PyTorch, Gradio, StableDiffusion, LoRA, Google Cloud Console}}}{}\vspace{-15pt}
          \resumeItemListStart
            \resumeItem{Developed an Generative image AI model for creative purposes without any censorship and limitations, using LoRA for better learning with fewer data items of each type along with StableDiffusion, Gradio for interface and GCP notebooks to build the models and test them.}\vspace{-6pt}
          \resumeItemListEnd
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{\textcolor{myColor2}{Power Outage Forecasting}} $|$ \emph{\textcolor{myColor2}{RestAPI, FbProphet, Google Cloud, Anvil}}}{}\vspace{-15pt}
          \resumeItemListStart
            \resumeItem{Created a fullstack application that updates daily with forcasted power outages for the next 7 days using meta's opensourced fbprophet model using RestAPI for accessing daily data and Anvil for the front end integration}\vspace{-6pt}
          \resumeItemListEnd 
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{\textcolor{myColor2}{Autonomous lunar lander}} $|$ \emph{\textcolor{myColor2}{DQN, Pygame, OpenAI Gym, Box2D, PyTorch}}}{}\vspace{-15pt}
          \resumeItemListStart
            \resumeItem{Implemented a lunar lander that accounts for miscalculation by working for random starting point in the landing environment along with factors like varying landing spot, wind, etc..}\vspace{-6pt}
          \resumeItemListEnd 
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{\textcolor{myColor2}{Image/Video to Aristic Image/GIF Converter}} $|$ \emph{\textcolor{myColor2}{CLIP, PixRay, Scipy, Pygame, PyTorch}}}{}\vspace{-15pt}
          \resumeItemListStart
            \resumeItem{Implemented models that converts given Images to Image and Videos to GIF in the form of low poly art or animated pixel art. Incase of videos, chosen number of unique colors are chosen and each frame as a image is induvidually converted before stiching together as a GIF.}\vspace{-6pt}
          \resumeItemListEnd     
    \resumeSubHeadingListEnd
\vspace{-13pt}
%-----------CO-CURRICULAR ACHIEVEMENTS-----------
\section{\textcolor{myColor1}{Co-Curricular Achievements}}
  \resumeSubHeadingListStart
    \resumeItem{\textbf{\textcolor{myColor2}{WASSA 2023 EMO}}: Top performing team, published work in ACL,\hfill May 2023}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{GATE 2022 CS}}: Rank 2301 out of over 100K, \hfill Feb 2022}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{GATE 2022 MATH}}: Rank 688 out of over 100K, \hfill Feb 2022}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{JEE MAINS}}: Rank 233 out of over 120K, \hfill Mar 2018}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{IMO 2012}}: Rank 110 out of over 650K, \hfill Dec 2012}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{BIOS 2013}}: Rank 333 out of over 140K, \hfill Nov 2013}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{BIOM 2013}}: Rank 30 out of over 170K, \hfill Nov 2013}\vspace{-4pt}
    \resumeItem{\textbf{\textcolor{myColor2}{IMO 2015}}: Rank 283 out of over 700K, \hfill Dec 2015}\vspace{-4pt}
    \resumeItem{Additional Achievements: Won several more medals in National \& International Math \& Science Olympiads, got featured in local newspapers 18 times during school days.}\vspace{-4pt}
  \resumeSubHeadingListEnd
\end{document}
