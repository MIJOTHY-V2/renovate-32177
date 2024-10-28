# 32177

Reproduction for issue https://github.com/renovatebot/renovate/discussions/32177

## Current behavior

Pull request for `logback-classic:1.5.12` is created, despite release not having passed `minimumReleaseAge` condition.

## Expected behavior

Pull request for `logback-classic:1.5.12` is not created until `minimumReleaseAge` period has passed.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/32177
