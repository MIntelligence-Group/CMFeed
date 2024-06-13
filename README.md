CMFeed: A Benchmark Dataset for Controllable Multimodal Feedback Synthesis
================================================

Implementation for the paper (submitted to NeurIPS 2024 Datasets and Benchmarks Track).  
**[CMFeed: A Benchmark Dataset for Controllable Multimodal Feedback Synthesis][1]**  
[Puneet Kumar](https://puneet-kr.github.io/), [Sarthak Malik](https://www.linkedin.com/in/sarthak-malik-03777a190/), [Balasubramanian Raman](http://faculty.iitr.ac.in/~balarfma/) and [Xiaobai Li](https://www.oulu.fi/en/researchers/xiaobai-li). 

## Code Files
The code files are currently private and will be made public after the acceptance/publication of the corresponding paper. 

## Dataset Details & Access
The [`Controllable Multimodal Feedback Synthesis (CMFeed) Dataset`][2] has been compiled by Puneet Kumar and Sarthak Malik under the supervision of Prof. Balasubramanian Raman and Prof. Xiaobai Li. It contains 61,734 samples from 3,646 posts compiled by crawling news articles from Sky News, NYDaily, FoxNews, BBC News, and BBC NW through Facebook posts. It consists of multiple images per sample, corresponding news text, post likes and shares, and human comments. The comments for each post have been sorted based on Facebook's 'most-relevant' criterion.

This data has been collected through manual crawling from news websites and corresponding Facebook posts in the public domain while adhering to [Facebook's terms and conditions][3].

### Explanation about Compliance to Facebook Terms & Conditions
Facebook prohibits automatic scraping of its users' personal data. Complying with these conditions, we:  
1) Crawl the data manually (as per the steps described below) [Ref][4]. We do not perform automatic data scraping. 
2) Collect the public data corresponding to public news articles [Ref][5]. 

## Steps involved in Data Collection
The process to manually crawl the data is depicted in the following diagram:

<img src="data_construction.jpg" width="90%" align="middle">

## Data Samples and Further Details 
Representative samples from the CMFeed dataset are shown in the following figure where 'Post Likes' and 'Comment Likes' show the number of likes for the post and comment, respectively. 'Share' denotes post shares and `Senti-class` represents comment's sentiment ($1$: positive, $0$: negative).

<img src="data_samples.jpg" width="90%" align="middle"> 

Various parameters of the CMFeed dataset have been described in the following Table.

<img src="data_table.jpg" width="37%" align="middle">

Access to the CMFeed dataset can be obtained at https://zenodo.org/records/11409612.

[1]: https://neurips.cc/Conferences/2024/CallForDatasetsBenchmarks
[2]: https://zenodo.org/records/11409612
[3]: https://developers.facebook.com/terms/
[4]: https://www.facebook.com/help/463983701520800
[5]: https://webscraping.blog/how-to-scrape-facebook/
