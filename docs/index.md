Hi! This is my Github site where I show off the game that I made for my Programming I final!
Blaise Carley - Creator


This is the UI for the game! It was created using windows forms.

![horseerror](https://private-user-images.githubusercontent.com/153130544/290957712-83ab3ad5-4ae0-4e2e-9403-bc6f13d3798e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDI2ODQ4ODAsIm5iZiI6MTcwMjY4NDU4MCwicGF0aCI6Ii8xNTMxMzA1NDQvMjkwOTU3NzEyLTgzYWIzYWQ1LTRhZTAtNGUyZS05NDAzLWJjNmYxM2QzNzk4ZS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjE1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIxNVQyMzU2MjBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zZjU3MTkyNmU2ZTM5YTNmYTQzZWFlMWVjNTM1ZWRjNzM4NDVlZDBhNTA1Y2NlMjM0MmRhZGVhMTIxYmI5NjdhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ESsAjdKBYd7z8lVyYRSiW5wtos6ZptE7rh_2MkbQFsg)

There are 5 Areas to travel to.

The Forest, where you can gather Wood
![forestimage](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/01886f30-8b72-45ae-9fff-f01b6902a46c)

The Town, where Trading is available
![townimage](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/02593df6-505f-4aab-a0fd-5f56123176b1)

The River, where you can gather Water
![riverimage](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/1633bbca-c2e8-47eb-8e9a-47b7fef6b8aa)

The Canyon, where you can gather Clay
![canyonimage](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/9f3b3b1e-3716-450d-8c0a-4ea6f1021ddf)

And The Mountain, where you can gather Horns
![mountainimage](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/07661ca4-e300-4d9a-baa8-6c92023dd7b8)

All of these areas are instances of the class Location, which are connected to Player and Game.
![code1](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/4c74db40-15ae-4165-ae51-d8206fcf78f8)

Within these Location instances, a corresponding item to CurrentLocation is used, in order to determine what item will be given when the
"Collect Item" button is pressed.

![code3](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/46590116-e973-4e36-9e6c-3afb039771f9)
This code here is what registers that.
![code4](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/15fcd70a-dd41-44e5-a519-63d0a5775480)
This code is for showing the proper UI elements depending on the area.
![code5](https://github.com/blaisecar/blaisecar.github.io/assets/153130544/6f57eedd-9aa4-47fd-b3f5-03035c2180e6)
This is some of the code for the Item class itself, which are objects placed into the Inventory list.

Once you bring all the items from each area and trade them to the town NPC, you win the game, getting the ultimate item!


Other projects:








