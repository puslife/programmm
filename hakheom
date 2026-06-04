a = []

while True:

    b = input("1추가 2삭제 3보기 4종료 : ")

    if b == "1":

        c = input("과목명 : ")
        d = int(input("학점 : "))
        e = float(input("평점 : "))

        a.append([c,d,e])

    elif b == "2":

        for i in range(len(a)):
            print(i,a[i])

        f = int(input("번호 : "))
        a.pop(f)

    elif b == "3":

        g = 0
        h = 0

        for i in range(len(a)):
            print(a[i])

            g += a[i][1]
            h += a[i][1] * a[i][2]

        if g > 0:
            print(round(h/g,2))

    elif b == "4":
        break
