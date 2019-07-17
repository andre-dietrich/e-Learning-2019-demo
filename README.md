<!--
author:   André Dietrich

email:    andre.dietrich@ovgu.de

version:  0.0.1

language: en

narrator: US English Female

comment:  This is a short presentation (live-demo) of online-course development
          with LiaScript.

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js


import:   https://raw.githubusercontent.com/liaTemplates/rextester/master/README.md
          https://raw.githubusercontent.com/liaTemplates/vtk/master/README.md


-->

# e-Learning-2019-demo

Project-site: https://LiaScript.github.io

    {{1}}
> See the main presentation at: https://github.com/andre-dietrich/e-Learning-2019
>
> https://LiaScript.github.io/course/?https://raw.githubusercontent.com/andre-dietrich/e-Learning-2019/master/README.md


    {{2}}
> Demo at GitHub: https://github.com/andre-dietrich/e-Learning-2019-demo
>
> Demo at LiaScript:
>
> https://LiaScript.github.io/course/?https://raw.githubusercontent.com/andre-dietrich/e-Learning-2019-demo/master/README.md


## Background & Main Problem

    {{0-1}}
!?[eLab](https://www.youtube.com/watch?v=bICfKRyKTwE)<!-- style="width: 100%; height: 60vw;" -->

    {{1}}
![tower of babel](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Pieter_Bruegel_the_Elder_-_The_Tower_of_Babel_%28Rotterdam%29_-_Google_Art_Project_-_edited.jpg/959px-Pieter_Bruegel_the_Elder_-_The_Tower_of_Babel_%28Rotterdam%29_-_Google_Art_Project_-_edited.jpg)<!-- style="width: 100%" -->

## Markdown

You can use common
[Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
syntax to create your course, such as:

1. Lists
2. ordered or

   * unordered
   * ones ...


| Header 1   | Header 2   |
| :--------- | :--------- |
| Item 1     | Item 2     |


### Multimedia

https://soundcloud.com/flatbushzombies/crown-feat-portugal-the-man

https://www.youtube.com/watch?v=8pTEmbeENF4


### Animations and Text-Output





      --{{2 Russian Female}}--
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном
Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по
разметке текста в электронных письмах...




## Charting


## Quizzes


## Executable Code

A drawing example, for demonstrating that any JavaScript library can be used, also for drawing.

```javascript
// Initialize a Line chart in the container with the ID chart1
new Chartist.Line('#chart1', {
  labels: [1, 2, 3, 4],
  series: [[100, 120, 180, 200]]
});

// Initialize a Line chart in the container with the ID chart2
new Chartist.Bar('#chart2', {
  labels: [1, 2, 3, 4],
  series: [[5, 2, 8, 3]]
});
```
<script>@input</script>

<div class="ct-chart ct-golden-section" id="chart1"></div>
<div class="ct-chart ct-golden-section" id="chart2"></div>


### Macros

https://github.com/liaTemplates/Rextester

```cpp hello.c
#include <stdio.h>

int main(void)
{
  printf("Hello, world!");
  return 0;
}
```
@Rextester.C

### Templates

https://github.com/liaTemplates/


> __Note:__ This might take a while, to load and render the vtk data set within the browser.
>
> `@VTK.load(https://data.kitware.com/api/v1/file/58e665158d777f16d095fc2e/download)`

@VTK.load(https://data.kitware.com/api/v1/file/58e665158d777f16d095fc2e/download)

# Finally

* LiaBooks: https://github.com/LiaBooks
* Previewer: https://atom.io/packages/liascript-preview
* Snippets: https://atom.io/packages/liascript-snippets


# Thx

``````````
      +10-15V           ___0,047R
      *---------o-----o-|___|-o--o---------o----o-------.
    + |         |     |       |  |         |    |       |
    -===-      _|_    |       | .+.        |    |       |
    -===-      .-.    |       | | | 5k2    |    |       |
    -===-    470| +   |       | | |        |    |      _|_
    - |       uF|     '--.    | '+'       .+.   |      \ / LED
      +---------o        |6   |7 |8    1k | |   |      -+-
             ___|___   .-+----+--+--.     | |   |       |
              -═══-    |            |     '+'   |       |
                -      |            |1     |  |/  BC    |
               GND     |            +------o--+   54999 |
                       |            |      |  |`>       |
                       |            |     ,+.   |       |
               .-------+            | 220R| |   o----||-+  IRF9Z34
               |       |            |     | |   |    |+->
               |       |  MC34063   |     `+'   |    ||-+
               |       |            |      |    |       |  BYV29     -12V6
               |       |            |      '----'       o--|<-o----o--X OUT
 6000 micro  - | +     |            |2                  |     |    |
 Farad, 40V ___|_____  |            |--o                C|    |    |
 Capacitor  ~ ~ ~ ~ ~  |            | GND         30uH  C|    |   --- 470
               |       |            |3      1nF         C|    |   ###  uF
               |       |            |-------||--.       |     |    | +
               |       '-----+----+-'           |      GND    |   GND
               |            5|   4|             |             |
               |             |    '-------------o-------------o
               |             |                           ___  |
               `-------------*------/\/\/------------o--|___|-'
                                     2k              |       1k0
                                                    .+.
                                                    | | 5k6 + 3k3
                                                    | | in Serie
                                                    '+'
                                                     |
                                                    GND
``````````
