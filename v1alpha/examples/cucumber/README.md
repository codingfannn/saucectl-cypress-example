# saucectl cypress & cucumber example

Example running saucectl with cypress & cucumber.

## What You'll Need

The steps below illustrate one of the quickest ways to get set up. If you'd like a more in-depth guide, please check out
our [documentation](https://docs.saucelabs.com/dev/cli/saucectl/#installing-saucectl).

_If you're using VS Code, you can use [Runme](https://marketplace.visualstudio.com/items?itemName=stateful.runme) to run the following commands directly from VS Code._

### Install `saucectl`

```shell
npm install -g saucectl
```

### Set Your Sauce Labs Credentials

```shell
saucectl configure
```

## Install Local NPM Dependencies

Run the following command inside the `examples/cucumber` folder :rocket:

```bash
npm install
```

## Running The Examples

Run the following command inside the `examples/cucumber` folder :rocket:

```bash
saucectl run
```

### Running With Tags

Run the following command inside the `examples/cucumber` folder :rocket:

```bash
saucectl run --env "CYPRESS_TAGS=@smoke"
```

## The Config

[Follow me](.sauce/config.yml) if you'd like to see how saucectl is configured for this example.
