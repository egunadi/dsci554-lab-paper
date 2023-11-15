# Lab on paper

## Get started with Overleaf

After you [register with Overleaf](https://www.overleaf.com/register):

- Login at [Overleaf](https://www.overleaf.com)
- Click `New Project` and `Upload Project`
- Upload `LNCS-Template.zip`
- Click ✎ icon next to the title at the top of the page and rename with your project name
- Click `Share` to share within your team
- In the <code>Share Project</code> panel click <code>Turn on link sharing</code> and use the <q>Anyone with this link can view this project</q>

## Working with latex

- To cite URLs see d3_url entry in `mybibliography.bib`
- To cite some other reference (including books from Colin Ware):
  - Go to google scholar
  - Search
  - Click on `＂` link next to the star and click on `BibTex` link
  - Paste in the mybibliography.bib file
- To add png pictures upload the picture and follow the example in fig1.eps with the png filename
- If you want to add a table, say of descriptive stats of your data, cut and paste an example from [Overleaf Tables Introduction](https://www.overleaf.com/learn/latex/Tables#Introduction)
- For any latex help search [Overleaf learn latex](https://www.overleaf.com/learn/latex)

Suggested outline:

```tex
\section{Introduction}
\label{introduction}
​
\begin{itemize}
    \item Explain motivation (importance of topic and need for visualization)
    \item Explain the scope of you visualization (who is it addressed to, how it is useful)
    \item Explain what is challenging and novel
    \item Explain your contributions compare to the prior work
    \item Introduce the rest of the sections, e.g., in section~\ref{related-work} we present related visualization work, in section~\ref{data} we present the dataset used, in section~\ref{approach} we explain how we designed and the process we used to build the system, in section~\ref{system} we showcase the main aspects of the website we have built and finally conclude with~\ref{conclusion}.
\end{itemize}
​
\section{Related Work}
\label{related-work}
​
\begin{itemize}
    \item Explain what others have done in the same topic
    \item Explain what others have done in other areas that is relevant
    \item Explain how your work fits in relation to others.
\end{itemize}
​
\section{Data}
\label{data}
​
\begin{itemize}
    \item Explain the dataset (descriptive statistics...)
    \item Explain what pre-processing you had to do
\end{itemize}
​
\section{Visual Data Analysis & Modeling}
\label{data-modeling}
​
\begin{itemize}
    \item Explain what analysis you did, how you used visualization for this
    \item Explain what models you built, how you used visualization for this 
\end{itemize}

\section{Design}
\label{design}
​
\begin{itemize}
    \item Explain the design process
    \item Explain the design considerations
    \item Explain how original...
\end{itemize}
​
\section{Demonstration Scenarios}
\label{demo}
​
\begin{itemize}
    \item Explain how you built the dashboard/infographic (technologies & methods)
    \item Explain highlights of demo...
\end{itemize}
​
\section{Results}
\label{results}
​
\begin{itemize}
    \item Explain the model
    \item Explain the model performance...
\end{itemize}

\section{Conclusion}
\label{conclusion}
​
\begin{itemize}
    \item List your contributions
    \item Explain what you would do next or differently
\end{itemize}
```
