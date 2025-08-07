<div align="center">
  <h1>CS ALP GitHub</h1>
</div>

Welcome to the GitHub repository for our ALP! <br>
This repositories stores all of your references, logs, activities, and assignments. <br>

Each activity will have their own respective folder where you will submit your assignments and activities.

## Q&A
#### **How do I submit?**
There are two ways that you can submit:

<details>
  <summary>Using the GitHub site</summary>
  <br>

  <ol>
    <li>
      Go to the respective folder for an activity. <br>
      <img src=".images/1.1_tutorial.png">
      <hr>
    </li>
    <li>
      Click the `Add file` button on the top right.<br>
      <img src=".images/1.2_tutorial.png">
      <hr>
    </li>
    <li>
      Select the `Upload files` option. <br>
      <img src=".images/1.3_tutorial.png"> <br>
      > Optionally, you can select the `Create new file` option and write your code there.
      <hr>
    </li>
    <li>
      Select your file and upload it. <br>
      <img src=".images/1.4_tutorial.png"> <br>
      <img src=".images/1.5_tutorial.png">
      <hr>
    </li>
    <li>
      Make a commit message that includes your last name and commit. <br>
      <img src=".images/1.6_tutorial.png">
    </li>
  </ol>
</details>

<details>
  <summary>Manually through the terminal</summary>
  <br>
  <ol>
    <li> Create a folder of your choosing.</li>
    <li>
      <a href="https://git-scm.com/download/win"> Install Git on your Windows system. </a><br>
      If you're using Arch Linux, run <code>sudo pacman -S git</code>
    </li>
    <li>
      Run these commands to initialize your Git folder and to copy this repository.
      <pre><code>
        git init
        git clone https://github.com/CS-ALP/CS-ALP.git
      </code></pre>
    </li>
    <li>
      Now add your files to the folder. For example, if you want to add the file `Hello`, do
      <pre><code>
        git add hello
      </code></pre>
    </li>
    <li>
      Commit your changes and push them to this repository.
      <pre><code>
        git commit -m "First commit. Hello CS-ALP!"
        git push
      </code></pre>
    </li>
    <li>
      To update your files whenever a new change is committed by someone else, do
      <pre><code>
        git pull
      </code></pre>
    </li>
  </ol>
</details>

## Other
If you have any questions or suggestions, please ask on the CS ALA Messenger group chat or DM me directly on Messenger.

<sub>
  Repository created by: @Andrei Jose R. Embarque
</sub>
