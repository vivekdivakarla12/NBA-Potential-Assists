# NBA-Potential-Assists
Research around the Potential Assist Stat in the NBA, and how accurately it predicts how many assists a player will have

First Update - importing the data and making preliminary graphs. 
Took the Top 50 players in assists from https://www.nba.com/stats/players/passing and made it a CSV, and import it into Pandas
The graphs have Assists on the X axis, with Potential assists, AST to Pass %, and Potential Assist Per Assist on the Y axis. 
These graphs were made to see if there were any big correlations to the Assist stat, which the Potential Assist one is fairly linear


<img width="420" alt="Screen Shot 2023-01-06 at 3 33 45 PM" src="https://user-images.githubusercontent.com/11672096/211095184-f90d6eb2-bd14-49c7-849a-93923c38a130.png">

<img width="404" alt="Screen Shot 2023-01-06 at 3 34 05 PM" src="https://user-images.githubusercontent.com/11672096/211095242-857b1d7f-f19f-41b1-9222-606dcdfe7555.png">

<img width="416" alt="Screen Shot 2023-01-06 at 3 34 28 PM" src="https://user-images.githubusercontent.com/11672096/211095299-36b83e7d-7467-4d34-abbb-a3ed43fb27cc.png">

<img width="419" alt="Screen Shot 2023-01-06 at 3 34 46 PM" src="https://user-images.githubusercontent.com/11672096/211095343-011a99b0-a9e4-496b-be19-dda1f96c77df.png">

These graphs, as expected, are mostly linear. However, there are a few outliers in each which are interesting, and can possibly show differences between the top passers in the NBA. Some of them (Trae Young, for example), pass the ball much less, but still average high assist numbers. This could show how the Hawks offense essentially works, with many drives from Trae Young, then passes to open players in the paint or at the 3 point line. Next steps could be comparing touches and drives data to see if this has an impact on assists
