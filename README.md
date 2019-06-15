# Build
*#Using private repo*

Need build argument GIT_TOKEN. Set this up by passing --build-arg GIT_TOKEN=`<token>`

*#Use a specific version of dependency*

Use go get with @version or @commitid (first 12 characters) as:
`go get github.com/gohugoio/hugo@v0.55.6` or `go get github.com/gohugoio/hugo@9b48c5d6bd56`
