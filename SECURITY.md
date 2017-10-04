# Security Issues

This document aggregates security issues (weaknesses and vulnerabilities) affecting osquery. It tracks issues in the format:

```
#PRNumber Title - (Optional CVE) - Fixed in Version - Optional Reporter
```

There are several types of issues that do not include a CVE or reporter. If you find a security issue and believe a CVE should be assigned, please contact the project maintainers in the [osquery Slack](https://osquery-slack.herokuapp.com), we are happy to submit the request and provide attribution to you. The project maintainers will tag related issues and pull requests with the [`hardening`](https://github.com/facebook/osquery/issues?q=is%3Aissue+is%3Aopen+label%3Ahardening) label. There may be changes with this label that are not directly security issues.

If you are editing this document please feel encouraged to change this format to provide more details. This is intended to be a helpful resource so please keep content valuable and concise.

- #3133 Bad output size for TLS compression - 2.4.0 - Facebook Whitehat
- #2447 Multiple fixes to macOS `crashes` - 2.0.0 - Facebook Whitehat and zzuf
- #2330 Add size checks to `package_bom` - 2.0.0 - Facebook Whitehat
- #1598 `readFile` TOCTOU error - 1.6.0 - NCC Group
- #1596 Uncaught exception in config JSON parsing - 1.6.0 - NCC Group
- #1585 Various comparisons of integers of different signs - 1.6.0 - NCC Group
- #993 Add restricted permissions to RocksDB - 1.4.5 - Anonymous security review
- #740 Add hardening compile flags and `-fPIE` - 1.4.1 - Anonymous security review
- #300 Add restricted permissions to osqueryd logging - 1.0.4