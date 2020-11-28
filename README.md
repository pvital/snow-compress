# snow-compress

A command line interface (CLI) tool to upload and manage archives (files) in
[Amazon S3 Glacier].

"Glaciers are made up of fallen snow that, over many years, compresses into
large, thickened ice masses." [1] A glacier is formed when **snow** piles up in
one location long enough to **compress** and transform into ice, than the time
it takes to melt. 

[Amazon S3 Glacier] (Glacier) is a secure, durable, and extremely low-cost
serveless storage solution for "cold data" provided by [Amazon Web Services].
It is a good data archiving and long-term backup solution for those files you
want or have to store at low costs.

## Features

**snow-compress** is able to:

1. upload files to a Glacier vault;
2. list files stored in a Glacier vault. 


[1]: https://nsidc.org/cryosphere/glaciers/questions/what.html "What is a glacier?"
[Amazon S3 Glacier]: https://aws.amazon.com/glacier/ "Amazon S3 Glacier"
[Amazon Web Services]: https://aws.amazon.com/ "AWS"