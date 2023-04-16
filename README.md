# NiagaraMissileExample
Niagaraでホーミングミサイルの処理を作成した際のサンプルプロジェクト　　

## 概要：OverView
Niagaraを使用したホーミングミサイルのサンプルプロジェクトになります。
![GamePlay](https://user-images.githubusercontent.com/5137050/232280463-b8f21ed6-adcd-409b-83e2-1040cf1dae92.gif)

## 各種操作：Method of operation  　
W・A・S・D Key  
キャラクターの移動:CharacterMove  
R Key  
敵のロック:LockTarget  

## 各種説明:Various explanations
### プロジェクト内の処理の説明　
ブログ内の紹介記事  
https://argonauts.hatenablog.jp/entry/2023/04/16/164958  

### 改良できそうな所
・敵キャラへのロック持続  
・エフェクトの強化などなど  

### プロジェクト構成
├─Config  
└─Content  
    ├─Characters  
    ├─Collections  
    ├─LevelPrototyping  
    │  ├─Materials  
    │  ├─Meshes  
    │  └─Textures  
    ├─Map  
    ├─Missile  
        ├─Blueprint  
        ├─Image  
        ├─Input  
        │  └─Actions  
        └─Niagara  
