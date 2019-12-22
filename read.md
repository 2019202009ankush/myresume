%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Ankush Mitra(http://ankush.mitra@students.iiit.ac.in)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Ankush}{Mitra}{ 
\urlstyle{same}\href{mailto:ankush.mitra.1996@gmail.com}{ankush.mitra.1996@gmail.com} | +91-9064222037 | \href{mailto:ankush.mitra@students.iiit.ac.in}{ankush.mitra@students.iiit.ac.in}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{IIIT Hyderabad}
\descript{MTech in Computer Science and Information Security}
\location{July 2019 | Hyderabad,India}
\location{ CGPA: 8.9 / 10.00 }
\sectionsep

\subsection{UIT Burdwan}
\descript{BE in Information Technology}
\location{June 2014 | West Bengal, India}
\location{ Percentage: 82.24 / 100.00 }
\sectionsep

\subsection{St Paul's School}
\descript{Higher Secondary}
\location{May 2012|  Kolkata, India}
\location{ Percentage: 76.00 / 100.00 }
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
Hackerrank:// \href{https://www.hackerrank.com/2019202009_anku}{\bf Ankush Mitra}(5 star)\\
Facebook:// \href{https://www.facebook.com/princearry.mitter}{\bf Ankush Mitra} \\
Github:// \href{https://github.com/2019202009ankush}{\bf Ankush Mitra} \\
LinkedIn://  \href{https://www.linkedin.com/in/ankush-mitra/}{\bf Ankush Mitra} \\
YouTube://  \href{https://www.youtube.com/channel/UCTJPFWBpMrHBS5QPw6qSkYw}{\bf Ankush Mitra} \\


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Coursework}
\subsection{Graduate}
Operating System\\
Advance Problem Solving + Practicum \\
Scripting and Computer Environment \\
Discrete Math  \\
\sectionsep

\subsection{Undergraduate}
DBMS + Practicum\\
Operating Systems  + Practicum \\
Data Structure and Algorithm \\
Computer Architecture  + Practicum \\
Digital Electronic + Practicum \\
Functional Programming + Practicum \\
Object Oriented Programming  \\
Digital Image Processing \\
Compiler \\
Software Engineering \\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\subsection{Programming}
\location{Over 5000 lines:}
C++ \textbullet{}   Shell \textbullet{} Python \textbullet{} C \\
CSS \textbullet{} Matlab \textbullet{} HTML \\ 
\location{Over 1000 lines:}
JAVA \textbullet{} React JS  \textbullet{} JS \textbullet{} PHP \textbullet{} Assembly \\
\location{Familiar:}
GIT \textbullet{} Linux \textbullet{} MySQL \textbullet{} Tile38 \textbullet{} Redis
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience}
\runsubsection{Adonmo Private Limited}
\descript{| Software Engineering Intern}
\location{DEC 2019 - DEC 2019 | Hyderabad , India}
\vspace{\topsep} % Hacky fix for awkward extra vertical space
\begin{tightemize}
\item Back-end developer - added back-end support to make location based digital advertising possible.
\item Wrote code in Python to set geo-fence around some coordinate and send notification to a MQTT server using web-hook when some device are inside the fence.
\item Front-end developer- make a interface to visualize the updated position of a device on map using leaflet,material-ui,react,npm.
\end{tightemize}
\sectionsep


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Project}
\runsubsection{Mini Torrent(Peer to Peer file sharing)}
\descript{| \textbf{\href{https://github.com/2019202009ankush/peer_to_peer_file_sharing_mini_torrent}{github}}}
\location{Oct 2019 – Oct 2019}
\begin{tightemize}
\item Developed a tracker and peer based architecture to support peer to peer file sharing.
\item It is multi-threaded so file upload and download can be done in chunks using independent thread.Hence it is very fast.
\item For optimization I did load balancing based on seeder list at tracker. 
\end{tightemize}  
\sectionsep
\runsubsection{Distributed Key Value Store(PIAZZA)}
\descript{| \textbf{\href{https://github.com/2019202009ankush/Piazza}{github}}}
\location{Sep 2019 – Nov 2019}
\begin{tightemize}
\item Developed a coordinator  and replication group  (data store server) based architecture to support Distributed Key Value store.
\item For optimization I did consistent hasing to distribute load optimally on slave server.
\item For data consistency I have used two phase commit protocol here.
\end{tightemize}
\runsubsection{Linux Shell}
\descript{| \textbf{\href{https://github.com/2019202009ankush/ankush_shell}{github}}}
\location{Sep 2019 – Sep 2019}
\begin{tightemize}
\item Developed a basic Linux shell to run all useful Linux command.
\item It supports IO redirection and multiple pipe.
\end{tightemize}
\runsubsection{Indian Currency Detection}
\descript{| \textbf{\href{https://github.com/2019202009ankush/indian_currency}{github}}}
\location{Sep 2019 – Sep 2019}
\begin{tightemize}
\item Wrote code in python to develop a system to detect Indian currency based on local feature using Open CV.
\end{tightemize}
\runsubsection{Design and Implementation of Barrel Shift-er }
\descript{}
\location{Dec 2017 – Feb 2018}
\begin{tightemize}
\item Implemented a Virtual Barrel Shift-er using Xilinx to support Logical rotation of Binary data.
\end{tightemize}
\runsubsection{Tour and Travel Management System }
\descript{ Website | \textbf{\href{https://www.youtube.com/watch?v=PjyScY1wRwU&t=290s}{Youtube}}}
\location{Dec 2016 – Jan 2017}
\begin{tightemize}
\item Made a beautiful website for tour and travel management system using HTML,CSS,Bootstrap,JS.
\item Applied Shortest Path Algorithm when suggesting a root distance and cost.
\item Used map Api and payment card Api.
\end{tightemize}
\runsubsection{Snake Game }
\descript{|\textbf{\href{https://github.com/2019202009ankush/Cool_python_scripts/blob/master/new_snake_game.py}{github}}}
\location{Dec 2019 – Dec 2019}
\begin{tightemize}
\item Made a simple snake game using Python . In this game if you win 3 points then one level will be increased .The game has maximum of 50 level.
\end{tightemize}
\sectionsep


\end{minipage} 
\end{document}  \documentclass[]{article}
