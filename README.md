# Program-to-print-the-result-in-main

def AP(m1, m2, m3):
    tot = m1 + m2 + m3
    avg = tot / 3
    per = (tot / 150) * 100
    print("Average = %0.2f  Percentage = %0.2f" % (avg, per))


def main():
    i = int(input("Enter sub1 marks out of 50 : "))
    j = int(input("Enter sub2 marks out of 50 : "))
    k = int(input("Enter sub3 marks out of 50 : "))
    AP(i, j, k)


main()


Output:
Enter sub1 marks out of 50 : 49
Enter sub2 marks out of 50 : 44
Enter sub3 marks out of 50 : 46
Average = 46.33  Percentage = 92.67

