# Week 01 打卡记录

## 本周目标

掌握 Git 基础概念、常用命令、分支操作和基础提交习惯。

## Day 1

### 今日学习内容### 今日学习内容

### 

### | 学习内容                | 对应命令演示                                                                   |

### | ------------------- | ------------------------------------------------------------------------ |

### | 如何进入项目文件夹           | `cd "C:\\Users\\李潇然\\Documents\\Codex\\2026-06-16\\ai-agent-1-readme-md-2"`    |

### | 如何查看当前目录内容          | `dir`                                                                    |

### | 如何初始化 Git 仓库        | `git init`                                                               |

### | 如何查看 Git 状态         | `git status`                                                             |

### | 如何把文件加入暂存区          | `git add .`                                                              |

### | 如何提交第一个版本           | `git commit -m "Day 1: 初始化学习仓库*"`*                                         |

### | 如何查看提交历史            | `git log --oneline`                                                      |

### | 如何设置 Git 用户名        | `git config --global user.name "李潇然"`                                    |

### | 如何设置 Git 邮箱         | `git config --global user.email "lxr103060@gmail.com"`                   |

### | 如何查看 Git 配置         | `git config --global --list`                                             |

### | 如何连接 GitHub 远程仓库    | `git remote add origin https://github.com/kxr1214qef/agent-learning.git` |

### | 如何查看远程仓库地址          | `git remote -v`                                                          |

### | 如何将分支改名为 main       | `git branch -M main`                                                     |

### | 如何查看当前分支            | `git branch`                                                             |

### | 如何尝试把本地项目上传到 GitHub | `git push -u origin main`                                                |



### 今日实操 初步在终端使用git对学习仓库进行使用

### 遇到的问题 没有将git本地仓库的文件上传到github上面

### 今日总结

### 是否完成 本地 Git 学习目标：已完成。

### &#x20;              GitHub 上传目标：暂未完成，原因是终端网络无法连接 GitHub。

### commit 链接 本地 commit 记录：

### 

### 5078eb1 Day 1: 初始化学习仓库

### 

### GitHub commit 链接暂时没有，因为今天还没有成功 push 到 GitHub。

### 

### 等成功上传后，commit 链接会出现在 GitHub 仓库的 Commits 页面中。

## Day 2

### 今日学习内容
学习内容	对应命令 / 操作演示
如何进入新的项目文件夹	cd D:\project\agent-learning
如何确认移动后的项目仍然是 Git 仓库	git status
如何确认远程 GitHub 仓库地址还在	git remote -v
如何检查 GitHub CLI 是否登录成功	gh auth status
如何重新设置 Git 用户名	git config --global user.name "lxr"
如何重新设置 Git 邮箱	git config --global user.email "lxr103060@gmail.com"
如何查看 Git 全局配置	git config --global --list
如何拉取 GitHub 远程仓库内容	git pull origin main --allow-unrelated-histories
如何查看合并冲突状态	git status
如何标记冲突文件已解决	git add README.md
如何完成合并提交	git commit -m "合并 GitHub 远程 README"
如何上传本地仓库到 GitHub	git push -u origin main
以后如何日常上传	git push
如何查看 GitHub 仓库提交记录	GitHub 页面点击 Commits
如何理解 GitHub Insights	Dependency graph、Traffic、Actions metrics 等是仓库统计功能
如何修改仓库公开 / 私有	GitHub 仓库 Settings → Danger Zone → Change repository visibility
### 今日实操
今天把项目移动到了新的英文路径：

D:\project\agent-learning

进入项目后，确认 Git 仓库正常：

git status

确认远程 GitHub 地址正常：

git remote -v

然后拉取 GitHub 远程内容：

git pull origin main --allow-unrelated-histories

过程中遇到 README.md 冲突，在 VS Code 中解决冲突后执行：

git add README.md
git commit -m "合并 GitHub 远程 README"

最后成功上传到 GitHub：

git push -u origin main
### 遇到的问题
今天主要遇到三个问题：

移动项目路径后，担心 Git 仓库会丢失。
最后通过 git status 确认 .git 仍然存在，仓库正常。
执行 pull 时提示 Git 用户名和邮箱缺失。
通过重新设置 user.name 和 user.email 解决。
本地和 GitHub 远程都有 README.md，导致合并冲突。
在 VS Code 中解决冲突后，用 git add README.md 标记为已解决，再用 git commit 完成合并。
### 今日总结
今天成功完成了：

本地 Git 仓库 → 拉取 GitHub 内容 → 解决冲突 → 合并提交 → 上传到 GitHub

我理解了：

git pull = 从 GitHub 拉取并合并
git add = 把修改或冲突解决结果放进暂存区
git commit = 保存成一个 Git 版本
git push = 上传到 GitHub
-u = 建立本地分支和远程分支的默认关联

以后日常上传 GitHub，只需要在 commit 后执行：

git push
### 是否完成
已完成。

今天已经成功把本地 Git 仓库上传到了 GitHub。
### commit 链接
commit 链接

今日关键 commit：

77b12c0 合并 GitHub 远程 README

GitHub 仓库已经显示本地提交记录，说明同步成功。
## Day 3

### 今日学习内容

### 今日实操

### 遇到的问题

### 今日总结

### 是否完成

### commit 链接

## Day 4

### 今日学习内容

### 今日实操

### 遇到的问题

### 今日总结

### 是否完成

### commit 链接

## Day 5

### 今日学习内容

### 今日实操

### 遇到的问题

### 今日总结

### 是否完成

### commit 链接

## Day 6

### 今日学习内容

### 今日实操

### 遇到的问题

### 今日总结

### 是否完成

### commit 链接

## Day 7

### 今日学习内容

### 今日实操

### 遇到的问题

### 今日总结

### 是否完成

### commit 链接

