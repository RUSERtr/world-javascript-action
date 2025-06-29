# CREATING-TESTING-BUILDING  ACTIONS TO MARKETPLACE 🧰🖥

# Hello world JavaScript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/js-action-by-ruser@v1
with:
  who-to-greet: Mona the Octocat
```

