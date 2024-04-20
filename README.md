# Excel-Projects
Deliverables:
The report you produce must include the following deliverables:
● A description of the data source used.
Some of the columns included in the dataset are listed below:
 School ID: Unique identification number for each school.
 School Name: The name of the school.
 Location: The information on district, street, and union councils Enrollment: The total number of students enrolled in the school.
 Teachers: The number of teachers in the school School Upgradation Years: The years in which the school levels were upgraded (in datasets cols are upgrade_primary_year, upgrade_middle_year, upgrade_high_year,upgrade_higher_sec_year) 
School Gender: The gender for which the school was initially built. Gender Studying: The genders currently studying in the school School Head Information, School status, School medium, Year of establishment, Genders studying, Infrastructure.
● Documentation of any cleaning or manipulation of data.
•	As per the given overview the dataset, school ID’s given are the actual schools along with their name. but there are 48,120 schools that are functional and 1 school is non-functional. So according to this 70 schools are there whose status is not clear. If I say that those are the proposed schools but nothing has been done anything about them so far. 
We can remove those schools from our dataset and can just spend all the funds in improving the buildings and all. 
•	We can also spend some funds on making buildings of those proposed schools if we have that much amount.
•	There are 18 schools whose “Construct Type” is “Completely Rough”, which needs to be inspected for children’s safety.
•	 There are 129 schools which are “running in the Mosque” , they need a proper building.
•	705 schools don’t have functional classrooms.
•	There are 280 buildings whose status is 0 means these needs to be renovated.
● Justification for the allocation of funds to specific educational initiatives.
(School ID 54934) A school in liaqatpur has a non functional building with poor condition and construction quality is dangerous. That should be demolished and built from scratch. 
The following tasks will be useful in helping you navigate and using the dataset as needed:
● Determine the total number of schools present in the dataset.
There are 48,191 schools, but total functional schools are 48, 120 and 1 school is non-functional.
Rest of 70 schools have no record at all except school id, emiscode, and location. There aren’t any teachers, herads or students in those schools.
● Identify the lowest students of school_Gender(male & female) by school level of schools established in the 2000s
The H. Secondary has the lowest number of students.
● Determine the top 5 districts with the highest number of teachers and non-teachers in
schools.
Row Labels	Sum of Teachers	Sum of NonTeachers
FAISALABAD	22996	4918
LAHORE	16654	3128
RAHIMYAR KHAN	17601	3006
RAWALPINDI	17112	3438
SARGODHA	15798	3418
Grand Total	90161	17908


 
● Explore the school level and medium that have the lowest number of functional
classrooms.
Row Labels	Sum of functional_classrooms
H.Sec.	15396
Middle	61192
Primary	102125
Secondary	83398
sMosque	512
(blank)	
Grand Total	262623

 

Conclusion:
•	Maximum number of functional class rooms are in Primary level 
•	It covers 39% of the total classrooms
● Create a bar chart showcasing the distribution of teachers across different schools. 
 


Conclusion:
•	Out of functional schools, there are different number of teachers allocated to different schools.
•	Two school have more than 100 teachers but that justifies the school strength.
•	The schools that are using Mosque buildings need to hire more teachers.
●Calculate the number of male and female students (School_Gender) 
Row Labels	Count of school_gender
Female	25229
Male	22891
Grand Total	48120

 
Conclusion: 
There is an equal amount of Male and Female students.
● Count the number of schools in rural and urban areas and calculate the percentage
of schools offering Urdu and English medium education or both in each category.

Count of number of schools in rural and urban areas by dragging a unique identifier ie school ID.
Row Labels	Both	English	Urdu	Grand Total
Rural	7596	4264	30489	42349
Urban	1808	1214	2749	5771
Grand Total	9404	5478	33238	48120

Percentage of number of schools in rural and urban areas by dragging a unique identifier ie school ID.

Row Labels	Both	English	Urdu	Grand Total
Rural	17.94%	10.07%	71.99%	100.00%
Urban	31.33%	21.04%	47.63%	100.00%
Grand Total	19.54%	11.38%	69.07%	100.00%

Conclusion:
•	In rural areas, 72% school are Urdu medium where are urban areas have 48% Urdu medium schools.
•	Therefore, we need to change the mediums to produce competent generation.
● Identify the district with the highest enrollment in primary schools since their establishment.
Row Labels	Sum of enrollment
VEHARI	132077
T.T.SINGH	115485
SIALKOT	134986
SHEIKHUPURA	98575
SARGODHA	160621
SAHIWAL	93598
RAWALPINDI	96860
RAJANPUR	98489
RAHIMYAR KHAN	257799
PAKPATTAN	108198
OKARA	131889
NAROWAL	94505
NANKANA SAHIB	73190
MUZAFFARGARH	184840
MULTAN	136061
MIANWALI	89499
MANDI BAHA UD DIN	69993
LODHRAN	64909
LAYYAH	120390
LAHORE	120464
KHUSHAB	64148
KHANEWAL	130888
KASUR	151602
JHELUM	44058
JHANG	153896
HAFIZABAD	60965
GUJRAT	108364
GUJRANWALA	129561
FAISALABAD	234888
D.G. KHAN	176390
CHINIOT	87974
CHAKWAL	42068
BHAKKAR	102846
BAHAWALPUR	136240
BAHAWALNAGAR	188760
ATTOCK	72057
Grand Total	4267133


Conclusion:
•	Rahimyar Khan is the district with highest number of enrollments in primary levels.

● Determine the district with the highest enrollment in secondary schools since their
establishment.
Row Labels	Sum of enrollment
VEHARI	99163
T.T.SINGH	122685
SIALKOT	165435
SHEIKHUPURA	125310
SARGODHA	173756
SAHIWAL	119178
RAWALPINDI	180642
RAJANPUR	39269
RAHIMYAR KHAN	153560
PAKPATTAN	65486
OKARA	143249
NAROWAL	90675
NANKANA SAHIB	57784
MUZAFFARGARH	82843
MULTAN	124820
MIANWALI	76161
MANDI BAHA UD DIN	96709
LODHRAN	47296
LAYYAH	86581
LAHORE	353382
KHUSHAB	53342
KHANEWAL	135106
KASUR	141328
JHELUM	74328
JHANG	109509
HAFIZABAD	42826
GUJRAT	157207
GUJRANWALA	186595
FAISALABAD	362868
D.G. KHAN	75440
CHINIOT	56857
CHAKWAL	94396
BHAKKAR	66668
BAHAWALPUR	99065
BAHAWALNAGAR	110309
ATTOCK	101752
Grand Total	4271580

Conclusion:
At secondary level, Faisalabad is the one with highest number of enrollments.
● Find the district with the highest enrollment in higher secondary schools since their
establishment.

Row Labels	Sum of enrollment
VEHARI	27048
T.T.SINGH	18219
SIALKOT	40423
SHEIKHUPURA	30830
SARGODHA	36088
SAHIWAL	35339
RAWALPINDI	33499
RAJANPUR	16034
RAHIMYAR KHAN	31133
PAKPATTAN	15474
OKARA	12891
NAROWAL	19752
NANKANA SAHIB	14021
MUZAFFARGARH	16695
MULTAN	38429
MIANWALI	11274
MANDI BAHA UD DIN	14492
LODHRAN	12786
LAYYAH	10050
LAHORE	50918
KHUSHAB	11998
KHANEWAL	28009
KASUR	20300
JHELUM	13932
JHANG	22285
HAFIZABAD	19179
GUJRAT	22618
GUJRANWALA	25971
FAISALABAD	99227
D.G. KHAN	21770
CHINIOT	7050
CHAKWAL	15162
BHAKKAR	8093
BAHAWALPUR	28322
BAHAWALNAGAR	22815
ATTOCK	17879
Grand Total	870005

Conclusion: 
•	highest number of enrollments in higher school is in district Faisalabad


● Create a bar chart displaying the distribution of schools according to school_level
Row Labels	Count of school_id
H.Sec.	749
Middle	8277
Primary	31994
Secondary	6667
sMosque	433
Grand Total	48120

Conclusion:
Distribution of schools is 1.56% for H.Sec, 17.20% for middle, 66.49% for primary, 13.85% for secondary.

● Generate a bar chart representing the number of students categorized by gender (School_Gender).
Row Labels	Count of school_id
Female	52.43%
Male	47.57%
Grand Total	100.00%

● Create a table showcasing the school_ownership with respect to schools.
Row Labels	Count of school_id
Building Provided By Local Residents	1028
Education Department	45607
Municipal Building	537
On Rent	183
Property Of Any Other Institution Besides The Municipal Institution	132
Running In The Mosque	128
School Council provided building	83
Some Other Govt. School	148
(blank)	274
Grand Total	48120

 ● Visualize the distribution of teachers based on their respective job posts using a bar chart.
No enough data is given about teachers’ job posts, instead, if it was heads posts, it would be like this:
Row Labels	Count of school_id
Additional Charge	5752
Lookafter Charge	2223
NULL	198
Permanent	39947
Grand Total	48120

● Create a pie chart to show the percentage of vacant and filled teaching and non-teaching posts.

Row Labels	Count of Adjusted teachers
Filled	47961
Vaccant	159
Grand Total	48120

 

Row Labels	Count of Adjusted Non teachers
Filled	23536
Vacant	24584
Grand Total	48120

 
 
•	Determine the percentage of schools with satisfactory building conditions (bldg_condition).
 
Conclusion: 

•	74% of the schools are with satisfactory building conditions.
● Calculate the number of schools with satisfactory security measures. 

Row Labels	Count of school_id
Available	1
Not Available	11222
Not Satisfying	3074
Satisfying	33823
Grand Total	48120



 


Conclusion:
•	70% of schools have satisfying security.
● List the names of the 5 districts with the lowest availability of drinking water facilities in schools.
 

Conclusion:
•	LODHRAN
•	NAROWAL
•	VEHARI
•	T.T.SINGH
•	PAKPATTAN
•	KHUSHAB
•	SAHIWAL
•	JHANG
•	SHEIKHUPURA
•	Are the districts with lowest drinking water facilities.
● Identify the names of the 5 districts with the lowest availability of electricity in schools.
NANKANA SAHIB	748
MUZAFFARGARH	1754
MULTAN	1312
MIANWALI	1228
MANDI BAHA UD DIN	773
LODHRAN	755
LAYYAH	1513
LAHORE	1137
KHUSHAB	951
KHANEWAL	1237
KASUR	1358
JHELUM	788
JHANG	1476
HAFIZABAD	732
GUJRAT	1393
GUJRANWALA	1549
FAISALABAD	2208
D.G. KHAN	1602
CHINIOT	697

 

Conclusion:
Chiniot, Hafizabad, Lodhran, Mandi Bahud Din, Nankhana Sahib are the districts with lowest electricity availability.
● Determine the names of the 5 districts with the lowest presence of boundary walls in schools.
NANKANA SAHIB	748
MANDI BAHA UD DIN	773
LODHRAN	755
JHELUM	788
HAFIZABAD	732
CHINIOT	697


Conclusion:
•	Above are the districts with lowest presence of boundary walls.
● List the names of the 5 districts with the lowest availability of toilets in schools.
 
Conclusion:
•	Chiniot is the one with lowest presence of  toilets in the schools
These objectives will guide your analysis and provide insights for your report. You are
expected to export tables from Excel for a more comprehensive report. Additionally, feel free
to explore the dataset further and present any other findings that you deem relevant for
educational policymaking.

