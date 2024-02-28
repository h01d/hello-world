# hello-world of development
Here I will document the lessons I learn regarding many major aspects of development which includes the following:

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
      
1. Main: Stable, direct to production.<br>
2. Develop: Unstable, all feature changes will be pushed here.<br>
3. Feature: Check out from Develop branch, and push changes to it.<br>
4. Hotfix: Check out from Main, push changes to main and develop.<br>
5. Release: Semi-stable, ready to release, following with a few bugfixes. Checkout from Develop and push to both Main and Develop.<br><br>
      Drawbacks are maintaining a Develop branch long-term. Also changes in Hotfix and Release need to push to both Main and Develop for sync. The git history would look very messy and hard to follow.<br><br>
      GitFlow Workflow:<br>
    
    ![Alt text](images/gitflow_workflow.png)
    </details>

      <br>
      <details>
      <summary>GitHub Flow</summary>
      <br>
      GitHub Flow is a simple, lightweight strategy for small teams and quick relases. It emphasizes small teams and quick releases. It also emphasizes small, frequent commits to the main branch, ensuring it's always deployable. This stategy is flexible and promotes fast feedback loops.
      <br>
      <br>
      With this flow we maintain main and usually other branches accompanying it like bug fixes and features branches.<br><br>
      GitHub Workflow:<br>
    
    ![Alt text](images/github_workflow.png)
    </details>

      <br>
    <details>
      <summary>GitLab Flow</summary>
      <br>
      GitLab Flow is robust and scalable, suitable for large projects. It focuses on a single, protected main branch, integrating continious integration and automated testing to ensure stability. While this is like GitHub flow, having environment branches is a big difference.
      <br>
      <br>
      With this flow there are two different types of release cycles:<br>

    1. Versioned Release: each release has an associated release branch that is based off the main branch. Bug fixes should be merged into the main branch first, before cherry-picked into the release branch.<br>
    2. Continuous Release: production branches are utlilized to contain deployment-ready code, so code is merged into production branch when it's ready to be released.<br><br>
        GitLab Workflow:<br>

    ![Alt text](images/gitlab_workflow.png)
    </details>

      <br>
    <details>
      <summary>Trunk-Based Development</summary>
      <br>
      TBD involves direct merges to a shared trunk branch, aiming for frequent, small changes to maintain a releasable state. It reduced merge conflicts and encourages collaboration but can be complex for large teams.
      <br>
      <br>
      With this flow there a many different styles or methods suited to specific circumstances:<br>
## The first being what not to do
### Shared branches off mainline/main/trunk are bad at any release cadence:<br>
![Alt text](images/TBD_bad.png) <br>
## The second and third being applicable to specific use cases
### Trunk-Based Development For Smaller-Teams:<br>
![Alt text](images/TBD_good_1.png) <br>
### Scaled Trunk-Based Development:<br>
![Alt text](images/TBD_good_2.png) <br>
    </details>
    <br>  
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
