java c
STA220H1 The Practice of Statistics I (Fall 2024)
Assignment 1 Instructions
Due Date: October 18, 2024 at 11:59 on Crowdmark
Instructions
This is an individual assignment. You are expected to work on this independently. While you may discuss ideas and concepts, please do not share your code or written answers. It is expected   that all code and written work should be written by yourself. Please note, this assignment is fairly open, so the context of most of the work completed here should not match your peers.
Submission Format and Instructions
Your final submission will be in PDF file. You will submit your solutions on Crowdmark. There will be a different upload box for each question, so it is recommended that you place each question on different pages or files.
For question 1, your PDF file will need to show (1) R code, (2) R output/figures, and (3) your written answers. Here are some suggested ways you can create your final submission:
•   Use Microsoft Word to type out your answers. Screenshot your R output and place these images throughout the document. For the R code, either copy/paste as text or screenshot.
•   Use an app like Notability, OneNote, etc., where you can write/type your answers and include screenshots of your R code and output.
•   Use RMarkdown and knit to a PDF. Alternatively, you can knit to an HTML file and then save it as a PDF.
How you create the final file is up to you, as long as it is clear and organized. You don’t want the TA to be frustrated while marking your work! 
Late Penalty
As described on the course syllabus, late work will be deducted 10% per hour.
Question 1 (30 marks)
Consider the Airbnb dataset provided for this assignment. The provided Airbnb dataset offers insights into the listing activity of homestays in New York City, including essential information such as the geographical location, pricing, reviews, and host details. Below is a description of the variables included in the dataset:
•    Name: The name of the property listing.
•    host_identity_verified: Indicates whether the host's identity has been verified.
•    host.name: The name of the host.
•    neighbourhood.group: The larger neighborhood group where the listing is located.
•    neighbourhood: The specific neighborhood where the listing is located.
•    lat: The latitude of the listing, based on the WGS84 geographic coordinate system.
•    long: The longitude of the listing, based on the WGS84 geographic coordinate system.
•    instant_bookable: Specifies whether the listing can be instantly booked.
•    cancellation_policy: The type of cancellation policy applied to the listing.
•    room.type: The type of room available for the listing (e.g., entire home, private room).
•    construction.year: The year the property was constructed.
•    price: The price of the listing per night, in USD.
•     service.fee: The service fee per night, in USD.
•    minimum.nights: The minimum number of nights required to book the listing.
•    number.of.reviews: The total number of reviews received in the last 12 months.
•    reviews.per.month: The average number of reviews received each month over the listing’s lifetime.
•    review.rate.number: The average review rating of the listing.
•    calculated.host.listings.count: The number of listings managed by the host, as calculated by Airbnb.
•     availability.365: The number of days the listing is available for booking within the next 365 days.
Your task is to explore and analyze the Airbnb dataset using graphical summaries created using R. Create a minimum of 4 properly labelled plots/graphs/figures that summarize some of the patterns in the data. It is recommended that you use at least 3 different t代 写STA220H1 The Practice of Statistics I (Fall 2024)R
代做程序编程语言ypes of plots. For each plot, write a few sentences explaining the patterns and/or trends you see in the plot.
You will be graded on not only your ability to create plots in R, but also your ability to use the plots to highlight important and/or compelling information in the data.
Question 1 Rubric

Inadequate
Fair
Good
Excellent
Plots (10 marks)
0-4 marks

Does not meet   the requirement of 4+ plots.
5-6 marks

Required plots
are provided, but
plots do not
highlight the important
information or show a variety of trends. The  type of plots
chosen are not ideal for the
situation.
7-8 marks

Required plots
are provided,
and mostly
shows that the
student is able to create a plot
relevant for the
situation. A
variety of plots are used, and
plots are labelled properly.
9-10 marks

Required plots are provided,
and a lot of
thought was put into creating the plot. Plots are
interesting,
compelling, and communicate
well to the viewer.
Written
descriptions (10 marks)
0-4 marks

Written
descriptions are not sufficient in describing the
plots. Writing is unclear.
5-6 marks

Written
descriptions are provided but
contain major errors. The
descriptions do not accurately   describe the
plots or are
misleading. Writing is   somewhat   unclear.
7-8 marks

Written
descriptions are provided and
shows that
student is able to properly
interpret plots. Writing is
generally clear.
9-10 marks

Written
descriptions are excellent.
Student exceeds  expectations and highlights the
important trends within the data.  Writing is clear  and compelling.
R code (10 marks)
0-4 marks

R code is not shown or has many major   errors.
5-6 marks

R code is
provided but is difficult to
follow.
7-8 marks

R code is
provided, but
does not show a variety of plot    types.
9-10 marks

R code is
provided. A
variety of plot
types are shown.
Question 2 (30 marks)
Consider a study evaluating the effectiveness of two treatments (A and B) for a particular disease. The effectiveness of these treatments is measured under two different conditions: mild and severe. The outcome for each patient is classified into one of two categories: survived or   deceased. The following table summarizes the observed results:

Mild
Severe
Survived
Deceased
Survived
Deceased
A
150
850
30
70
Treatment
B
5
45
100
400
a)  For each treatment, draw a tree diagram illustrating the problem (2pts)
b)  Calculate all the conditional probabilities appear on your tree diagrams (4pts)
c)  For each treatment, what’s the conditional probabilities of survival under either
condition? (2pt) Briefly summarize the findings based on your results. Which treatment has a better effect and why? (2pts)
d)  For each treatment, what’s the marginal probabilities of survival? (2pts) Briefly
summarize the findings based on your results. Based on this new result, which treatment has a better effect and why? (2pts)
e)  For each treatment, conditioning on a patient survived, what’s the probability that the patient is under mild condition? (4pts)
f)   For patient under either mild or severe conditions, conditioning on a patient survived, what’s the probability that the patient receives treatment A? (4pts)
g)  From your results above, could you explain the reasons why there are contradict findings
between (c) and (d). Overall, which treatment is better? (4pts)
h)  Suggest any possible solutions to avoid the confusions induced by contradict findings. (4pts)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
