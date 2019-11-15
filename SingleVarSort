def sort(arr,n):
    c = 0
    while(c < n-1):
        if(arr[c] < arr[c+1]):
            arr[c],arr[c+1] = arr[c+1],arr[c]
            if(c > 0):
                c = c-1
            #endif
        else:
            c = c+1
        #end if
    #end while
    
def prt(arr):
    for i in arr:
        print(i,end = " ")
    print()
i = int(input())
ls = list()
for j in range(i):
    l = int(input())
    ls = list(map(int, input().split()))
    sort(ls,l)
    prt(ls)
        
        
