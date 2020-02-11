# 不具合内容

”rake import_csv:users”を実施後
インポート処理を開始
rake aborted!
ActiveRecord::StatementInvalid: Could not find table 'users'
/Users/taniguchitakayasu/Desktop/projects/rake_task_sample/lib/tasks/import_csv.rake:26:in `block (2 levels) in <main>'
Tasks: TOP => import_csv:users
(See full trace by running task with --trace)
