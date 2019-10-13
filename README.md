# Cricket-Match-Highlight-Generation
<h2> 1.1 Dataset Description </h2>
- For the processing I have download the cricket match video from youtube. It is a famous video, in which yuvraj singh hit 6 sixes on six balls in T-20 world cup 2007
<h2> 1.2 Sources/Useful Links</h2>
- You Tube Link for the Video : https://www.youtube.com/watch?v=KPn3ZUcaBOY
### Approach
- In our approach we have used sound energy for the categorization of the 5 second video chunk, whether it should be in the highlight or not. Through exploratory data analysis we found out the optimal threshold. If some part of the video is having less sound energy then threshold, we will remove that part from the video. 
