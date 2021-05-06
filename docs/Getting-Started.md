# Getting-Started

> ** Heads Up!** This API is experimental and subject to change anytime without notice. It is not supported for production use. Please share your comments on GitHub.

## Usage 

```
curl -XPOST -H "Authorization: token $token" \
    https://slack.github.com/repos/:owner/:repo
    -d "$message" 
```

Where:

- "$token" is any valid GitHub token.
- "$message" is one or more valid slack attachments.