# __Ivanov Gleb__
![Image](/Images/DSC_2503.JPG "Image")

## _Contacts_

| Platform | Link |
|:--------:|:----:|
| Telegram | @ssl33pl3ss |
| Discord | ssl33pl3ss#3639 |
| Discord (rs-school) | Gleb Ivanov (@ssl33pl3ss) |
| E-mail | sball13@mail.ru |

## _About myself_
I'm Gleb, 17 y.o. Was born in Saratov, Russia and still live in here. I'm in my third year of College of Radioelectronics on IT faculty. Responsible, teachable, fast learner, ready to get new information and work with it.

## _Skills_
- C++
- Basics of WPF/C#, HTML/CSS, Git
- Little bit of shell scripting (mostly bash and fish)
- Graphic redactors (Photoshop, Krita, GIMP, Illustrator, Coreldraw, etc.)

## _Code examples_
##### Codewars task:
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case).

##### Examples:
"the-stealth-warrior" gets converted to "theStealthWarrior"

"The_Stealth_Warrior" gets converted to "TheStealthWarrior"

##### C++ code:
```c
#include <iostream>
#include <string>
#include <cctype>

using namespace std;

string to_camel_case(string text) {
  string res;
  for(unsigned int i = 0; i < text.size(); i++){
    if(text[i] == '-' || text[i] == '_'){
      if(islower(text[i + 1])) text[i+ 1] = toupper(text[i + 1]);
      res += text[i + 1];
      i++;
    }
    else res += text[i];
  }
  return res;
}
```

## _Work experience_
[RS School CV](https://github.com/ssl33pl3ss/rsschool-cv)

## _Education_
- 9 years of school
- In the third year of college at the moment
- Couple of years ago finished [MSHP](https://informatics.ru/) courses

## _English level_
Something about __B2__. Was constantly learning it since I was 7 y.o.
