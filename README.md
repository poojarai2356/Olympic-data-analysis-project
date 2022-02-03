# Olympic-data-analysis-project

Olympic data analysis web app have 4 major section:
1. Medal Tally
2. Overall analysis
3. country-wise analysis
4. athlete-wise analysis

### Medal Tally module:
This section show all country gained medal summary. By default value of year and country are Overall. we can apply filter on the basis of:
1. year
2. country

### Overall Analysis:
This page show :
1. top statistics that include edition, host, nation, events, athlete, sports.
2. next it will show plotly line graph :

      i.   nations vs year
      
      ii.  events vs year
      
      iii. athletes vs year
3. next it we show heatmap for no.event over time
4. At the end it will show a table of top 15 most successsful atheles.we can also filter out athlete on the basis of sport.

### Country wise analysis:
In this section we can analysis whole data for a particular country. it show:
1. plotly line graph that show country medal tally over year.
2. heatmap that show in which sport country is excels.
3. table that show top 10 athlete from that country.

### Athlete-wise analysis:
In this module we can analysis whole data on the basis of athletes. it show:
1.Distribution of age.
2.Distribution of Age wrt Sports(Gold Medalist) that show in which athlete age range there is most probably chances of gold medal in particular sport.
3.Height Vs Weight that show height vs weight relation of athlete for particular sport. By default it show this realtion for all sport. we can filter out data on the basis of  particular sport.
4.Men Vs Women Participation Over the Years


dataset link: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

webapp link: https://olympic-da.herokuapp.com/
