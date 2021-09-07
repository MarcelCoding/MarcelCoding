## Hi there 👋!

<!-- <img align="right" src="https://github-readme-stats.vercel.app/api?username=MarcelCoding&theme=dark"> -->
<!-- <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcelCoding&theme=dark"> -->

### About Me

My name is **Marcel**.<br>
I am mainly a **Java Developer**, and currently learning [Rust](https://www.rust-lang.org).<br>
<br>
Besides backends, I also work on frontends with the framework [Angular](https://angular.io).
<br>
<br>

[![Visits](https://badges.pufler.dev/visits/MarcelCoding/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)
[![Years](https://badges.pufler.dev/years/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)
[![Repos](https://badges.pufler.dev/repos/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding?tab=repositories)
[![Gists](https://badges.pufler.dev/gists/MarcelCoding?style=flat-square&color=black&logo=github)](https://gist.github.com/MarcelCoding)
[![Monthly Commits](https://badges.pufler.dev/commits/monthly/MarcelCoding?style=flat-square&color=black&logo=github)](https://github.com/MarcelCoding)

### 👷 Check out what I'm currently working on
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{ with .Repo.Description }} - {{ . }}{{ end }} ({{humanize .OccurredAt}})
{{- end}}

### 🌱 My latest projects
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{ with .Description}} - {{ . }}{{ end }}
{{- end}}

### 🔭 Latest releases I've contributed to
{{range recentReleases 5}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}){{ with .Description}} - {{ . }}{{ end }}
{{- end}}


