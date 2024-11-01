## Reddit-Israel Analysis

A personal project analyzing Reddit posts in the six months before and after October 7.

Dashboard Link: [Tableau Dashboard](https://public.tableau.com/views/Reddit_Israel_Analysis/maindashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This project was undertaken out of curiosity to examine the impact of the October 7 Hamas attack on Israel and the subsequent conflict on Reddit discussions.
### Data And Code
All data used for this analysis was collected and posted by u/Watchful1 on Reddit. Full data can be found [here](https://academictorrents.com/details/9c263fc85366c1ef8f5bb9da0203f4c8c8db75f4). 
Of this data I included only posts regarding Israel using keywords such as: Israel, israeli, IDF, IOF, zionist ,zionism, zionists, Netanyahu, Bibi,Tel Aviv, etc.

For processing and preprocessing of the data, I used Python. The Jupyter Notebook (.ipynb) file for this part is also included in this repository.

For sentiment analysis, I utilized the code from [prusrafal](https://github.com/prusrafal/NLP-Sentiment-Analysis-of-Opinions-in-Israeli-Palestinian-Conflict/blob/main/README.md).

For visualizations, I chose Tableau as a tool to enhance my learning experience. While I have included some observations in the dashboard, I refrained from drawing conclusions, allowing viewers to explore the data and form their own interpretations.

Important Note: The sentiment analysis used here is not perfect; it represents the best option among the methods I have tried. Some issues include poor labeling of ironic or joking posts, as well as posts whose main content is not text-based. I have added a dashboard to examine the posts and assess their labeled sentiment.

### Usage
Click on the dashboard link and view the data using the navigations and instruction there. You can also download the dashboard and worksheets directly from said link. if you found a problem with anything please contact me and I will try to fix it. The data used for this is too large to be uploaded here, I will upload it to kaggle when I have the time, until then feel free to contact me if you need it. 
Feel free to use this code in accordance with the MIT License.
