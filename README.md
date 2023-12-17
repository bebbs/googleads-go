# googleads-go

Unofficial Go library for the Google Ad Manager API

[!WARNING]
The Go code in this module is generated from the poorly formed WSDL specification of the Google Ad Manager API. Use in production at your own risk.

### Issues / future improvements

- Only generates code for the `v202311` API
- The generated Go is not very idiomatic, and constrained by the abilities of the `gowsdl` tooling.
- We have to apply some gross hacks to the generated code to get it to compile, as the WSDL definitions are often poorly formed, and do not translate well to Go.
- The generated client library is clunky to use, and there is a lot of duplicated code between packages.
- Would be far better supported as a 1st party library maintained by Google.
 