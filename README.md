# func127
calculations of marks using functios
total=0
def add_subject_marks():
    global total
    marks=int(input("enter marks of a subjet:"))
    total+=marks
    return marks
print("subject1 marks :",add_subject_marks())
print("subject1 marks :",add_subject_marks())
print("subject1 marks :",add_subject_marks())
print("total marks stored in global:",total)
