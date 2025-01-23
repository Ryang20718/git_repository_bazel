# Discussion number 33806

## Current behavior

git_repository update to a latest commit with commit set. this is a regression which was added in https://github.com/renovatebot/config-help/issues/173.

## Expected behavior

Update the commit sha to latest commit

## Current behavior
```bash
DEBUG: github/tags.findCommitOfTag: Tag undefined not found for bazelbuild/rules_typescript
DEBUG: Could not determine new digest for update.
{
  "packageName": "bazelbuild/rules_typescript"
  "datasource": "github-releases"
}

```

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/33806#discussioncomment-11934761
