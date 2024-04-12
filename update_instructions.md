Notes to self

- To update (as explained in the github docs): `bundle update`
- To add a draft post: just drop a markdown file in _drafts
- To preview locally: `bundle exec jekyll serve`
- To preview locally, with drafts: `jekyll serve --watch --drafts --baseurl`
- Publish your draft using jekyll compose:

`bundle update && bundle jekyll serve`


```
$ bundle exec jekyll publish _drafts/my-new-draft.md 
// or specify a specific date on which to publish it

$ bundle exec jekyll publish _drafts/my-new-draft.md --date 2014-01-24
```

To publish: commit locally and git push
