# cpassword
3times password

#include <string.h>

int main() {
	printf("welcome to bit\nwrite dowm your\n");
	char password[20] = "1234";
	char write[20] = { 0 };
	int i = 0;

	for (; i < 3; i++) {
	scanf("%s", &write);
		if (strcmp(password, write) == 0) {  //if = return 0
			printf("yes\n");
			break;
		}
		else {

		}
	}if (i==3)
			printf("ynobye\n");
	return 0;
}
