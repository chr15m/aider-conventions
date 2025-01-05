Build an [aider](https://aider.chat) CONVENTIONS.md file from markdown snippets.

 * Symlink [`aider-conventions`](./aider-conventions) into your path.
 * Add your .md Markdown chunks for different technologies to the same folder.
 * Create a CONVENTIONS.md file with `aider-conventions name1 name2...`

Configure aider to use your conventions file (in `~/.aider.conf.yml`):

```yaml
read: [CONVENTIONS.md]
```
