### 找出大小大於100MB的檔案
`find / -type f -size +100M  -print0 | xargs -0 ls -lh`
