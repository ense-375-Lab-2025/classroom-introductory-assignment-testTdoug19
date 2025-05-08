# :wave: GitHub Classroom Introductory Assignment

Starter lesson for assessing GitHub Classroom use.

The goal of this assignment is to introduce learners to using GiHub Classroom assignments and to assess that learners have the necessary skill set to complete a classroom assignment.

At the end of this lesson, learners will be able to:

1. Describe what a GitHub Classroom assignment is and accept a GitHub Classroom assignment
2. Use git to complete an assignment task
3. Use GitHub features to request feedback

---

## :page_facing_up: Classroom Assignments

A [GitHub Classroom](#learn-more-assignments) assignment is a way that your teacher can distribute coding assignments or exercises to students. Assignments are distributed as GitHub [repositories](#terms). Once an assignment is accepted, students only interact with GitHub. This means students use the same industry standard tools as used by millions of developers around the world.

Assignments can make use of GitHub features to:

- grade your work
- provide a mechanism to get feedback from your teacher
- make commenting on code easier
- set a deadline for assignment completion

<details>
  <summary id="learn-more-assignments">:book: Learn more about GitHub Classroom</summary>

  GitHub Classroom is a tool that helps your teacher organize and manage GitHub repositories that are used for class exercises and assessments. GitHub Classroom automates repository creation and access control, making it easy to distribute starter code and collect assignments on GitHub.

  A GitHub Classroom assignment is a GitHub repository with access control setup so both you and your teacher can access it. When you accept an assignment, GitHub Classroom will automatically create a new repository for you. The assignment repository will belong to your course's organization account on GitHub, but you and your teacher will have access to it.

  Once an assignment has been accepted, students no longer interact with GitHub classroom. They just interact with GitHub.
</details>

<details>
  <summary id="assignment-steps">Accepting Classroom assignment steps</summary>

  1. Follow the assignment link your teacher gave you.
  2. Sign in to GitHub. If you don't have a GitHub account you will need to [create one](https://github.com/join).
  3. If it's your first time accepting an assignment for the class you may need to select your name from the class roster. This makes it easier for your teacher to identify you. (Your teacher may find it difficult to recognize your GitHub username.)
  4. Wait for the assignment to copy to new repository. This usually only takes a few seconds.
  5. Refresh the page.
  6. If the new assignment repository is ready, there will be a link to it on the page. Follow the link.

</details>

| :keyboard: Activity - Accept assignment |
|:---|
| <p>Chances are, if you are reading this, you have already accepted the assignment and have completed the task. Well done. :tada:<br />(You might need to refresh the page to see the completion status).</p><p>If you haven't accepted the assignment yet and are reading this from a central site, ask your teacher for the link to the assignment, then follow the [steps](#assignment-steps) to accepting a classroom assignment. |

---

## :octocat: Git and GitHub

In order to complete classroom assignments, you will need to be able to use git and be familiar with GitHub.

### :large_orange_diamond: git

Git is a software tool for tracking changes across a set of files. It helps programmers to undo changes that break their code and to work collaboratively with others when developing software.

If you are already family with using git, continue on.  
If you are new to using git, please __complete the MS Learn course: :book:  [Introduction to Git](https://docs.microsoft.com/en-us/learn/modules/intro-to-git/)__ before continuing.

### :octocat: GitHub

GitHub is a cloud based service for hosting Git repositories. It provides a website, command-line tools, and workflow that makes it easier for developers and users to work together.

:tv: [Video: What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)

To learn more about GitHub and its features, please __complete the MS Learn course: :book: [Introduction to GitHub](https://docs.microsoft.com/en-us/learn/modules/introduction-to-github/)__.

|:keyboard: Activity - Make commit |
|:---|
| <p>Make a commit to this assignment repo.</p><p>Edit the editme.md file and add a question for your teacher. When you have finished editing the file, save the changes and commit them to this repository.</p><p>You can either use the editing tools on GitHub to do this, or clone this repository to your local computer, make the changes, commit them and push the commit back to GitHub.  Here is an examle to commit your changes from the command line.</p> 

```bash

> git commit -am "Making some changes to my code "

```

This stages and commits your changes in one command.


|

---

## :pencil: Push your commit

If you cloned your repository to a local machine then you must push your changes to your GitHub repository.

:keyboard: Activity - Push |
|:---|
| There are a number of ways you can push your changes to your GitHub repository.  You may use an IDE or the command line.  If you use the command line you can push your commit like so:

```bash

> git push

```
This will ensure that your latest changes to your assignment are updated to your repository and your assignemnt is ready to be graded.
|

---

## :dart: Knowledge Check

Complete the knowledge review quiz. There are five multiple choice questions on the topics covered in this lesson.

| :keyboard: Activity - Review quiz |
|:---|
| Edit the quiz.md file and add your answers to each question on the same line as and after where it says 'Answer: '. When you have finished answering the questions, save the file, commit the changes and push your commit back to GitHub. |

---

## :books: Further Resources

<details>
  <summary id="terms">Terms</summary>

  ### Repository<a id="repository"></a>

  A repository is a collection of all your project's files and revision history. You can think of it as a folder that contains all of your project's files. You can work within a repository alone or invite others to collaborate with you on those files. Repositories are called "repos" for short.

  ### GitHub Flow<a id="github-flow"></a>

  The GitHub flow is a lightweight branch-based workflow that allows you to experiment and collaborate on your projects easily.

  Learn more about GitHub Flow:
  - [Interactive Guide](https://guides.github.com/introduction/flow/)
  - [Video: GitHub Flow](https://www.youtube.com/watch?v=PBI2Rz-ZOxU)

</details>