# wkhtmltopdf for Centos7 0.12.2.1 qtwebkit

[All the binaries for Centos7 from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries-centos7": "0.12.2.1"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltoimage-amd64-centos7

vendor/bin/wkhtmltopdf-amd64-centos7
```

4. `yum install xorg-x11-fonts-75dpi`

Enjoy the bin files!
