# URLs

## Internal mechanism

If an URL is incomplete (lack of the scheme name, lack of resource path), LibreCast will try to do its best to complete it. LibreCast will try the HTTP scheme. If the resource path is lacking, LibreCast will try `/feed.xml`, then `feed.rss`.

## Good practices

Name your feed file `feed.xml`, serve your files using the HTTP protocol. This will ensure the availibility of your podcast to people who don't have to complete URL.