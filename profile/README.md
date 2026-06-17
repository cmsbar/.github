<div align="center">

<img src="https://raw.githubusercontent.com/cmsbar/.github/main/profile/logo.png" alt="CMSBar" width="88" height="88" />

# CMSBar

### Your client edits the live site. You get a pull request.

**The Git-as-CMS bar you drop into your own codebase.** Editors click anything
on the page and change it in place — every save becomes a branch and a pull
request in *your* repo. No database, no dashboard to host, no vendor. You own
every line.

[![npm](https://img.shields.io/npm/v/cmsbar?color=f0497c&label=cmsbar&logo=npm)](https://www.npmjs.com/package/cmsbar)
[![license](https://img.shields.io/npm/l/cmsbar?color=f0497c)](https://github.com/cmsbar/cmsbar/blob/main/LICENSE)
[![stars](https://img.shields.io/github/stars/cmsbar/cmsbar?color=f0497c)](https://github.com/cmsbar/cmsbar)

[**Website**](https://cmsbar.com) &nbsp;·&nbsp; [**Live playground**](https://playground.cmsbar.com) &nbsp;·&nbsp; [**Docs**](https://cmsbar.com/docs) &nbsp;·&nbsp; [**npm**](https://www.npmjs.com/package/cmsbar)

</div>

---

```sh
npx cmsbar init
```

One command scaffolds the editing bar into your project — **seven hosts**:
Next.js, React Router 7, TanStack Start, a Vite SPA, Astro, SvelteKit, and Nuxt.

### How it works

- **Your repo is the CMS.** Content is a JSON file in the repo. Drafts are
  branches, versions are open PRs, approval is a label, history is `git log`.
- **Copy-in, shadcn-style.** The CLI copies the source into your project —
  nothing phones home, nothing to subscribe to, nothing to break under you.
- **Editors never see Git.** They see *drafts*, *Save*, *Preview* and
  *Versions*. One draft = one branch = one PR = one version-in-progress.

### Repositories

| Repo | What it is |
| --- | --- |
| [**cmsbar**](https://github.com/cmsbar/cmsbar) | The product — the `npx cmsbar` CLI, the framework-neutral core, and a runnable example per host &nbsp;·&nbsp; [npm](https://www.npmjs.com/package/cmsbar) |
| [**web**](https://github.com/cmsbar/web) | Marketing site + documentation &nbsp;·&nbsp; [cmsbar.com](https://cmsbar.com) |
| [**playground**](https://github.com/cmsbar/playground) | Zero-setup live demo — edit a real page in your browser &nbsp;·&nbsp; [playground.cmsbar.com](https://playground.cmsbar.com) |
| [**cloud**](https://github.com/cmsbar/cloud) | Cloud Studio — the optional hosted control plane: token custody, approvals, editor identity &nbsp;·&nbsp; [studio.cmsbar.com](https://studio.cmsbar.com) |

### License

**MIT** — the code ships into your repo, and you own it.

<div align="center">
<sub><a href="https://cmsbar.com">cmsbar.com</a> &nbsp;·&nbsp; <a href="mailto:hello@cmsbar.com">hello@cmsbar.com</a></sub>
</div>
