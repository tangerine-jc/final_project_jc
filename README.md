# Morning flight punctuality

P8105 final project proposal, prepared November 11, 2026.

## Files

- [`proposal.Rmd`](proposal.Rmd): English proposal source for team review.
- [`proposal.md`](proposal.md): rendered proposal to read on GitHub.
- `proposal_requirements_zh.md`: requirement checks, submission steps, and implementation limits.
- `flight_punctuality_final.Rproj`: open this file in RStudio to use the project directory.

## Render

Open `proposal.Rmd` in RStudio and choose **Knit**. The YAML selects `github_document`; no raw data, downloads, or analysis results are required to render the proposal.

Alternatively, from this project directory:

```r
rmarkdown::render("proposal.Rmd", encoding = "UTF-8")
```

R Markdown requires `rmarkdown`, `knitr`, and Pandoc. RStudio supplies Pandoc automatically. The proposal does not install packages or change settings on a teammate's computer.

Within an editing session, leave **3–5 minutes between consecutive Knit runs**, as agreed by the team.

## Collaboration and submission

The shared repository is [tangerine-jc/final_project_jc](https://github.com/tangerine-jc/final_project_jc). Give all five members access and have everyone review their part before submission. Commit both the Rmd and its rendered Markdown. Each member should make substantive contributions during the project.

One member submits the proposal link through the course platform. Submit the team's UNI registration once using the form linked on the [course project page](https://p8105.com/final_project.html). Neither submission nor registration has been performed here.

The names and identifiers follow the user-provided list and correction. 刘峙岳's confirmed UNI is `zl3802`.

## Working scope

Keep the question focused on morning departures. Core results use descriptive comparisons and classroom tools. Weather joins, aircraft rotation chains, causal claims, a predictive app, and a nationwide flight-level regression are outside the promised deliverables. No full-data processing has been started in this repository.

The current proposal source is `proposal.Rmd` in this directory. Its implementation limits are summarized in `proposal_requirements_zh.md`.
