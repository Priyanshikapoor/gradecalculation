# gradecalculation
#include<stdio.h>
int main()
{
  int eng,maths,chem,phy,comp,total;
  printf("marks of english out of twenty",eng);
  scanf("%d",&eng);
  printf("marks of maths out of twenty",maths);
  scanf("%d",&maths); 
  printf("marks of chemistry out of twenty",chem);
  scanf("%d",&chem);
  printf("marks of physics out of twenty",phy);
  scanf("%d",&phy);
   printf("marks of computer out of twenty",comp);
  scanf("%d",&comp);
  total=eng+maths+chem+phy+comp;
  printf("total marks are ",total);
  if(total>85&&total<100)
  {
    printf("grade A")
  }
  elseif(total>70&&total<84)
  {
    printf("grade B")
  }
  elseif(total>55&&total<69)
  {
    printf("grade C")
  }
  elseif(total>40&&total<54)
  {
    printf("grade D")
  }
  else
  {
    print("grade F")
  }  
