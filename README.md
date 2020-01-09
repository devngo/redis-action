# Redis GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up Redis database.

Inspired by https://github.com/Harmon758/postgresql-action, @Harmon758 Thanks!

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: zhulik/redis-action@1.1.0
  with:
    redis version: '5'
    number of databases: 100
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
