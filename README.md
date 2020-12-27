# internshipsolution

Provides solution to given problem

Assumptions 

1)Players don't care about small errors when their rank is low, for ex- players don't care if their rank is 109,548 but actual rank should be 109,768 
but they do care if their rank is 108 or 109 or any other good rank

2)Players who have played for less than 4 mpnths or play infrequently(3 or less times a month) don't havea high rank

3)Players with less than 100,000 score have less than 2000th rank

Design upwards and lower scalibilty-

1)It is an overkill for anything less than 8000-12,000 users 

2)The algorithm is too single and has too little efficiency for anything more than 70-100 million users

Pros-

1)Faster and less costly to implement than brute force

2)Easy to code and requires low overhead

3)Reasonably accurate 

4)Uses very few number of variables making it faster, cheaper and easier to use with very low chances of errors

Cons-

1)Can be a little inaccurate for low ranking gamers

2)Hard to scale beyond a certain point arounf 70-100 mllion players as computations costs for even this become too high and inaccuracies will start
to creep up in the system

3)Has few variable making easy to code,implement and oversee but hard to scale beyond a certain pint where more complicated
variable+Tensorflow models must be utilised
