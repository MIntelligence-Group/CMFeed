Synthesizing Sentiment-Controlled Feedback For Multimodal Text and Image Data
================================================

Implementation for the paper (submitted to IEEE Transactions on Affective Computing ). <br>
**[Affective Feedback Synthesis Towards Multimodal Text and Image Data][1]**<br>
[Puneet Kumar](https://puneet-kr.github.io/), Sarthak Malik, [Balasubramanian Raman](http://faculty.iitr.ac.in/~balarfma/) and Xiaobai Li. 

## Code Files
The code files are currently private and will be made public after the acceptance/publication of the corresponding paper. 

Dataset Details & Access
-------------------------
The [`Controllable Multimodal Feedback Synthesis (CMFeed) Dataset`][2] dataset' has been compiled by Puneet Kumar and Sarthak Malik under the supervision of Prof. Balasubramanian Raman and Prof. Xiaobai Li. It contains $61734$ samples from $3646$ posts compiled by crawling news articles from Sky News, NYDaily, FoxNews, BBC News, and BBC NW through Facebook posts. It consists of multiple images per sample, corresponding news text, post likes and shares, and human comments. The comments for each post have been sorted based on Facebook's 'most-relevant' criterion.


\begin{table}[!h]
\centering
{\fontsize{8}{10}\selectfont
\caption{CMFeed dataset's parameters and respective values}
\label{tab:data}
\resizebox{.32\textwidth}{!}{
\begin{tabular}{@{}lc@{}}
    \toprule
    \textbf{Parameter}               & \textbf{Value} \\ \midrule
    No. of news posts                & 3646          \\
    No. of data samples              & 61734         \\
    Avg. no. of likes per post       & 65.1           \\
    Avg. no. of likes per comment    & 10.5           \\
    Avg. length of news text         & 655 words      \\
    Avg. no. of images per post      & 3.7            \\
    Percentage of positive comments  & 39.7           \\ \bottomrule
\end{tabular}
}}\vspace{-.1in}
\end{table}

Access to the CMFeed dataset can be obtained by through [`Access Form - CMFeed Dataset.pdf`][2].   

[1]: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5165369
[2]: https://github.com/MIntelligence-Group/CMFeed/blob/main/Access%20Form%20-%20CMFeed%20Dataset.pdf
