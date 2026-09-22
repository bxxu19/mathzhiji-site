# 推送到 GitHub Pages

本目录仅含静态站点（无源码），已本地 commit，remote：
`https://github.com/bxxu19/mathzhiji-site.git`

## 一次性步骤

1. 浏览器打开 https://github.com/new  
   - Repository name: `mathzhiji-site`  
   - Public  
   - **不要**勾选 README / .gitignore / license（空仓库）  
   - Create repository

2. 在本机终端登录 GitHub（任选其一）  
   - 安装 GitHub CLI：`brew install gh`，然后 `gh auth login`  
   - 或配置 SSH key：https://docs.github.com/en/authentication/connecting-to-github-with-ssh  
   - 或使用 Personal Access Token（HTTPS push 时作密码）

3. 推送：

```bash
cd /Users/boxixu/Desktop/mathzhiji-site-publish
git push -u origin main
```

4. 打开仓库 Settings → Pages → Branch: `main` / folder: `/ (root)` → Save  

5. 约 1～2 分钟后访问：  
   https://bxxu19.github.io/mathzhiji-site/

