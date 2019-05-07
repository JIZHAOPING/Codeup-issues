# **问题集合**

### Contest100000574 - 《算法笔记》2.10小节——C/C++快速入门->黑盒测试
#### 问题 H: A+B 输入输出练习VIII
##### *错误写法*
![mistake](https://raw.githubusercontent.com/JIZHAOPING/Codeup-issues/master/imgs/_8GV1X%25NP%40CD2J%5D_)1SL%7D1U.png)
##### ***正确写法***
```
	int main(){
		int N,M,a;
		scanf("%d",&N);
		while(N--){
			int sum=0;
			scanf("%d",&M);
			for(int i=0;i<M;i++){
					scanf("%d",&a);
					sum+=a;
				}
			printf("%d\n\n",sum);		
		}
		return 0;
	}
```
