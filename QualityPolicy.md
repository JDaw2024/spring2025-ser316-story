### Quality Policy
Our team’s **Quality Policy** ensures we deliver high-quality, reliable, and consistent work. We focus on:  
- Following coding standards and best practices.  
- Testing early and often to catch and fix issues.  
- Sharing responsibility for quality as a team.  
- Incorporating feedback to improve continuously.

---

### GitHub Workflow (Sprint 1) 

#### Branching Standards  
- **`main`**: Stable and production-ready at all times.  
- **`dev`**: Active development branch; merge only after thorough testing and review.  
- **Feature Branches (`US#-<short description>`)**: Directly tied to Taiga User Stories, branched from `dev`.  
- **Sub-task Branches (Optional)**: For specific tasks, branch from related User Story branches.  

#### Commit Standards  
- Include `US#` and `Task#` references in commit messages (e.g., `feat: US#12 Add login feature`).  
- Write clear, descriptive commit messages and commit often, even for work in progress (use `WIP` if incomplete).  

#### Pull Requests and Reviews  
- All merges to `dev` and `main` require Pull Requests (PRs).  
- PRs must be reviewed and approved by at least one team member.  
- The Git Master oversees the process but is not responsible for resolving conflicts (handled by the PR creator).  

#### Testing  
- Test thoroughly before merging changes.  
- Merge updates from `dev` into feature branches regularly to avoid large conflicts.  

#### Code Review  
- Reviews are a shared responsibility to ensure quality and adherence to standards.  
- Early sprints: Informal reviews; later sprints: More structured reviews.  


#### Clean History  
- Use squash merges for feature branches into `dev` to maintain a clean commit history.  
- Avoid squash merging from `dev` to `main` to preserve alignment between histories.  

#### Continuous Improvement  
- Regularly review and improve workflows and processes as the project progresses.  

This policy is designed to ensure the stability, quality, and collaboration required for project success.

---

**Unit Tests Blackbox** (start Sprint 2)
  > Describe your Blackbox testing policy 

 **Unit Tests Whitebox** (online: start Sprint 2, campus: start Sprint 3)
  > Describe your Whitebox testing policy 

**Code Review** (online: start Sprint 2, campus: start Sprint 2)
  > Describe your Code Review policy for on campus it is ok to have a less formal process in Sprint 2, should be updated in Sprint 3 though

  > Include a checklist/questions list which every developer will need to fill out/answer when creating a Pull Request to the Dev branch. 

  > Include a checklist/question list which every reviewer will need to fill out/answer when conducting a review, this checklist (and the answers of course) need to be put into the Pull Request review.

**Static Analysis**  (online: start Sprint 3, campus: start Sprint 3)
  > Your Static Analysis policy   

**Continuous Integration**  (start Sprint 3, campus: start Sprint 3)
  > Your Continuous Integration policy
