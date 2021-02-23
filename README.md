# Software Support
Software implementations that support the WLCG Token Profile

# Library software

| Software      | Language | Link | Comment  |
| ------------- |----------|------|----------|
| SciTokens | C++ | https://github.com/scitokens/scitokens-cpp/ | Library that supports SciToken and AuthZ profile tokens. |

# Client and Relying Party software

| Software      | Link | Comment  |
| ------------- |------| ---------|
| mod_scitokens | https://github.com/scitokens/apache-scitokens | Apache httpd authentication module.  Example uses include authorising WebDAV access. "prototype quality" |
| dCache | https://dcache.org/ | AuthZ token support available since dCache v6.1, via the `scitoken` gPlazma module. |
| xrootd | https://xrootd.slac.stanford.edu/ | AuthZ token support available since xrootd v5.1, via scitoken plugin |

# Token issuer software

| Software      | Link | Comment  |
| ------------- |------| ---------|
| IAM           | https://github.com/indigo-iam/iam |  |
