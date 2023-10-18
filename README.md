# Hello world docker action

Creating a Docker container action - GitHub Docs https://docs.github.com/en/actions/creating-actions/creating-a-docker-container-action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: showa-yojyo/hello-world-docker-action@v2
with:
  who-to-greet: 'showa-yojyo'
