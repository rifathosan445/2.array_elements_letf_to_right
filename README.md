# 2.array_elements_letf_to_right
make a array then input "K".Print array left to right and left=0 k time.


    #include<stdio.h>
    int main()
    {
    int a[5]={1,2,3,4,5},i,k;
    scanf("%d",&k);
    int a2[5];
    int j=k;
    for(i=0;i<5;i++)
    {
          a2[j] = a[i];
          j++;
          if(j==5)
                break;
    }
  
    for(j=0;j<k;j++)
    {
           a2[j]=0;
    }
    for(j=0;j<5;j++)
    {
           printf("%d,",a2[j]);
    }
  
    return 0;
    }

