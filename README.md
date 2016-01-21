# vasimahmad-aasaanjobs
set b;
question 1;
void duplicate(int s[100])
{
static int a[100],i;
for(i=1;i<101;1++)
{
a[i]=0;
}
for(i=0;i<100;i++)
{
num=s[i];
a[num]++;
if(a[num]!=1)
{
cout<<"This number is repeated";
}}}


question 3:
void  main()
{
int a[10],i,j,min,e1,e2;
cout<<"Enter  the elements of array";
for(i=0;i<10;i++)
cin>>a[i];
for(i=0;i<10;i++)
{
for(j=0;j<10;j++)
{
if(i!=j)
{
sum=a[i]+a[j];
if(sum<0)
sum=-1*sum;
if(sum<min)
{
min=sum;
e1=a[i];
e2=a[j];
}}}}
cou<<"minimum sum is"<<min<<"of elements"<<e1<<e2;
}

