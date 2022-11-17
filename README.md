#1.create list calls subjects:
subjects = ["physics", "calculus", "poetry", "history" ]

#2.create list calls grades:
grades = ["98", "97", "85", "88"]

#3.create 2-D list combining list1 and list2:
gradebook = [[subjects[0], grades[0]],[subjects[1], grades[1]], [subjects[2], grades[2]], [subjects[3], grades[3]]]
print(gradebook)

#4.a. add computer scienece grade=100
#4.b. add visual art grade= 93
gradebook.append(["computer science", 100])
gradebook.append(["visual art", 93])
print(gradebook)

#5. Remove the numerical grade for poetry and replace with Pass:
gradebook[2].remove("85")
gradebook[2].append("Pass")
print(gradebook)

6. 
last_semester_gradebook = [["Math", 95]]
full_gradebook = last_semester_gradebook + gradebook
print(gradebook)
print(full_gradebook)
