# hello-world
while True:
    try:
        n,m = map(int,input().split())
        s1 = list(map(int,input().split()))         
        s2 = list(map(int,input().split()))
        s = sorted(list(set(s1)|set(s2))) 
        s=map(str,s)
        print(" ".join(s))
    except:
        break
