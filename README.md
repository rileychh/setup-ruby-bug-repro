# Reproductions

This repository contains minimal reproductions for various bug reports and issues.

## Structure

Each reproduction lives in its own branch, named using the pattern:

```
{org}/{repo}/{issue-number}
```

For example:
- `ruby/setup-ruby/867` - Reproduction for [ruby/setup-ruby#867](https://github.com/ruby/setup-ruby/issues/867)

## Usage

To view a specific reproduction:

```bash
git checkout {org}/{repo}/{issue-number}
```

To create a new reproduction:

```bash
git checkout -b {org}/{repo}/{issue-number}
# Add your reproduction files
git add .
git commit -m "Add reproduction for {org}/{repo}#{issue-number}"
git push -u origin {org}/{repo}/{issue-number}
```

## Available Reproductions

Browse the branches in this repository to see all available reproductions.
