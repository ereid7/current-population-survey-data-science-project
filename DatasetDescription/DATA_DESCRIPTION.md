# Column Headers
The first name is the column name in this edited version of the CPS 2016 dataset. The second code in parenthesis is the column name from the original dataset (found in readme).

---

### 1. age (PRTAGE) - Numerical
Persons age in years. <br/>
Valid Entries: 0 - 99

---

### 2. weekly_hrs (PRHRUSL1) - Numerical
Usual hours worked weekly. <br/>
Valid Entries: 0 - 99

---

### 3. educ (PEEDUCA) - Numerical/Categorical
Highest level of school completed, or degree recieved. <br/>
Valid Entries: <br/>
1.	LESS THAN 1ST GRADE
2.	1ST, 2ND, 3RD OR 4TH GRADE
3.	5TH OR 6TH GRADE
4.	7TH OR 8TH GRADE
5.	9TH GRADE
6.	10TH GRADE
7.	11TH GRADE
8.	12TH GRADE NO DIPLOMA
9.	HIGH SCHOOL GRAD-DIPLOMA OR EQUIV (GED)
10.	SOME COLLEGE BUT NO DEGREE
11.	ASSOCIATE DEGREE-OCCUPATIONAL/VOCATIONAL
12.	ASSOCIATE DEGREE-ACADEMIC PROGRAM
13.	BACHELOR'S DEGREE (EX: BA, AB, BS)
14.	MASTER'S DEGREE (EX: MA, MS, MEng, MEd, MSW)
15.	PROFESSIONAL SCHOOL DEG (EX: MD, DDS, DVM)
16.	DOCTORATE DEGREE (EX: PhD, EdD)

---

### 4. fam_income (HEFAMINC) - Numerical/Categorical
Family Income expressed as an integer representing income groups. <br/>
Valid Entries: <br/>
1.	LESS THAN $5,000
2.	5,000 TO 7,499
3.	7,500 TO 9,999
4.	10,000 TO 12,499
5.	12,500 TO 14,999
6.	15,000 TO 19,999
7.	20,000 TO 24,999
8.	25,000 TO 29,999
9.	30,000 TO 34,999
10.	35,000 TO 39,999
11.	40,000 TO 49,999
12.	50,000 TO 59,999
13.	60,000 TO 74,999
14.	75,000 TO 99,999
15.	100,000 TO 149,999
16.	150,000 OR MORE

---

### 5. num_in_house (HRNUMHOU) - Numerical
Total number of persons living in household. <br/>
Valid Entries: 0 - 16

---

### 6. num_child (PRNMCHLD) - Numerical
Total number of own children under 18 years of age. <br/>
Valid Entries: 0 - 99

---

### 7. sex (PESEX) - Categorical
Valid Entries: 1 Male, 2 Female

---

### 8. marital (PEMARITL) - Categorical
Marital Status. <br/>
Valid Entries:
1.	MARRIED - SPOUSE PRESENT
2.	MARRIED - SPOUSE ABSENT
3.	WIDOWED
4.	DIVORCED
5.	SEPARATED
6.	NEVER MARRIED

---

### 9. race (PTDRACE) - Categorical
Valid Entries: <br/>
1.  White Only	
2. 	Black Only	
3.  American Indian, Alaskan Native Only	
4.  Asian Only	
5.  Hawaiian/Pacific Islander Only		
6.  Other/Mixed

---

### 10. region (GEREG) - Categorical
Valid Entries: <br/>
1.  Northeast
2. 	Midwest
3.	South
4.	North

---

### 11. state (GESTIFPS) - Categorical
Valid Entries: <br/>
01	AL	|	30	MT |
02	AK	|	31	NE | 
04	AZ	|	32	NV |
05	AR	|	33	NH |
06	CA	|	34	NJ |
08	CO	|	35	NM |
09	CT	|	36	NY |
10	DE	|	37	NC |
11	DC	|	38	ND |
12	FL	|	39	OH |
13	GA	|	40	OK |
15	HI	|	41	OR |
16	ID	|	42	PA |
17	IL	|	44	RI |
18	IN	|	45	SC |
19	IA	|	46	SD |
20	KS	|	47	TN |
21	KY	|	48	TX |
22	LA	|	49	UT |
23	ME	|	50	VT |
24	MD	|	51	VA |
25	MA	|	53	WA |
26	MI	|	54	WV |
27	MN	|	55	WI |
28	MS	|	56	WY |
29  MO	|

---

### 12. citizen (PRCITSHP) - Categorical
Citizenship Status. <br/>
Valid Entries: <br/>
1. NATIVE, BORN IN THE UNITED STATES
2. NATIVE, BORN IN PUERTO RICO OR OTHER U.S. ISLAND AREAS 
3. NATIVE, BORN ABROAD OF AMERICAN PARENT OR PARENTS
4. FOREIGN BORN, U.S. CITIZEN BY NATURALIZATION
5. FOREIGN BORN, NOT A CITIZEN OF THE UNITED STATES

---

### 13. worker_class (PRCOW1) - Categorical
Class of worker. <br/>
Valid Entries: <br/>
1. FEDERAL GOVT
2. STATE GOVT
3. LOCAL GOVT
4. PRIVATE (INCL. SELF-EMPLOYED INCORP.)
5. SELF-EMPLOYED, UNINCORP.
6. WITHOUT PAY

---

### 14. industry (PRJIND1) - Categorical
Industry of worker. <br/>
Valid Entries: <br/>
1. Agriculture, forestry, fishing, and hunting				
2. Mining									
3. Construction										 
4. Manufacturing									
5. Wholesale and retail trade							
6. Transportation and utilities					      
7. Information									
8. Financial activities								
9. Professional and business services
10. Educational and health services						
11. Leisure and hospitality							
12. Other services									
13. Public administration								
14. Armed Forces

---

### 15. occupation (PRDTOCC1) - Categorical
Occupation of worker. <br/>
Valid Entries: <br/>
1. Management, business, and financial occupations	
2. Professional and related occupations					
3. Service occupations							
4. Sales and related occupations					
5. Office and administrative support occupations	
6. Farming, fishing, and forestry occupations			
7. Construction and extraction occupations				
8. Installation, maintenance, and repair occupations	
9. Production occupations						
10. Transportation and material moving occupations	
11. Armed Forces

---

### 16. faminc_50 (Derived from fam_income) - Binary Categorical
Valid Entries: 0 and 1, 1 meaning income is $50,000 or greater

---

### 17. ismarried (Derived from marital) - Binary Categorical
Valid Entries: 0 and 1, 1 meaning the individual is married 






