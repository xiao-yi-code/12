# 12
12
int main()//写一个代码，在数组中找到某一个数字。
{
	int arr[] = {1,2,3,4,5,6,7,8,9,10};
	int k = 7;
	int i = 0;
	int sz = sizeof(arr)/sizeof(arr[0]);//sz等于10
	for(i=0;i<sz;i++)
	{
	  if(k == arr[i])
	  {
		  printf("找到了，下标是：%d\n",i);
		  printf("找到了，下标是：%d\n",sz);
		  break;
	  } 
	  if(i == sz)
	  {
		  printf("找不到你要的数字!\n");
	  }
	}
   return 0;
}
