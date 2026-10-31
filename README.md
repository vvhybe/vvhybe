<div align="center">

```txt
██╗   ██╗██╗   ██╗██╗  ██╗██╗   ██╗██████╗ ███████╗
██║   ██║██║   ██║██║  ██║╚██╗ ██╔╝██╔══██╗██╔════╝
██║   ██║██║   ██║███████║ ╚████╔╝ ██████╔╝█████╗  
╚██╗ ██╔╝╚██╗ ██╔╝██╔══██║  ╚██╔╝  ██╔══██╗██╔══╝  
 ╚████╔╝  ╚████╔╝ ██║  ██║   ██║   ██████╔╝███████╗
  ╚═══╝    ╚═══╝  ╚═╝  ╚═╝   ╚═╝   ╚═════╝ ╚══════╝
```

[![typing](https://readme-typing-svg.demolab.com?font=Victor+Mono&weight=500&size=18&duration=2600&pause=900&color=808080&center=true&vCenter=true&width=640&lines=ERP+and+Odoo+for+the+bills.;TypeScript+and+Next.js+for+the+thrills.;Learning+Rust.+Losing+arguments+to+the+borrow+checker.;Drawing+manga+I+will+finish+someday.)](https://vvhybe.com)

![visit](https://img.shields.io/badge/vvhybe.com-000?style=for-the-badge&labelColor=fff&color=000&label=visit)
![based](https://img.shields.io/badge/Marrakech-MA-000?style=for-the-badge&labelColor=fff&color=000&label=based)
![palette](https://img.shields.io/badge/two_colours_only-000?style=for-the-badge&labelColor=fff&color=000&label=palette)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/boot-dark.svg">
  <img alt="vvhybe boot log: /day is erp, odoo, backend. /night is typescript, next.js, open source. /atelier is manga, photography and a book in arabic. Rust is still fighting the borrow checker." src="assets/boot-light.svg" width="820">
</picture>

</div>

```txt
vvhybe@marrakech:~$ whoami
yassine bouba. erp developer by day, web builder by night.
computer science and fine arts. based in marrakech.
```

```txt
vvhybe@marrakech:~$ neofetch
      ████████▄▄        yassine@vvhybe
      ██      ▀██       --------------
  ▄▄  ██       ▀▀ ▄▄    role     erp developer @ BigBang Cloud
  ▀▀██▄        ▄██▀▀    base     marrakech, morocco
     ▀▀█▄▄  ▄▄█▀▀▄▄     day      odoo, erp, backend
        ▀████▀▄██▀      night    typescript, react, next.js
           ▄██▀▀        shell    bash, vim keys everywhere
        ▄▄██▀           atelier  manga, photography, a book
      ▄██▀██            os       vvhybe_os, 1-bit
     ███  ██   ██       learning rust
     ██   ██ ▄▄█▀       site     vvhybe.com
     █████████▀         palette  #000000 #ffffff
```

```txt
vvhybe@marrakech:~$ stack --list
erp        odoo, backend
web        typescript, react, next.js
tools      bash, vim, git
learning   rust
```

---

### `cat /etc/schedule`

Two shifts, one person. The day shift pays the bills, the night shift is the fun part.

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#ffffff','primaryTextColor':'#000000','primaryBorderColor':'#8b8b8b','lineColor':'#8b8b8b','secondaryColor':'#f2f2f2','tertiaryColor':'#ffffff','clusterBkg':'#f2f2f2','clusterBorder':'#8b8b8b','titleColor':'#000000','fontFamily':'monospace'}}}%%
flowchart LR
  subgraph day["/day"]
    direction LR
    A["odoo"] --> B["erp + backend"] --> C["the bills"]
  end
  subgraph night["/night"]
    direction LR
    D["typescript + next.js"] --> E["open source"] --> F["the thrills"]
  end
  C -.-> G(["vvhybe"])
  F -.-> G
```

---

### `ls -la ~/projects`

```txt
drwxr-xr-x  papyrus            PDF rendering as a service. POST your data and a
                               template, get a job id back, GET the finished PDF.
                               Invoices, quotes, delivery notes. Made at BigBang Cloud.
drwxr-xr-x  odoo-client        type-safe JSON-RPC and XML-RPC client for Odoo 14-19.
                               Zero deps, native fetch, async pagination, retries.
drwxr-xr-x  dome               dotfiles manager in Bash. Links, hooks, backups.
drwxr-xr-x  handyscript        JavaScript utility library, with @tchisama.
drwxr-xr-x  vvhybe_os          my portfolio, as a 1-bit terminal you browse like vim.
```

[`@vvhybe/odoo-client`](https://www.npmjs.com/package/@vvhybe/odoo-client) ·
[`dome`](https://github.com/vvhybe/dome) ·
[`handyscript`](https://github.com/handyscript/handyscript) ·
[`vvhybe.com`](https://vvhybe.com)

---

### `git log --graph`

```mermaid
%%{init: {'theme':'base','themeVariables':{'git0':'#8b8b8b','git1':'#8b8b8b','git2':'#8b8b8b','gitBranchLabel0':'#000000','gitBranchLabel1':'#000000','gitBranchLabel2':'#000000','commitLabelColor':'#000000','commitLabelBackground':'#ffffff','tagLabelColor':'#000000','tagLabelBackground':'#f2f2f2','tagLabelBorder':'#8b8b8b','lineColor':'#8b8b8b','primaryTextColor':'#000000','fontFamily':'monospace'},'gitGraph':{'showCommitLabel':true,'mainBranchName':'main'}}}%%
gitGraph
  commit id: "2021-06 first shop, freelance" tag: "root"
  branch school
  commit id: "2021-09 OFPPT NTIC"
  checkout main
  commit id: "2021-12 first commit as whybe7"
  checkout school
  commit id: "2023-02 intern at M5 Tech"
  checkout main
  commit id: "2023-06 jnanin yoga site"
  merge school id: "2023-07 DTS diploma" tag: "DTS"
  commit id: "2023-11 BigBang Cloud" tag: "erp developer"
  commit id: "2025-02 dome v2"
  commit id: "2026-03 odoo-client"
  branch rust
  commit id: "2026 learning rust"
  checkout main
  commit id: "now" tag: "HEAD"
```

---

### `cat /etc/hobbies`

```txt
manga        drawn by hand, finished "someday"
camera       candid "stolen moments"
book         الشيئخيص: الشيئ (the Thing, the unknown X) comes before الشخص (the Person).
             on a writing hiatus. not abandoned.
anime        100+ watched. One Piece and Bleach still reign.
k-thrillers  consumed at an alarming rate. looking for something better than
             The Incheon Protocol.
```

---

### `cat TODO`

- [x] ship `@vvhybe/odoo-client`
- [x] turn a portfolio into a terminal you can browse like vim
- [ ] stop fighting the Rust borrow checker
- [ ] finish the manga (someday)
- [ ] get back to the book

---

### `man vvhybe`

<details>
<summary><code>:help</code> (press to open)</summary>

<br>

| keys | goes to |
| --- | --- |
| <kbd>:</kbd> <kbd>e</kbd> <kbd>work</kbd> | [vvhybe.com/work](https://vvhybe.com/work/): projects, told as case studies |
| <kbd>:</kbd> <kbd>e</kbd> <kbd>about</kbd> | [vvhybe.com/about](https://vvhybe.com/about/): who I am, and what drives me |
| <kbd>:</kbd> <kbd>e</kbd> <kbd>atelier</kbd> | [vvhybe.com/atelier](https://vvhybe.com/atelier/): sketchbook, manga, photos |
| <kbd>:</kbd> <kbd>e</kbd> <kbd>cv</kbd> | [vvhybe.com/cv](https://vvhybe.com/cv/): a man page that prints as a one-page résumé |
| <kbd>startx</kbd> | [vvhybe.com/?session=gui](https://vvhybe.com/?session=gui): the graphical session |

**Easter egg:** open devtools on [vvhybe.com](https://vvhybe.com). Something comes out. Click to squish, <kbd>Esc</kbd> sends them home.

</details>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/crawler-dark.svg">
  <img alt="a small web crawler walking across the page" src="assets/crawler-light.svg" width="820">
</picture>

```txt
-- NORMAL --                                   vvhybe/README.md   1,1   All
```

[**vvhybe.com**](https://vvhybe.com) · [**linktr.ee/vvhybe**](https://linktr.ee/vvhybe)

</div>