# web-todo-app
テックセレクトで簡易的な「やることリスト」を作成。<br>

# ユーザの新規登録・ログイン
未ログイン時には画面右上に「Login」「Register」のリンクを表示させ、「ログイン」「新規登録画面」へ遷移。<br>

# To Do の登録・表示
メイン画面登録フォームから To Do を登録。<br>
ログインしているユーザが登録した To Do のみが表示される。<br>
他のユーザに To Do の内容は表示されない。<br>

# To Do の削除
To Do に表示されている「削除」のリンクをクリックすると To Do を削除<br>

# DB 設計
To Do とユーザを紐づける必要があるため、ユーザを管理する DB と、To Do を管理する DB で構成<br>
