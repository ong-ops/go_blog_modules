# go_blog_modules
Learning about Go Modules (https://go.dev/blog/using-go-modules)

## Command:

`go list -m all` -> List all dependency
`go list -m -versions rsc.io/sampler` -> List available tagged versions
`go list -m rsc.io/q...` -> Use ... for widecard
`go get golang.org/x/test` -> Upgrade dependency
`go get rsc.io/sampler@v1.3.1` -> Specific version | @latest (default)
`go doc rsc.io/quote/v3` -> Reading the docs
`go mod tidy` -> Cleanup unused dependencies
