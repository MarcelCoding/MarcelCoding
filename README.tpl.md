## Hi there 👋!

<!-- <img align="right" src="https://github-readme-stats.vercel.app/api?username=MarcelCoding&theme=dark"> -->
<!-- <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcelCoding&theme=dark"> -->

### About Me

My name is **Marcel**.
<br><br>
I'm mainly a **Java Developer**, who is currently trying to learn **Rust**. I deploy most of the stuff that I create or use using **Docker**.
<br>
Besides backends, I also work on frontends in the past mostly with the framework **Angular** but in the recent time I also used some **NuxtJS**. 

<!--
[![Visits](https://badges.pufler.dev/visits/MarcelCoding/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)
[![Years](https://badges.pufler.dev/years/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)
[![Repos](https://badges.pufler.dev/repos/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding?tab=repositories)
[![Gists](https://badges.pufler.dev/gists/MarcelCoding?style=flat-square&color=black&logo=github)](https://gist.github.com/MarcelCoding)
[![Monthly Commits](https://badges.pufler.dev/commits/monthly/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)
-->

### 👷 Check out what I'm currently working on
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{with .Repo.Description}} - {{.}}{{end}} ({{humanize .OccurredAt}})
{{- end}}

### 🌱 My latest projects
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{with .Description}} - {{.}}{{end}}
{{- end}}

### 🔭 Latest releases I've contributed to
{{range recentReleases 5}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}){{with .Description}} - {{.}}{{end}}
{{- end}}

### 🔨 Latest Pull Requests I published
{{range recentPullRequests 5}}
- [{{.Title}}]({{.URL}}) on [{{.Repo.Name}}]({{.Repo.URL}}) ({{humanize .CreatedAt}})
{{- end}}

### 📜 My recent blog posts
{{range rss "https://m4rc3l.de/blog.rss" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}

### ⭐ Recent stars
{{range recentStars 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{with .Repo.Description}} - {{.}}{{end}} ({{humanize .StarredAt}})
{{- end }}
