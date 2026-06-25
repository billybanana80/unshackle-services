# Unshackle Services

A collection of smaller services for Unshackle.

## Usage

Clone repository:

```bash
git clone https://github.com/billybanana80/unshackle-services
```

Add folder to `unshackle.yaml`:

```yaml
directories:
    services: "path/to/services"
```

See help text for each service:

```bash
unshackle dl SERVICE --help
```

## Notes

Some versions of the dependencies work better than others. These are the recommended versions as of 01/05/2026:

- [Shaka Packager](https://github.com/shaka-project/shaka-packager): v2.6.1
- [CCExtractor](https://github.com/CCExtractor/ccextractor): v0.93
- [MKVToolNix](https://mkvtoolnix.download/): latest
- [FFmpeg](https://ffmpeg.org/download.html): latest
