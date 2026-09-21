\documentclass[10.5pt,letterpaper]{article}

% ---------- Packages ----------
\usepackage[left=0.65in,right=0.65in,top=0.5in,bottom=0.5in]{geometry}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{tabularx}
\usepackage[T1]{fontenc}

% ---------- Colors ----------
\definecolor{navy}{HTML}{000000}
\definecolor{gray}{HTML}{595959}
\definecolor{lightline}{HTML}{BFBFBF}

% ---------- Hyperlinks ----------
\hypersetup{colorlinks=true, urlcolor=navy, linkcolor=navy}

% ---------- Section formatting ----------
\titleformat{\section}
  {\large\bfseries\color{navy}}
  {}{0em}{}
  [{\color{navy}\titlerule[1.1pt]}]
\titlespacing*{\section}{0pt}{10pt}{6pt}

% ---------- Custom commands ----------
\newcommand{\resumeEntry}[2]{%
  \noindent\textbf{#1} \hfill \textit{\color{gray}#2}\par
}
\newcommand{\resumeSub}[1]{%
  \noindent\textit{\color{gray}#1}\par\vspace{2pt}
}

\newlist{resumeItems}{itemize}{1}
\setlist[resumeItems]{leftmargin=16pt, topsep=2pt, itemsep=1pt, parsep=0pt, label=\textbullet}

\pagestyle{empty}
\setlength{\parindent}{0pt}

\begin{document}

% ---------- Header ----------
\begin{center}
  {\fontsize{22}{24}\selectfont\bfseries\color{navy} AYUSH KUMAR}\\[4pt]
  {\large\color{gray} Aspiring Data Analyst \ $|$ \ Python \& SQL}\\[4pt]
  {\small\color{gray}
    Bengaluru, Karnataka, India \ $|$ \ [phone number] \ $|$ \
    \href{mailto:ayushkumar1248@gmail.com}{ayushkumar1248@gmail.com} \ $|$ \
    \href{https://linkedin.com/in/yourname}{linkedin.com/in/yourname} \ $|$ \
    \href{https://github.com/yourusername}{github.com/yourusername}
  }
\end{center}
\vspace{-4pt}
{\color{lightline}\hrule height 0.8pt}
\vspace{2pt}

% ---------- Professional Summary ----------
\section{Professional Summary}
Electronics and Communication Engineering graduate transitioning into data analysis, with a solid foundation in Python, SQL, and relational database design built through hands-on backend development. Experienced in structuring and querying MySQL databases, modeling relationships between entities (customers, leads, employees, tasks), and building applications that turn raw data into organized, actionable systems. Comfortable moving between writing queries, cleaning data, and building the logic that acts on it.

% ---------- Skills ----------
\section{Skills}
\textbf{Languages:} Python, SQL\\
\textbf{Databases:} MySQL, Django ORM, relational database design \& normalization\\
\textbf{Frameworks \& Tools:} Django, Django REST Framework (in progress), Git/GitHub\\
\textbf{Web:} HTML, CSS, Bootstrap\\
\textbf{Data Analysis Tools:} [Add any Excel, Power BI, Tableau, pandas, or NumPy experience you have --- these are commonly expected for analyst roles and worth building if you haven't yet]

% ---------- Education ----------
\section{Education}
\resumeEntry{B.E./B.Tech, Electronics and Communication Engineering --- [University Name]}{[Month Year]}
\begin{resumeItems}
  \item {[}Add relevant coursework if applicable, e.g. Statistics, Data Structures, Database Management Systems{]}
\end{resumeItems}

% ---------- Projects ----------
\section{Projects}

\resumeEntry{CRM Management System}{[Month Year]}
\begin{resumeItems}
  \item Designed a normalized MySQL schema to manage customer and lead data, supporting structured querying and reporting.
  \item Built Django-based user authentication and role-based authorization to control access to customer records.
  \item Developed a Bootstrap front end for viewing and managing customer/lead data.
  \item Link: \href{https://github.com/yourusername/project}{github.com/yourusername/project}
\end{resumeItems}

\vspace{4pt}
\resumeEntry{Employee Leave Management System}{[Month Year]}
\begin{resumeItems}
  \item Modeled an employee leave-approval workflow in MySQL, tracking request status and approval history end-to-end.
  \item Implemented role-based access (employee/manager/admin) using Django ORM to control who could view or approve records.
  \item Link: \href{https://github.com/yourusername/project}{github.com/yourusername/project}
\end{resumeItems}

\vspace{4pt}
\resumeEntry{Task Management System}{[Month Year]}
\begin{resumeItems}
  \item Built a task-tracking application with full CRUD operations and status tracking (To Do / In Progress / Done) backed by a MySQL database.
  \item Implemented authentication so task data stayed scoped to the correct user.
  \item Link: \href{https://github.com/yourusername/project}{github.com/yourusername/project}
\end{resumeItems}

% ---------- Achievements & Leadership ----------
\section{Achievements \& Leadership}
\begin{resumeItems}
  \item \textbf{Winner} --- College Quiz Competition
  \item \textbf{Runner-up} --- College Debugging Competition
  \item \textbf{Coordinator} --- Managed and coordinated an online parliamentary debate competition, handling logistics and cross-team communication
\end{resumeItems}

% ---------- Certifications ----------
\section{Certifications (optional)}
\begin{resumeItems}
  \item {[}Add any relevant certifications --- e.g. Google Data Analytics, SQL, or Python courses --- or delete this section if you don't have any yet{]}
\end{resumeItems}

\end{document}
