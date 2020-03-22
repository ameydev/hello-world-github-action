# hello-world-github-action
This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

### `English`

**Required** The Laguage of the person to greet. Default `"English"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

- name: Hello World by Ameydev
  uses: ameydev/hello-world-github-action@v1.01
  language: 'Engish'
