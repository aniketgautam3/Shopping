# Shopping

#### 1. Creating a new folder called Shopping.

```bash
mkdir Shopping
```
#### 2. Initialing a new git repo inside of the Shopping folder (make sure you're not already inside of a Git repo!)

```bash
git init
```

#### 3. Make a new file called yard.txt

```bash
touch yard.txt
```

#### 4. Make a new file called groceries.txt

```bash
touch groceries.txt
```

#### 5. Making a commit that includes both empty files. The message should be "create yard and groceries lists"

```git
git status
git add .
git commit -m "create yard and groceries lists"
git push origin main
```

#### 6. In the yard.txt file, added the following changes:
- 2 bags of potting soil
- 1 bag of worm castings

#### 7. In the groceries.txt file, add the following:
- 4 tomatoes
- 6 shallots
- 1 fennel bulb

#### 8. Make a new commit, including ONLY the changes from the groceries.txt file. The commit message should be "add ingredients for tomato soup"

```git
git status
git add groceries.txt
git commit -m "add ingredients for tomato soup"
git push origin main
```
#### 9. Make a second commit including ONLY the changes to the yard.txt file. It should have the commit message "add items needed for garden box"

```git
git status
git add yard.txt
git commit -m "add items needed for garden box"
git push origin main
```
#### 10.Next up, add the following line to the end of groceries.txt
- couple of seed potatos

#### 11.In the yard.txt file, change the first line so that it says "3 bags of potting soil" instead of "2 bags of potting soil"
- 3 bags of potting soil

#### 12.Making a commit that includes the changes to BOTH files. The message should read "add items needed to grow potatoes"

```git
git status
git add .
git commit -m "add items needed to grow potatoes"
git push origin main
```

#### 13.Using a Git command to display a list of the commits. You should see 4!

```git
git log
```


