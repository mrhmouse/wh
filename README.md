Wallhaven Scraper
=================

Usage examples:

```sh
# Get first page of 'linux' wallpapers
./wh linux

# Get second page of 'linux' wallpapers
./wh linux 2

# Download first page of 'linux' wallpapers
for url in $(./wh linux) ; do
  curl -O $url
done
```
