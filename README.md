#Sublime Text 2のスニペット
ここにない場合はここで  
[LaTeXコマンド集](http://www.latex-cmd.com/)  
ショートカットを打って`Tab`  
改行して，先頭じゃないと補間が効かないかも  

##cas
```tex
\begin{cases}
  equation, &\text{ if }case\\

\end{cases}
```

##cha
```tex
\chapter{chapter name} % (fold)
\label{cha:chapter_name}

% chapter chapter_name (end)
```

##$$
```tex
\[

\]
```

##enum
```tex
\begin{enumerate}
  \item
\end{enumerate}

```

##eq
```tex
\begin{equation}
\label{eq:?}
  
\end{equation}
```

##eq
```tex
\begin{eqnarray}
\label{eq:?}
   & = & \nonumber \\
   & = &
\end{eqnarray}
```

##eq
```tex
式\eqref{eq:?}
```

##figure
```tex
Fig~\ref{fig:}
```

##figure
```tex
\begin{figure}[htbp]
  \begin{center}
    \includegraphics[clip,width=?cm]{filename.eps}
  \end{center}
  \caption{title}
  \label{fig:title}
\end{figure}
```

##item
```tex
\begin{itemize}
  \item
\end{itemize}
```

##listing
```tex
Listing~\ref{lst:}
```

##mat
```tex
\begin{p/b/v/V/B/smallmatrix}

\end{p/b/v/V/B/smallmatrix}
```

##page
```tex
page~\pageref{}
```

##par
```tex
\paragraph{paragraph name} % (fold)
\label{par:paragraph_name}

% paragraph paragraph_name (end)
```

##part
```tex
\part{part name} % (fold)
\label{prt:part_ _name_}

% part part_ _name_ (end)
```

##section
```tex
Section~\ref{sec:}
```

##spl
```tex
\begin{split}

\end{split}
```

##subp
```tex
\subparagraph{subparagraph name} % (fold)
\label{subp:subparagraph_name}

% subparagraph subparagraph_name (end)
```

##table
```tex
Tab~\ref{tab:}
```

##tab
```tex
\begin{tabular}{c}

\end{tabular}
```

##begin
```tex
\begin{env}

\end{env}
```

##sec
```tex
\section{section name}
\label{sec:section_name}

% section section_name (end)
```

##sub
```tex
\subsection{subsection name}
\label{sub:subsection_name}

% subsection subsection_name (end)
```

##subs
```tex
\subsection{subsection name}
\label{sub:subsection_name}

% subsection subsection_name (end)
```