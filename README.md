% 1. Title: PISA Brazil Dataset

% 2. Sources:
%    (a) Original owners: OECD (Organisation for Economic Co-operation and Development)
%    (b) Donor of database: Researcher Name (email@example.com)
%                           Research Center
%                           Institution
%                           Address
%                           Phone
%    (c) Date received: 15 January 2025

% 3. Relevant Information:
%       This dataset includes anonymized data from Brazilian students who participated in the PISA assessment. 
%       It evaluates students' proficiency in reading, mathematics, and science.

% 4. Number of Instances: 1000 (example size)

% 5. Number of Attributes: 6 plus class

% 6. For Each Attribute: (all numeric-valued except the class)
%    1. Gender (1 = Male, 2 = Female)
%    2. Age (years)
%    3. Reading score (0-1000)
%    4. Mathematics score (0-1000)
%    5. Science score (0-1000)
%    6. Socioeconomic status (0 = low, 1 = medium, 2 = high)
%    7. Class variable (performance level: low, medium, high)

% 7. Missing Attribute Values: None

@relation pisa_brazil

@attribute 'gender' {1, 2}
@attribute 'age' numeric
@attribute 'reading_score' numeric
@attribute 'math_score' numeric
@attribute 'science_score' numeric
@attribute 'socioeconomic_status' {0, 1, 2}
@attribute 'class' {low, medium, high}

@data
1,15,400,380,420,0,medium
2,16,600,650,610,1,high
1,15,300,290,310,0,low
2,17,720,710,730,2,high
1,16,500,480,520,1,medium
2,15,450,470,440,1,medium
1,17,250,260,240,0,low
2,16,560,540,550,2,high
1,15,380,390,370,0,low
2,16,480,500,490,1,medium

