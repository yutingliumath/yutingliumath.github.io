# Yuting Liu — academic homepage

A simple English academic homepage for Yuting Liu, PhD student in the Department of Mathematics at Imperial College London, supervised by Paolo Cascini.

The site consists of `index.html` (home) and `talks.html` (past talks), each including its own styles. It uses no JavaScript, external fonts, tracking, build tools, or paid services. Open `index.html` in a browser to preview it. The layout adapts to desktop and mobile screens.

## Publish with GitHub Pages

1. Create a public repository named `yutingliumath.github.io` under the account `yutingliumath`.
2. Upload `index.html`, `talks.html`, and `.nojekyll` to the root of its `main` branch. Do not upload the enclosing folder or the ZIP archive itself.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/ (root)**, and save.
4. Once GitHub reports a successful deployment, the site will be available at `https://yutingliumath.github.io/`.

If publishing under a different GitHub account, substitute that username in both the repository name and the site address. No changes to `index.html` are necessary.

GitHub's official guide: https://docs.github.com/en/pages/quickstart

## Update the homepage

Edit `index.html` directly on GitHub and commit the change. GitHub Pages republishes after a successful build.

- The personal information is in the `identity` aside and the `about` section.
- Each preprint is one `<li class="paper">` in the `papers` section. Copy an existing entry to add another paper, and update its title, unique IDs, author list, year, status, arXiv link, and PDF link.
- When changing the email, update all occurrences of `yuting.liu24@imperial.ac.uk`, including `mailto:` links.
- Update the date in the footer after substantive changes.
- Edit `talks.html` to update the talks page. Each talk is one `<li class="talk">`; list new talks in reverse chronological order.
- A photo, CV link, or teaching section can be added later.

## Content sources

The name, affiliation, supervisor, research interests, contact email, and submission statuses were supplied by Yuting Liu. The two papers are listed as submitted to a journal; no journal name or acceptance is implied.

Paper titles, authors, and initial arXiv years were checked on 1 November 2026:

- **Holonomy and Integrability of p-Closed Foliations**, arXiv:2608.26813 (2026): https://arxiv.org/abs/2608.26813
- **Positivity of exterior products of tangent bundles and their subsheaves**, arXiv:2310.19315 (2023, revised in 2026): https://arxiv.org/abs/2310.19315

Department: https://www.imperial.ac.uk/mathematics/

Supervisor's institutional profile: https://profiles.imperial.ac.uk/p.cascini

## 中文发布说明

1. 在 GitHub 新建公开仓库，仓库名称填写 `yutingliumath.github.io`。
2. 将 `index.html` 和 `talks.html` 上传到仓库最外层；不要把 ZIP 文件直接上传，也不要再套一层文件夹。`.nojekyll` 是可选的静态站点标记文件，若系统隐藏了它，上传两个 HTML 文件也可按 GitHub Pages 的默认流程发布。
3. 在仓库的 **Settings → Pages** 中，将 Source 设为 **Deploy from a branch**，Branch 设为 **main**，文件夹设为 **/ (root)**，然后保存。
4. 等待 GitHub 显示部署成功，再打开主页地址。

以后添加论文时，只需编辑 `index.html` 中现有的论文条目并保存。论文年份使用首次上传 arXiv 的年份；投稿状态独立标注。

## Talks: sources and date conventions

The user confirmed giving talks at all three events. Event titles and links were checked on 1 November 2026. Their participation in the Westlake conference is supplied by the user; the organizer's archived speaker list is not treated as an exhaustive programme.

- August 2026: **Conference on Foliation, Fibration, and Moduli**, Westlake University, Hangzhou, China. The conference ran 24–29 August, but the individual talk date and title were not supplied. The public page therefore displays the month only. Organizer's page: https://jihaoliu.org/ffm-conference.html
- 12 June 2026: **Junior Geometry Seminar**, Imperial College London. Talk title: **Linear Series on K3 Surfaces**. The date and title are supplied by the university's indexed event announcement: https://www.imperial.ac.uk/events/210540/junior-geometry-seminar-yuting-liu/
- May 2026: **SinG School in Geometry: Birational Geometry of Foliations**, University of Trento, Italy. The school ran 25–29 May and lists Yuting Liu among its lecturers. The individual presentation title and date were not supplied; the public page displays the month only. Official school page: https://sites.google.com/unitn.it/sing-trento/home

Only the Imperial talk has a verified individual talk title. No titles, slides, invitation status, or individual talk dates have been invented for the other two entries.
