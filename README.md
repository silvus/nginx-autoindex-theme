# Nginx autoindex theme

## Installation

Clone the repository into a root hidden .theme folder

``` shell
git clone https://github.com/silvus/nginx-autoindex-theme.git .theme
```

Add the following parameters to your nginx configuration

``` nginx
add_before_body /.theme/header.html;
add_after_body /.theme/footer.html;

autoindex_exact_size off;
autoindex on;
```

## Inspiration

https://github.com/JoseluCross/nginx-indexer
https://github.com/manala/nginx-autoindex-theme
