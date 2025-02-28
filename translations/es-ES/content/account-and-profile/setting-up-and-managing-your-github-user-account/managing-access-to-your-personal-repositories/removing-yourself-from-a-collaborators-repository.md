---
title: Eliminarte del repositorio de un colaborador
intro: 'Si no quieres seguir siendo colaborador del repositorio de otra persona, te puedes eliminar.'
redirect_from:
  - /leave-a-collaborative-repo
  - /leave-a-repo
  - /articles/removing-yourself-from-a-collaborator-s-repo
  - /articles/removing-yourself-from-a-collaborator-s-repository
  - /articles/removing-yourself-from-a-collaborators-repository
  - /github/setting-up-and-managing-your-github-user-account/removing-yourself-from-a-collaborators-repository
  - /github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/removing-yourself-from-a-collaborators-repository
product: '{% data reusables.gated-features.user-repo-collaborators %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
  - Repositories
shortTitle: Eliminarte a ti mismo
---

{% data reusables.user_settings.access_settings %}
{% ifversion fpt or ghec or ghes > 3.3 or ghae-issue-5658 %}
2. In the "Code, planning, and automation" section of the sidebar, click **{% octicon "repo" aria-label="The repo icon" %} Repositories**.
{% else %}
2. En la barra lateral izquierda, haz clic en **Repositories** (Repositorios). ![Pestaña Repositories (Repositorios)](/assets/images/help/settings/settings-sidebar-repositories.png)
{% endif %}
3. Junto al repositorio que quieres abandonar, haz clic en **Leave** (Abandonar). ![Botón Leave (Abandonar)](/assets/images/help/repository/repo-leave.png)
4. Lee la advertencia con atención, luego haz clic en "I understand, leave this repository" (Comprendo, abandonar este repositorio). ![Cuadro de diálogo con advertencia sobre el abandono](/assets/images/help/repository/repo-leave-confirmation.png)
