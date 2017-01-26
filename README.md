# eslint-config-meowyo

An [stylelint shareable config](http://stylelint.io/) for me.

## Usage

Install via:
```
$ yarn add git+https://github.com/mayognaise/stylelint-config-meowyo.git -D
```

.stylelintrc:
```
{
  "extends": "stylelint-config-meowyo"
}
```

`scripts` in package.json:
```
{
  "stylelint": "stylelint LESS_PATH --syntax less"
}
```
