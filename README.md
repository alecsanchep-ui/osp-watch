# OSP Watch

A tool for machine shops that send jobs to outside processors (plating, anodize, heat treat): a morning list
of the jobs that need a check, with the email drafted; a ledger of expedite fees; real turn times per
processor.

**Early version.** The demo data is a fictional shop.

This repository only hosts the page. It holds no shop's data: jobs a shop enters are saved in that shop's own
browser, or in a file on its own shared drive. The page makes no network requests; its **For your IT** screen
says what it stores and how to check each statement.

`index.html` is generated. It is one file with its script and stylesheet inlined, uncompressed and commented,
so View Source shows everything that runs.
