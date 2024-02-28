# hello-world of development
Here I will document the lessons I learn from Sheldon regarding many major aspects of development which includes the following:

## Git
<details>
    <summary>more info</summary>
    <br>
      The Git section will cover 4 main Git branching strategies.
    <br>
    <br>
    <details>
      <summary>GitFlow</summary>
      <br>
        A strategy ideal for intricate projects, organizes development and releases across multiple branches. Supports parallel feature feature development, streamlined release management, and a clear path for hotfixes.
      <br>
      <br>
      With this flow we maintain 5 types of branches: <br>
      Main: Stable, direct to production.<br>
      Develop: Unstable, all feature changes will be pushed here.<br>
      Feature: Check out from Develop branch, and push changes to it.<br>
      Hotfix: Check out from Main, push changes to main and develop.<br>
      Release: Semi-stable, ready to release, following with a few bugfixes. Checkout from Develop and push to both Main and Develop.<br><br>
      Drawbacks are maintaining a Develop branch long-term. Also changes in Hotfix and Release need to push to both Main and Develop for sync. The git history would look very messy and hard to follow.
    </details>
      <br>
      <details>
      <summary>GitHub Flow</summary>
      <br>
      <br>
      <br>
    </details>
      <br>
    <details>
      <summary>GitLab Flow</summary>
      <br>
    </details>
      <br>
    <details>
      <summary>Trunk-Based Development</summary>
      <br>
    </details>
    <br>  
    GitFlow Workflow:<br>
    ![Alt text](images/gitflow_workflow.png)
</details>
<br>

## CLI
<details>
  <summary>more info</summary>
  <br>
  Pending lesson on 03/04/2024
</details>
<br>

## Testing
<details>
  <summary>more info</summary>
  <br>
  Pending lesson on 03/11/2024
</details>
<br>

## CI/CD
<details>
  <summary>more info</summary>
  <br>
  Pending lesson on 03/18/2024
</details>
<br>

## Deploy
<details>
  <summary>more info</summary>
    <br>
    Pending lesson on 03/25/2024
</details>
<br>
