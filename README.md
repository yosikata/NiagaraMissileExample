# NiagaraMissileExample

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

### プロジェクト構成
├─Config  
└─Content  
    ├─Characters  
    │  ├─Mannequins  
    │  │  ├─Animations  
    │  │  │  ├─Manny  
    │  │  │  └─Quinn  
    │  │  ├─Materials  
    │  │  │  ├─Functions  
    │  │  │  └─Instances  
    │  │  │      ├─Manny  
    │  │  │      └─Quinn  
    │  │  ├─Meshes  
    │  │  ├─Rigs  
    │  │  │  └─Poses  
    │  │  └─Textures  
    │  └─Mannequin_UE4  
    │      ├─Animations  
    │      ├─Materials  
    │      │  └─Layers  
    │      ├─Meshes  
    │      ├─Rigs  
    │      └─Textures  
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
