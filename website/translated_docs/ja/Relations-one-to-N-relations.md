---
id: one-to-many-relations
title: １対Ｎリレーション
---

このレッスンでは，4D for iOSアプリで１対Ｎリレーションを使用する方法を学びます。<div class = "tips"> 

**注記**

In this tutorial, we will use the relation names between your tables. ストラクチャの設定を容易にするため，リレーションには意味のある名前を設定することが勧められています。</div> 

素材プロジェクトをダウンロードしてください。

<div style="text-align: center; margin-top: 20px; margin-bottom: 20px">
  <p>
    

<a class="button"
href="https://github.com/4d-for-ios/tutorial-OneToManyRelations/archive/c006015afeb0e134d872152f53b8cd5e4dcb59bb.zip">ONE TO MANY STARTER PROJECT</a>

  </p>
</div>

In this tutorial, we are going to build a colorful **Task app** using 4D for iOS.

![Task App Final result](assets/en/relations/4D-for-iOS-dark-mode-card-relation-ios-13.gif)

But first, let's have a look at the structure of our database:

![「ストラクチャ」セクションで１フィールドを選択する](assets/en/relations/Database-1-to-N-relations-4D-for-iOS.png)

As you can see, there is a One to Many link named **tasks** that we will use in our iOS app to display the employees'(**One**) tasks(**to Many**).

Now, go straight to Open menu > Mobile project... to select *Time Keeper* and go to the **Structure section**.

## Structure section

You can see the **tasks relation** we have seen earlier... Publish it !

This will now operate as any other field for the rest of the app creation process.

![Structure section Relations properties](assets/en/relations/Structure-section-relations-4D-for-iOS.png)<div class = "tips"> 

**ヒント**

* On mouse over, a tip displays the table name originating the relation.</div> 

## Labels & Icons section

The One to Many relation is now available in the [Labels and Icons](labels-and-icons.html) section.

It is important to know that including a One to Many relation will create a button into the genrated iOS app.

So, in the Labels & Icons section you will define:

* ボタンタイトル
* ボタンアイコン
* 遷移した先の画面に表示される[タイトル](one-to-n-relations-title-definition.html)（たとえば，どの画面から移動してきたのかを示すために使用します）。

![Labels & Icons section Relations properties](assets/en/project-editor/Relations-properties-Labels-icons-section-4D-for-iOS.png)

## フォームセクション

* 「フォーム」セクションにページを切り替えて，Employee TableのTask Detail画面に*tasks*リレーションをドラッグ＆ドロップします。

![「フォーム」セクションに表示された１フィールド](assets/en/relations/1-to-n-relations-forms-section.png)

## ビルドして実行

1. Employeeのリスト画面で適当な従業員をクリックします。 
2. 従業員の情報が詳細画面に**Relation**ボタンが表示されているはずです。
3. Relationボタンをクリックすると，選択されている従業員のタスクが表示されます。 

![「フォーム」セクションに表示された１フィールド](assets/en/relations/One-to-n-relations-task-ios-app.png)

And voila, this is how One to Many relations work in 4D for iOS !

<div style="text-align: center; margin-top: 20px; margin-bottom: 20px">
  <p>
    

<a class="button"
href="https://github.com/4d-for-ios/tutorial-OneToManyRelations/releases/latest/download/tutorial-OneToManyRelations.zip">ONE TO MANY FINAL PROJECT</a>

  </p>
</div>