# mt-doc-lookup

To look up Movable Type documentation.

## INSTALL

1. Put `mt-doc-lookup.el` to `load-path`.
2. Add a below code `init.el`.

```emacslisp
(require 'mt-doc-lookup)
```

## SCREENSHOT

![Screenshot](https://github.com/taiju/mt-doc-lookup-el/raw/master/artwork/screenshot.gif)

Took screenshot with using `ido` + `smex` + `ido-vertical-mode`.

## USAGE

### To look up tags

```
M-x mt-doc-lookup-tags
```

### To look up config directives

```
M-x mt-doc-lookup-config-directives
```

### To look up modifiers

```
M-x mt-doc-lookup-modifiers
```

### To look up tags, config directives and modifiers

```
M-x mt-doc-lookup
```

### CUSTOMIZE

### Set `browser-function` for mt-doc-lookup

For Example to set `w3m-browse-url`.

```
(setq mt-doc-lookup-browser-function #'w3m-browse-url)
```

Default is `eww-browse-url`.

## LICENSE

See `LICENSE`.

## COPYRIGHT

See `mt-doc-lookup.el`.
