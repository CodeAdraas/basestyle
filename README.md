# @codeadraas/basestyles

```scss
@use '@codeadraas/basestyles/color' as theme;
@use '@codeadraas/basestyles' with (
  $primary-color: map-get(theme.$color, 'light'),
  $primary-bg: map-get(theme.$color, 'dark')
);
```