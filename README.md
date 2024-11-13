# RemoteLibrary_NguyentienVinh
Microsoft Windows [Version 10.0.26120.2222]
(c) Microsoft Corporation. All rights reserved.

C:\Users\vinh2>git clone https://github.com/Vinh262096/RemoteLibrary_NguyentienVinh.git
Cloning into 'RemoteLibrary_NguyentienVinh'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

C:\Users\vinh2>cd RemoteLibrary_NguyentienVinh

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>dỉ
'dỉ' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>dir
 Volume in drive C has no label.
 Volume Serial Number is A251-E0EC

 Directory of C:\Users\vinh2\RemoteLibrary_NguyentienVinh

13/11/2024  11:07 CH    <DIR>          .
13/11/2024  11:07 CH    <DIR>          ..
13/11/2024  11:07 CH                30 README.md
               1 File(s)             30 bytes
               2 Dir(s)  65.616.560.128 bytes free

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>echo "# Remote Library" > README.md

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>dir
 Volume in drive C has no label.
 Volume Serial Number is A251-E0EC

 Directory of C:\Users\vinh2\RemoteLibrary_NguyentienVinh

13/11/2024  11:07 CH    <DIR>          .
13/11/2024  11:07 CH    <DIR>          ..
13/11/2024  11:08 CH                21 README.md
               1 File(s)             21 bytes
               2 Dir(s)  65.617.063.936 bytes free

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git add README.md

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git commit -m "Thêm tệp README.md"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'vinh2@NGUYENVINH.(none)')

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git log
commit 48e2f70c1c3c8789b8df5676ef4847d726a81166 (HEAD -> main, origin/main, origin/HEAD)
Author: Vinh262096 <vinh262006@gmail.com>
Date:   Wed Nov 13 22:36:46 2024 +0700

    Initial commit

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git push origin main
info: please complete authentication in your browser...
Everything up-to-date

C:\Users\vinh2\RemoteLibrary_NguyentienVinh>git pull
Already up to date.
