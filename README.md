# C-tutorial

# What is C?
 Actual ma vanna parda chai `C` vaneko chai general-purpose programming language ho.
 General-purpose vanne bitikai euta specialized or exact task lai navai wide range of application ma use garna milxa.
Jastai examples ko lagi:

- C Langauge: Yo chai mid level, general programming langauge ho, widely Opreating System, Compilers, ani aru system software haru develop garna lai use hunxa.
- C++ : C++ chai object-oriented programming language ho based on C Langauge ani widely application development ma use hunxa particularly application jaslai chai high degree of performance ko jarurat hunxa.

C langauge chai unix naam gareko Opreating System banauna lai develop gareko ho.

# Why C langauge (learn C Language)?

- Yo chai world ko sab vhanda popular programming langauge ho.
- Yedi C language ramrari bujyo vane aru programming haru bujna lai garo hudaina jastai: Java, C++, C#, etc, syntax haru milxa.
- C langauge ko Compilation time ekdam chado xa aru programming langauge ko tulana maa.
- C Langauge ekdamnai versatile langauge ho yo application sangai technology development ma use hunxa.

# C and C++
C suru garna vhanda paila c ra c++ ko diffrence jann jaruri xa.

- C++ C ko extension aathwa bistarko rupp ma develop gariyeko thiyo, ra duitai language ko syntax dherai similar xa.
- C ra C++ bich ko important diffrence vaneko chai C++ le  classes, object support garxa tara C le gardaina.

# Let's Start
So C suru garna vhanda paila hamlai euta text editor code lekhna lai ani arko tyo code lai translate garna lai c compiler.
- Text Editor: Notepad++, Vs Code, Dev C++ (editor + compiler yo best hunxa).
- Compiler: gcc yesle chai C code lai translate garera computer le bujena langauge banauxa.
- Basic programming ko lagi online compiler haru use garda ni hunxa jastai: [GDB](https://www.onlinegdb.com/), [Programiz](https://www.programiz.com/c-programming/online-compiler/), etc.

# Quickstart
Aaba suru ma chai C programme ko basic structure bata suru garum.
- Paila compiler kholum ani euta naya file create garum `main.c`.
Tespaxi Hello World! print garney code lekhum:
```C
#include<stdio.h>

int main(){

    printf("Hello World!);
    return 0;
}
```
Mathi lekhiyeko C code bujnu vayo ki nai? Bujnu vayo vane thikai xa, Bujnu vayena vane pani thikai xa aaba hami mathi ko code lai tukra tukra parera bujna try garxum.

- Yo mathi code lai maile jasari lekhnus tapai le choose garna vako compiler ma lekhnus. 
` Maile chai Dev C++ use garey:

![image](https://user-images.githubusercontent.com/67673221/209978594-896b28be-18e1-4570-8e91-6bb330173441.png)



So aaba yo code lai run gari herum hai ta output aauxa ki aaudain raixa vanera.
`Note: Tapaile code lai run garna vhanda paila compile garna parney hunxa ani matra tapai ko code le output dinxa.`

![image](https://user-images.githubusercontent.com/67673221/209978704-452ab55e-f44c-4e0e-a82f-68b4657956ba.png)


Yedi tapai le lekhnu vako c code le `Hello World!`  output diyo vane Congratulation! Tapai le pailo C program lekhnu vayo.

# Syntax
Tapai le  code lekhera run garnu ta vayo aaba teslai bujna lai tyo code lai part part ma break garxaum, tapai le aajha ramrari bujnu hunxa:
Yeso aaba tapai le vharkhar lekhnu vako code ko 1st line ma hernus ta tapaile:

`#include <stdio.h>` lekhnu vako xa yo line le stdio.h vanne file lai tapai ko program ma include garauxa stdio vaneko chai `standard input/output` arthat yo file ko help bata tapai le aafno lekhiyeko code ma input ra output lina ra dina paunu hunxa.

For Example: 

Mathi `Line 5` ma `printf()` lekhnu vako xa yo function le Output diney kaam garxa, jastai tapai le mathi printf ko bracket vhitra Hello World! Lekhnu vako thiyo.

Teslai `printf()` vanne function le print garera output ma Hello World! dekhaidiyo.

Ajhai bujnu vayena? Chinta nalinuhos yedi tapaile `#include <stdio.h>` le kasari  kaam garxa vanera bujnu vayeko xaina vane, yeslai kehi euta chiz (something) ko rupp ma linu hos laagbaag tapaile lekhnu vako hareko program haru ma use hunxa.


- Aaba line 3 ma hernuhos arko kura jun jaile tapaile leknu vako c program ma dekha parxa `main()`. Yeslai chai main function vaninxa tapaile `{}` curly bracket vhitra lekhnu vayeko code lai compiler le execute garxa or execute hunxa.
- Line 5 ma `printf()` function xa jun chai screen ma output dina lai use hunxa, jastai mathi ko code ma `Hello World!`.

- Important kura C code ko statement chai jaile semicolon `;` le end garxa.
- Line 7 ma lekhiyeko `return 0;` le chai main function lai close or end garxa.
- Line 8 ma chai curly bracket close gareko xaum hamle ekchoti bracket open garepaxi teslai compulsory close garnai parxa.

# C Output 
Aaba hamle kei kura or value print garna paryo vane hamle `printf()` function use garxaum:

```C
#include <stdio.h>

int main(){
    printf("Orphic");
    return 0;
}
```
Output:`Orphic`

Hamle jati pani `printf()` use garna pauxa.
```C
#include <stdio.h>

int main(){
    printf("Orphic");
    printf("Rethink, Recode!");
    return 0;
}
```
Output: `OrphicRethink, Recode!`

Tapaile Note garna parne kura chai k ho vaney printf le print matra garxa naya line ma print garaudaina.

Naya printf() ko content lai naya line ma print garuna last ma `\n` use garna parxa.

```C
#include <stdio.h>

int main(){
    printf("Orphic\n");
    printf("Rethink, Recode!");
    return 0;
}
```
Output: 
```
Orphic
Rethink, Recode!
```
Hamle `\n` character use garesi tala ko printf ko content naya line ma print vayo.

# Comments in C
Simply, Tapaile tapai ko sathi ko photo ma comment garnu hunxa ni testai ho yesma ni comments use garera certain block of code lai explain garna or remainder ko lagi use garinxa.

 - Singled-Lined Comments (//)
 - Multi-Lined Comments (/*   */)

 Aaba hami yo mathi comment character lai hamro code ma use garxaum.

 ```
 #include <stdio.h>

 int main(){
// this is single line comment
/* this is
multi-line comments
*/
     printf("Hello World!");
     return 0;
 }
 ```
 Output:`Hello World!`

Hamle Comments ma lekheko kura haru lai compiler le purai ignore garxa.






