1) values added:  20
2) final result:  20
3) We shouldn't use var because that makes it globally accessible, which can lead to errors down the road.
4) values added:  20
5) Line 13 prints an error because we used let, which defines result within the if block, outside result is not visible.
6) The code errors and we receive "TypeError: Assignment to constant variable." This is because we are attempting to reassign a const variable.
7) The code errors and we receive "TypeError: Assignment to constant variable." This is because we are attempting to reassign a const variable.