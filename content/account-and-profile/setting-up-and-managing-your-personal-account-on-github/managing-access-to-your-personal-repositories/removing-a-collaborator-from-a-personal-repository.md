---
title: Removing a collaborator from a personal repository
intro: 'When you remove a collaborator from your project, they lose read/write access to your repository. If the repository is private and the person has created a fork, then that fork is also deleted.'
redirect_from:
  - /articles/how-do-i-remove-a-collaborator
  - /articles/what-happens-when-i-remove-a-collaborator-from-my-private-repository
  - /articles/removing-a-collaborator-from-a-private-repository
  - /articles/deleting-a-private-fork-of-a-private-user-repository
  - /articles/how-do-i-delete-a-fork-of-my-private-repository
  - /articles/removing-a-collaborator-from-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/removing-a-collaborator-from-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/removing-a-collaborator-from-a-personal-repository
  - /account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/removing-a-collaborator-from-a-personal-repository
product: '{% data reusables.gated-features.user-repo-collaborators %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
  - Repositories
shortTitle: Remove a collaborator
---
## Deleting forks of private repositories

While forks of private repositories are deleted when a collaborator is removed, the person will still retain any local clones of your repository.

## Removing collaborator permissions from a person contributing to a repository

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
{% ifversion fpt or ghec or ghes > 3.4 or ghae > 3.4 %}
{% data reusables.repositories.click-collaborators-teams %}
4. To the right of the collaborator you want to remove, click {% octicon "trash" aria-label="The trash icon" %}.
  ![Button to remove collaborator](/assets/images/help/repository/collaborator-remove.png)
{% else %}
3. In the left sidebar, click **Collaborators & teams**.
4. Next to the collaborator you want to remove, click the **X** icon.
  ![Remove link](/assets/images/help/organizations/Collaborator-Remove.png)
{% endif %}

## Further reading

- "[AUTOTITLE](/organizations/organizing-members-into-teams/removing-organization-members-from-a-team)"
- "[AUTOTITLE](/organizations/managing-user-access-to-your-organizations-repositories/removing-an-outside-collaborator-from-an-organization-repository)"
