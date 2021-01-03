#include<iostream>
using namespace std;
 /*struct student
    { int  xuehao;
      char name[50];
      int  score;
    }xuesheng[3];*/
int main()

{ cout<<"请输入10个数"<<endl;
  int a[10],i,j,t;
  for(int i=0;i<=9;i++)
   cin>>a[i];
   for(i=0;i<=9;i++)
     for(j=i+1;j<=9;j++) 
      if(a[i]>a[j])
	  { t=a[i];
	    a[i]=a[j];
	    a[j]=t;
      	
	  }
	  for(i=0;i<=9;i++)
	  cout<<a[i]<<endl;
	  return 0;
} 
/*{
      for(int i=1;i<=3;i++)
       scanf("%d\t%s\t%f\n",xuesheng[i].xuehao,xuesheng[i].name,xuesheng[i].score);
       struct student linshi
       for( m=0;m<2;m++)
         for(b=m+1;b<3;b++)
         if(xuesheng[b].score>xuesheng[m].score)
             {   linshi=xuesheng[m];xuesheng[m]=xuesheng[b];xuesheng[b]=linshi;
             }
         for(int i=1;i<=3;i++)
         cout>>xuesheng[i]>>endl;
         return 0;*/
		 
		    
			
			
			
	   
   







