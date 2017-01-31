# 2lewd-api
API documentation for 2lewd - lewd.sx's in-progress forum software.

[View generated documentation](https://lewd.github.io/2lewd-api/)

The documentation is written in [api blueprint](https://apiblueprint.org/). The api is currently drafting in the v0 stage, so breaking changes are likely. 

## Contributing

Contributions are welcome in the form of pull requests, but discussing issues should occur on [this forum thread](https://lewd.sx/t/2lewd-discussion-thread).

## Building Documentation

Install the `apiary` gem:
```
$ gem install apiaryio
```
Run the development documentation preview server on port 8085:
```
$ apiary preview --watch --server --path=v0.apib --port=8085
```

Generate HTML docs:
```
$ apiary preview --path=v0.apib --output=v0.html
```
