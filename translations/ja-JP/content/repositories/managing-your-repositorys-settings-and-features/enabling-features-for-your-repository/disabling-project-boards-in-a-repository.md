---
title: リポジトリ内のプロジェクトボードを無効化する
intro: 自分や自分のチームが異なる方法で作業管理をしている場合、リポジトリの管理者はリポジトリのプロジェクトボードをオフにできます。
redirect_from:
  - /github/managing-your-work-on-github/managing-project-boards/disabling-project-boards-in-a-repository
  - /articles/disabling-project-boards-in-a-repository
  - /github/managing-your-work-on-github/disabling-project-boards-in-a-repository
  - /github/administering-a-repository/managing-repository-settings/disabling-project-boards-in-a-repository
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
shortTitle: プロジェクトボードの無効化
---

プロジェクトボードを無効化すると、タイムラインや[監査ログ](/articles/reviewing-your-security-log/)でプロジェクトボード情報を見ることができなくなります。

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
3. [Features] の下で、[**Projects**] チェックボックスの選択を解除します。 ![[Projects] チェックボックスの選択を解除する](/assets/images/help/projects/disable-projects-checkbox.png)

プロジェクトボードが無効化されると、既存のプロジェクトボードはそれまでの URL でアクセスできなくなります。 {% data reusables.organizations.disable_project_board_results %}
