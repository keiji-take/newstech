#テーブル設計


##articlesテーブル
|   column   |   type     | options        |
|------------------------------------------|
| title      |  string    | null: false    |
| content    |  text      | null: false    |
| genre      |  integer   | null: false    |
| location   |  string    | null: false    |

###Association
- has_many: likes


