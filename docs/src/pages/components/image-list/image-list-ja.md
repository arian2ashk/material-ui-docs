---
title: Grid List React component
components: ImageList, ImageListItem, ImageListItemBar, ListSubheader, IconButton
materialDesign: https://material.io/components/image-lists
githubLabel:
  component: ImageList
---

# Grid List

<p class="description">グリッドリストは、整理されたグリッドで画像のコレクションを表示します。</p>

[グリッドリスト](https://material.io/design/components/image-lists.html) は、繰り返しパターンの項目の集まりを表します。 それらは、保持するコンテンツの視覚的理解を改善するのに役立ちます。

{{"component": "modules/components/ComponentLinkHeader.js"}}

## 画像のみのGrid list

{{"demo": "pages/components/image-list/ImageImageList.js", "hideEditButton": true}}

{{"demo": "pages/components/image-list/BasicImageList.js", "hideEditButton": true}}

## タイトルバー付きのGrid list

この例は、 `ImageListItemBar` を使用して、各 `ImageListItem`オーバーレイを追加する方法を示しています。 オーバーレイには、 `title`, `subtitle` および副次的アクション例えば`IconButton`を含めることができます。

{{"demo": "pages/components/image-list/TitlebarImageList.js", "hideEditButton": true}}

## Single line Grid list 単一行グリッドリスト

この例では、水平スクロール可能な単一行グリッドの画像リストを示します。 水平方向のスクロールグリッドリストは、スクロールが一般的な読み方の邪魔になり理解に影響を与えるため、推奨されません。 注目すべき例外の1つは、水平にスクロールする、ギャラリーなどの画像の1行グリッドリストです。

{{"demo": "pages/components/image-list/SingleLineImageList.js", "hideEditButton": true}}

## 高度なグリッドリスト

この例では、`rows` and `cols` プロップを使用してタイルのサイズを調整し、 `padding`プロップを使用して間隔を調整する方法を示します。 タイルには、上部にカスタムのタイトルバーがあり、カスタムのグラデーション`titleBackground`があります。 セカンダリアクション `IconButton` は左側に配置されます。

{{"demo": "pages/components/image-list/AdvancedImageList.js", "hideEditButton": true, "defaultCodeOpen": false}}