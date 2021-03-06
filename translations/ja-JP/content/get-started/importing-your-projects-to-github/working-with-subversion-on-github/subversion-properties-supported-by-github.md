---
title: GitHub がサポートする Subversion プロパティ
intro: '{% data variables.product.product_name %} 上の既存の機能に類似したいくつかの Subversion ワークフローやプロパティがあります。'
redirect_from:
  - /articles/subversion-properties-supported-by-github
  - /github/importing-your-projects-to-github/subversion-properties-supported-by-github
  - /github/importing-your-projects-to-github/working-with-subversion-on-github/subversion-properties-supported-by-github
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
shortTitle: Properties supported by GitHub
---

## Executable files (`svn:executable`)

Git リポジトリに追加する前に、ファイルモードを直接更新することで、`svn:executable` プロパティを変換します。

## MIME types (`svn:mime-type`)

{% data variables.product.product_name %}は、ファイルの MIME タイププロパティ、およびそれを追加したコミットを追跡します。

## Ignoring unversioned items (`svn:ignore`)

Subversion で無視されるようにファイルとディレクトリを設定している場合、{% data variables.product.product_name %} はそれらを内部的に追跡します。 Subversion のクライアントで無視されたファイルは、*.gitignore* ファイルのエントリとは全く別のものです。

## 現在サポートされていないプロパティ

現在は、{% data variables.product.product_name %} は、`svn:externals`、`svn:global-ignores`、カスタムプロパティ、その他上記にないプロパティをサポートしていません。
