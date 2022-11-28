# @codeadraas/basestyles

```scss
@use '@codeadraas/style/color' as theme;
@use '@codeadraas/style' with (
  $primary-color: map-get(theme.$color, 'light'),
  $primary-bg: map-get(theme.$color, 'dark')
);
```