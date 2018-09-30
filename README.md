### ferry
---

https://github.com/cmu-is-projects/ferry

```sh
gem 'ferry'
bundle
gem install ferry
ferry --help
ferry --to_csv production users
ferry --to_yaml development users
ferry --to_json development users
ferry --import_csv development users db/csv/import_data.csv
ferry --dump [environment]
ferry --fill [environment] [path/to/file.sql]
```

