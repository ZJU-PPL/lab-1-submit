# PPL Course Lab 1 Submission Instruction

You are required to use GitHub issues to upload your code. There are two steps.

1. Compress your code into a single .tar.gz file (in which the `dune-project` file should be at the root of the package, rather than in an inner directory). Then, encrypt it with the PGP public key attached at the end of this document, getting a ascii text file like the following. You'd better save it as a '.txt' file.

   ```pgp
   -----BEGIN PGP MESSAGE-----
   
   wcDMAzeDU5KNWkDZAQv/TbtirFruvoSG+EUF3s4Fnh7OisgrEnW8481K37mOqnDF
   qcam+xpH8SqY4NMIa5q6z9kas9ji7MOzMLljU4THwLXFSePEV6m45p1UHdmKbKkr
   ...
   M9W3Q5eOYcpKNE/iMUqaKeq3nZMEq6LxAiYxP1R1ywnWPpcQY9ghI1JRpuuBuqPt
   qP4neCvA77yv79PDkLyX8ZFpZanKwtaz54N+OsCf5YlEKGwLKw==
   =Ve7J
   -----END PGP MESSAGE-----
   ```

2. Create a issue [here](https://github.com/ZJU-PPL/lab-1-submit/issues) (click "New issue"), upload your encrypted file, and submit. About 2 minutes later, your issue will get a reply, reporting your scores. Submission Done.

Your warm-hearted teaching assistants have written a packing tool, which can be downloaded [here](https://github.com/ZJU-PPL/pack/releases). Put the binary in your project root directory (the same directory where `dune-project` resides), and execute it. It will generate a `stu-code.pgp.txt` (step 1 completed). Just submit it.

Warnings:

- DO NOT post any image link or other link before your code package link, or they may not be judged.

- DO NOT upload code without encryption. We will consider a penalty if you don't notice us to delete it in time.

- DO NOT try to hack the grader or do other cheating behaviors. There's going to be serious results.

# 编程语言原理课程实验一提交说明

你需要使用 GitHub Issues 来上传你的代码。

提交代码的步骤如下。

1. 把你的代码打包成一个 .tar.gz 格式的文件，**其中项目文件 dune-project 应该位于压缩包的根目录下，而不是在内部的某个目录中**。然后，把这个压缩包用本页末尾的 PGP 公钥加密，得到一个文本形式的加密后的文件，例如 `stu-code.pgp.txt`，形如

   ```pgp
   -----BEGIN PGP MESSAGE-----
   
   wcDMAzeDU5KNWkDZAQv/TbtirFruvoSG+EUF3s4Fnh7OisgrEnW8481K37mOqnDF
   qcam+xpH8SqY4NMIa5q6z9kas9ji7MOzMLljU4THwLXFSePEV6m45p1UHdmKbKkr
   ...
   M9W3Q5eOYcpKNE/iMUqaKeq3nZMEq6LxAiYxP1R1ywnWPpcQY9ghI1JRpuuBuqPt
   qP4neCvA77yv79PDkLyX8ZFpZanKwtaz54N+OsCf5YlEKGwLKw==
   =Ve7J
   -----END PGP MESSAGE-----
   ```

2. 在本仓库的 Issue 中[新建一个 issue](https://github.com/ZJU-PPL/lab-1-submit/issues/new)（自己起一个能辨识的名字），将上面得到的文本文件拖进去上传。上传成功后你就会看到一段形如 `[一些文本](一个链接)` 的东西出现在内容框里，这时直接提交就行了。两分钟后，你的 issue 下面就会收到评测结果。这样就完成了提交。

贴心的助教为大家写了打包程序，可以在[这里](https://github.com/ZJU-PPL/pack/releases)下载。把拿到的打包程序放在项目根目录下（跟 `dune-project` 文件在同一个目录下），执行它，就能得到 `stu-code.pgp.txt`（一键完成第一步）。提交它就行了。

注意：

- 不要在代码压缩包链接前放置任何链接。否则可能无法评测你的代码。
- 不要上传没有加密的代码。如果你上传了还不及时通知我们删除，有你好果子吃。
- 不要试图破解评分器或者进行其他作弊行为。否则有你好果子吃。



## Public Key

```pgp
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
=CGda
-----END PGP PUBLIC KEY BLOCK-----
```

