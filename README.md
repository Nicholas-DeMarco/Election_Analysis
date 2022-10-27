# Election_Analysis

Overview of Election Results

  In this analysis, we were trying to find out how many voters were coming out to vote from each of 3 counties. We also wanted to find a conclusion of our election results. In this overview we will break down some of our results and the steps we used to get there.
  
    This next section we are moving into will show us some of our results and the steps qwe used to get there. Let us let at some of our election outcomes now:
    
      *Using the image below we can see the code that gave us the result on how many total voters came out. The total number of voters was 369, 711. In this code we are using different variables to find each candidate's name and how many times they were voted for and then adding them all together to find our total vote count.
      
      ![Screenshot (61)](https://user-images.githubusercontent.com/114521887/198362343-d665d6de-1300-4215-858b-72f4935120b6.png)
      
      *Using some of the same code from the image entered above, along with some additional coding, we were able to find out how many voters came out from each county and the percentage that each county received. I will attach another image of code that was used to go through this process.
      
      ![Screenshot (62)](https://user-images.githubusercontent.com/114521887/198363205-32b33f52-3b0e-4918-a2f4-46084a47d064.png)
      
        The county of Jefferson received 38,885 votes, which was 10.5% of the total votes.
        The county of Denver received 306,055 votes, which was 82.8% of the total votes.
        The county of Arapahoe received 24,801 votes, which was 6.7% of the total votes.
      
      *Using the image below we can see the code that was used to find out which county had the biggest voter turnout. The county with the biggest voter turnout was Denver with 306,055 voters!
      
      ![Screenshot (63)](https://user-images.githubusercontent.com/114521887/198364292-2fdc87f8-e6a3-4008-bf0b-8a571f94f1f1.png)
      
      *Using the image below we can see the code that was used to find out the total number of votes each candidate received and what the percentage of the total votes was.
      
      ![Screenshot (64)](https://user-images.githubusercontent.com/114521887/198365098-dc26f527-ef8d-4885-a8cd-3fc40bec8be9.png)
      
        Charles Casper Stockham received 85,213 votes, which was 23% of the total votes.
        Diana DeGette received 272,892 votes, which was 73.8% of the total votes.
        Raymon Anthony Doane received 11,606 votes, which was 3.1% of the total votes.
        
       *By using all of this code that I have provided above and finally coming to our last few lines of code, we were able to find which candidate won by receiving the most votes. Our winning candidate was:
       
        Diana DeGette by receiving 272, 892 votes! She won by a massive margin, receiving 73.8% of all votes cast!
        
   Much of this code could be used for any election. By simply swapping out our csv file, which in this case was "election_results.csv", as long as our new dataset is found in the same folder, it can be a very easy modification. You may just have to widen how many rows and columns that your code is reading from your dataset. For example, in the given dataset that we used for this analysis our candidate name was located in column 2 and we were able to find that column using the code below:
   
   First we had to load in our csv file using : file_to_load = os.path.join("Resources", "election_results.csv"). and then we were able to locate the candidate names by using the code : candidate_name = row[2]. A column of a dataset always starts at 0, so counting over from 0 we are able to see that the names of the candidates are shown in column 2. So with some minor modifications to our coding, we could insert any dataset and read it using much fo the code we have used for this dataset.


      
