\documentclass{article}
\usepackage{hyperref}
\usepackage{xcolor}

\title{\textbf{Real Estate Price Estimator}}
\date{}

\begin{document}

\maketitle

\section*{📌 Project Workflow}

\textbf{1️⃣ Web Scraping} 🕵️‍♂️  
\begin{itemize}
    \item Used \textbf{Selenium} and \textbf{BeautifulSoup} to scrape property listings from \href{https://www.99acres.com}{99acres.com}.
\end{itemize}

\textbf{2️⃣ Data Cleaning \& Feature Engineering} 🛠️  
\begin{itemize}
    \item Processed raw data to ensure correctness and consistency.
    \item Engineered features for better model performance (e.g., numeric conversion, missing value handling).
\end{itemize}

\textbf{3️⃣ Market Analysis} 📊  
\begin{itemize}
    \item Extracted \textbf{hottest locations} and \textbf{variance in property prices} within localities.
\end{itemize}

\textbf{4️⃣ Machine Learning Model} 🤖  
\begin{itemize}
    \item Trained a \textbf{Random Forest Regressor} to predict property prices.
    \item Applied \textbf{One-Hot Encoding} for categorical data.
\end{itemize}

\textbf{5️⃣ Model Performance} 🎯  
\begin{itemize}
    \item Achieved an \textbf{R² score of ~60\%}, explaining a significant portion of price variance.
\end{itemize}

\end{document}
