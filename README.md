- 👋 Hi, I’m @ZHY13SF
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ZHY13SF/ZHY13SF is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
enum Sex
{
	MALE=6,
	FEAMLE,
	SECRET,
};
int main()
{
	enum Sex s = MALE;
	printf("%d", MALE);
	printf("%d", FEAMLE);
	printf("%d", SECRET);

	return 0;
}




#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int Max(int x, int y)
{
	if (x >= y) {

		return x;
	}
	else {
		return y;
	}
}
                
int main()
{
	int num1 = 0;
	int num2 = 0;
	int ans = 0;
	printf("输入两个数以比较大小>:");
	scanf("%d%d", &num1, &num2);
	ans = Max(num1, num2);
	printf("%d\n", ans);

	return 0;
}
