# 39プロジェクト規格(39-Project-Standard)

## 適用
有効期限 [シーズン3](./Season3.0.md)による。  
発行番号 S301 20230503
***
## 目的
この規格を制定するにあたって求められる使命は、[プロジェクト(project)](./words/project.md)の沿革な進行と、プロジェクト同士の関係をより具体的に示すことによる。  
それすなわち、プロジェクトの関係を構造体と改めることによつて、関連事項を結びやすくし、見やすさ・扱いやすさを向上させることである。
***
## プロジェクト構造体
この規格により制定される[プロジェクト(project)](./words/project.md)の構造体は次の構造による。
- [名称/name](#名称)
- [種類/type](#種類)
    - 種別/class
- 管理者/admin
    - 代表管理者/superadmin
    - 会員/member
- 所属/belongs
- 内容/contents
    - 情報/data
    - 規則/rule
- 付随情報/tags

## [名称](#プロジェクト構造体)
[名称(name)](./words/name.md)は、プロジェクトを特定でき、唯一であること。

## [種類・種別](#プロジェクト構造体)
[種類(type)](./words/type.md)は次による。
- 役務/service
    - 上級/super
    - 普通/general
- 部活/circle
- 物品/object
    - 動的/dynamic
    - 静的/static
    - 雛形/template

### 役務  

**役務**(**service**)とは、[役務(service)](./words/service.md)や[部活(circle)](./words/circle.md)によって形成される、実質的に活動を行うプロジェクトであり、何かしらの[物品(object)](./words/object.md)を持つ一般的なプロジェクトのことである。  
人間社会でいう会社に値し、[物品(object)](./words/object.md)を生成したり、[役務(service)](service.md)を行うところである。  
#### 役務の種別
**上級型**は、複数の[役務(service)](./words/service.md)を総括する代表であり、総括される普通役務(general service)は、いずれかの上級型役務(super service)に所属(belongs)する。
