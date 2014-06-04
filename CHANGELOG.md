## 1.2.0 (2014-06-04)

- Remove support for column rules
- Add per-breakpoint fallbacks for columns without support for CSS3:

```scss
@include guss-columns(
    $base-class: '.advanced-test',
    $css3-columns-support: false, // Because buggy in some versions of WebKit
    $columns-fallback-width: (
        tablet: 720px,
        desktop: 940px
    ),
    $columns-fallback-columns: (
        tablet: 2,
        desktop: 4
    )
);
```

## 1.1.3 (2014-04-22)

- Require newer version of guardian/guss-css3

## 1.1.2 (2014-04-17)

- Loosen dependency versioning

## 1.1.1 (2014-03-10)

- Fix a bug in IE10 and IE11 where hovering a link in a column would change the position of the surrounding elements
- Better element distribution between columns

## 1.1.0 (2014-02-24)

- Invoke mobile layout variations using `l-row--layout-m`

## 1.0.5 (2014-02-20)

- Fix a bug in IE9 where hovering a link in a column would change the position of the surrounding elements

## 1.0.4 (2014-02-19)

- Fix a reference error in README

## 1.0.3 (2014-02-14)

- Columns container is flexible - #1

## 1.0.2 (2014-01-10)

- Cross browser bug fixes
- Flexible box model is triggerred starting on tablet


## 1.0.1 (2014-01-09)

Various cross-browser fixes:
- Allow for no rule between columns
- Elements don't break in a column pattern on older browsers
- Firefox aligns boxes properly

## 1.0.0 (2013-12-13)

Public release.
