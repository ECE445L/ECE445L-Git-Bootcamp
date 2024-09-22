# Learning Enough to become "Dangerous"

Now we will do some practical excersizes to familarize you with common commands.

## Guides 
<details>
  <summary>Cloning your first repository</summary>
    * Joining a classroom
    * Adding your name
    * Getting a link
    * <code>git clone</code>
</details>

<details>
  <summary>Making your first changes</summary>

    * <code>git status</code>
    * <code>git pull</code>
    * <code>echo "test1" >> test1.txt</code>
    * <code>git add .</code>
    * <code>git commit -m "test1"</code>
      * (First Time Only) Adding your name and email
    * <code>git push</code>
</details>

<details>
  <summary>Reverting to the latest commit</summary>

  Sometimes we break our code, or even our git repository. It is useful to know a way to get back to a known good state.

  * <code>git checkout main</code>
    * This will reattach the head if you performed an operation that detached it
  *  <code>git reset --hard HEAD</code>
    * This will restore all files tracked by git to the state they were in during the last commit
  *  <code>git clean -xdf</code>
    * This will delete all untracked files in the git repositiory
</details>

<details>
  <summary>Automatic merge conflict resolution</summary>

</details>

<details>
  <summary>Manual merge conflict resolution</summary>

</details>

## Next Steps
Once you are done with these exercises continue to [ECE 445L - More features](https://github.com/ECE445L/ECE445L-Git-Bootcamp/blob/main/ECE%20445L%20-%20More%20features.md)