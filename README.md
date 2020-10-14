# communicate_data_findings

### Introduction
PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in [65 economies](https://www.google.com/url?q=http://www.oecd.org/pisa/aboutpisa/pisa-2012-participants.htm&sa=D&ust=1560360684115000) took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

- The data and topics of investigation come from the [PISA Data Visualization Competition](https://www.google.com/url?q=http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm&sa=D&ust=1560360684116000). For inspiration and examples, see the winners and submissions [here](https://www.google.com/url?q=http://mi2.mini.pw.edu.pl:8080/SmarterPoland/PISAcontest/&sa=D&ust=1560360684116000). If you want to know more about the survey design, the details can be found in the technical report [here](https://www.google.com/url?q=http://www.oecd.org/pisa/data/pisa2012technicalreport.htm&sa=D&ust=1560360684116000).

### Summary

1. Since the data is too large, after opening pisa2012.csv from Excel and reading the description of the field, I only select some features to observe the data.
2. We added a new cloum to describe the presence of parents at home.
3. We performed feature engineering to create a variable that tells us if a student comes from a homogenous or heterogeneous family background.
4. After cleaning data we analyzed it to see  the influence of gender,Parents' existence at home and a homogenous or heterogenous family background in student's perform in math, reading and science.
5. Finally, we also wanted to know which countries have students with exceptionally high literacy scores


### Insights

1. The performance of girls in reading is better than that of boys. But the performance of boys in mathematics and science is better.
2. Parental companionship is helpful for students' learning. Students' learning grows only once, parents should not miss.
3. Different countries have strong and weak performances in different subjects. For example, Ireland has a high reading score and is weak in mathematics and science. China has high mathematics and good reading.
4. Comparing the scores of each country in each subject, it seems that Asian countries are more prominent in each subject.
5. there is a very strong and positive correlation between any pair of the three variables representing the score of the three subjects.
