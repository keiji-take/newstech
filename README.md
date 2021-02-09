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


##usersテーブル
|   column   |   type     | options        |
|------------------------------------------|
| username   |  string    | null: false    |
| email      |  string    | null: false    |
| encrypted_password |  string    | null: false    |
| tel_number | integer    |  null: false   |

###Association
- has_many: likes, dependent: :destroy


