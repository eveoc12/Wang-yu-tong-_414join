# Wang-yu-tong-_414join
Hello word! 
我是数技02王雨桐
你好，我是新媒体学院数技2班王雨桐，喜欢建模，ps，动漫，听音乐等等，
游戏制作流程，了解游戏开放知识
![image](https://github.com/eveoc12/Wang-yu-tong-_414join/assets/147157295/20594405-6bf2-4f43-ab91-369fa882ce13)
#include<stdio.h>
int SUBI(int );//函数声明；
int SUBI(int a[20])
{
	int nums[20];//冒泡排序；
	int i, j, temp;
	for (i = 0; i < 10 - 1; i++) {
		for (j = 0; j < 10 - 1 - i; j++) {
			if (nums[j] > nums[j + 1]) {
				temp = nums[j];
				nums[j] = nums[j + 1];
				nums[j + 1] = temp;

			}
		}
	}
	for (i = 0; i < 10; i++) {
		printf("%d ", nums[i]);
	}
	printf("\n");
	return 0;
}

int main()  {   //主函数；输入数组；
	int kit; 
	int a [20];
	printf("请输入数组");
	scanf_s("%d",a);
	kit = SUBI(a[20]);  //传递数值；
	printf(" kit = %d", kit);
	return 0;
}


