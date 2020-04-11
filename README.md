#Gitコマンドまとめ

HTML-CSSのアップデート方法

	まずGitBashを開く
	$ cd Desktop/HTML-CSS
	$ git add [file] or git add *  : * はその階層のファイル全部を表す。
	$ git commit -m "コメント" : コメントは "Initial" とか "Modefied_20200407"　とかがおすすめ
	$ git push origin master


git push origin masterが上手くいかないとき

	git pull --rebase origin master

ローカルのgitの状態を知りたいとき

	git status

接続先のGit gubが正しいか確認したいとき

	git remote -v
