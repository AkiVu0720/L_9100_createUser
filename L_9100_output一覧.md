
>baseResponse一覧

|No|英語で名称|日本語で名称|タイプ|備考|
|-|-|-|-|-|
|1|status|ステータス| int||
|1|messenger|メッセンジ|text||
|1|[user_response](#user_response一覧)|エンティティ|object |

>user_response一覧

|No|英語で名称|日本語で名称|タイプ|備考|
|-|-|-|-|-|
|1|token|トークン|varchar(100)|not null|
|1|type|タイプ|varchar(6)|type＝"Bearer"|
|1|user_name|ユーザ名|varchar(100)|not null|
|2|email|メール|varchar(255)|not null|
|3|password|パスワード|varchar(100)|not null|
|3|role_name|ロール|enum|user, admin|