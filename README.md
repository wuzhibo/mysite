# mysite
python of web
git rm 和 git rm --cached 区别：
		当我们需要删除暂存区或分支上的文件，同时工作区 '不需要' 这个文件，可以使用 'git rm'
			git rm file
			git commit -m 'delete file'
			git push

		当我们需要删除暂存区或分支上的文件，但是本地 '需要' 这个文件，只是 '不希望加入版本控制'，可以使用 'git rm --cached'
			git rm --cached file
			git commit -m 'delete remote file'
			git push