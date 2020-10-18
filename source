#include <iostream>
#include <windows.h>
#include <string>
#include <cstdlib>

using namespace std;


int main()
{
	string username;
	string password;
	string regpassword;
	string regusername;
	int abc = 0;

	string hwid;
	HW_PROFILE_INFO hwProfileInfo;
	if (GetCurrentHwProfile(&hwProfileInfo)) {
		hwid = hwProfileInfo.szHwProfileGuid;
	}

	while (abc < 3)
	{
		cout << "Enter your name:\n";
		cin >> username;
		system("test&cls");
		cout << "Enter your password:\n";
		cin >> password;
		system("test&cls");

		if (username == "drabtime" && password == "suka" && hwid == "{3e1683d5-fb2f-11e9-8374-806e6f6e6963}" || username == "elay" && password == "7" && hwid == "{09161585-ae73-11ea-9eba-806e6f6e6963}" || username == "suka" && password == "123") {
			printf("Welcome ");
			cout << username;
			printf("!!! We hope you enjoy!!\n");
			system("pause");
			break;
		}
		else {
			printf("Login Attemp failed.\n");
			system("pause");
			system("test&cls");
			abc++;
		}
	}
	if (abc > 2) {
		printf("Too many tries.\n");
		system("pause");
	}
	return 0;
}



