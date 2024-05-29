# sitediff

> Monitor daily changes from a list of websites.

## Usage

### 1- Install dependencies

- curl
- htmlq
- html2text

### 2- Create your `MONITORS.txt` file

Format:
URL XpathQuery

- URL is passed to `curl` for downloading the content.
- XPath is passed to `htmlq` to isolate the content of interest.

Lines starting with `# ` are ignored.

Check MONITORS.example.txt for an example.

## License

GPL
