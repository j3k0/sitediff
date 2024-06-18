# sitediff

> Monitor daily changes from a list of websites.

## Usage

### 1- Install dependencies

- `curl`
- `htmlq` (used for HTML documents)
- `html2text`
- `jq` (only used for JSON documents)

### 2- Create your `MONITORS.txt` file

Line format can be:

```
URL XpathQuery
URL jq jqFilter
# comment
```

- URL is passed to `curl` for downloading the content.
- XPathQuery is passed to `htmlq` to isolate the content of interest.
- jqFilter is passed to `jq`

Lines starting with `# ` are ignored.

Check `MONITORS.example.txt` for an example.

## License

GPL
