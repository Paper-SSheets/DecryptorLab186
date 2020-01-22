# DecryptorLab186
Lab for SE186X, a course at Iowa State.

## Starting Point
1) Copy the `.gitignore` file that I have into the root of your repository. 
2) Know where to get the `Decryptor.java` file.

## Steps to Reproduce
1) First, I cloned this repository.
2) In Eclipse, open the cloned repository as a workspace.
3) You will note that there is nothing in the "package explorer" in the left. Go to `File`->`New`->`Java Project`, name the project `Decryptor`, and click `Finish`.
4) Right click on 'src' and create a new `package` named `lab`. Place `Decryptor.java` into this `lab` package.
5) As of right now, you should have a file structure of `Decryptor/src/lab/Decryptor.java`. You should be able to run this file by clicking the green arrow, if there are any compiler errors, fix them. Eclipse should be smart enough to tell you where the compiler errors are and you can fix them by hovering over the red in the file and selecting the correct fix; likely the problems are not including `package lab` at the top of your file, and `public class DecryptorSkeleton` should be renamed to `public class Decryptor`.
6) Now is a good time to `git add .`, `git commit . -m "<message>`, `git push`.
7) At this point, running the program should produce this in the terminal at the bottom of Eclipse.
```
[101001, 1001101, 1010011, 11010, 10, 10000000, 1001100, 1101011, 11, 11010, 1001000, 110101, 1001100, 1111111, 11100, 10101, 10, 10000000, 1001100, 1101011, 1011101, 1, 1100, 1011101, 11010, 111, 111010]
[101001, 1001101, 1010011, 11010, 10, 10000000, 1001100, 1101011, 11, 11010, 1001000, 110101, 1001100, 1111111, 11100, 10101, 10, 10000000, 1001100, 1101011, 1011101, 1, 1100, 1011101, 11010, 111, 111010]
[101001, 1001101, 1010011, 11010, 10, 10000000, 1001100, 1101011, 11, 11010, 1001000, 110101, 1001100, 1111111, 11100, 10101, 10, 10000000, 1001100, 1101011, 1011101, 1, 1100, 1011101, 11010, 111, 111010]
!
```
7) Your team members should do a `git pull` each time changes are pushed to the remote, so that should be done now.
8) Now, we finish the lab, you can refer to the comments in the code for expected outputs.
9) One of the team members finished the first method, added it to the stage, committed, and pushed it. The other team members should `git pull` to update their file with theirs.
10) Do the same thing with the remaining methods, the final output should look like this:
```
[41, 77, 83, 26, 2, 128, 76, 107, 3, 26, 72, 53, 76, 127, 28, 21, 2, 128, 76, 107, 93, 1, 12, 93, 26, 7, 58]
[40, 75, 80, 25, 0, 125, 75, 105, 0, 25, 70, 50, 75, 125, 25, 20, 0, 125, 75, 105, 90, 0, 10, 90, 25, 5, 55]
[8, 15, 16, 5, 0, 25, 15, 21, 0, 5, 14, 10, 15, 25, 5, 4, 0, 25, 15, 21, 18, 0, 2, 18, 5, 1, 11]
hope you enjoyed your break!
```

## Afterward...
- Now that you have completed this, complete the project proposal template given to you and put it in the root of your repository. Email me once you have finished, and I'll check you off. :)

## Expectations
- I will need to see at least one commit from each team member to be satisfied to check this off. You can view commits by clicking `commits` in GitHub when you're in the root of your repository. For example, here's what my commit history looks like: https://gyazo.com/b6739f5155bafffe1eed7b905374d555
- Your repository should look similar to mine. If it includes additional files (such as .classpath, etc, it's not a huge deal.
