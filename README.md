# StatusIndicator

Gives visual feedback when input is valid or invalid. For valid inpu tpaints the borders green and display a checkmark. For invalid paints the borders orange.

## Installation

In order to pull the latest version:

### npm (preferred)

```
npm i @endereco/statusindicator
```

### github

```
git clone https://github.com/Endereco/StatusIndicator.git
```

Then include StatusIndicator.js in `<header>` or before config.

## Configuration

In order to use status indicator you must specify the input field that emits events and the display element, that will get colorfull borders..

Here is an example configuration:

```
new StatusIndicator({
    'inputSelector': 'input[name="register[personal][email]"]',
    'displaySelector': 'input[name="register[personal][email]"]',
    'colors' : {
        'primaryColor' => '#fff',
        'primaryColorHover' => '#fff',
        'primaryColorText' => '#fff',
        'secondaryColor' => '#fff',
        'secondaryColorHover' => '#fff',
        'secondaryColorText' => '#fff',
        'warningColor' => '#fff',
        'warningColorHover' => '#fff',
        'warningColorText' => '#fff',
        'successColor' => '#fff',
        'successColorHover' => '#fff',
        'successColorText' => '#fff'
    }
});
```

## Dependencies

StatusIndicator relies on StatusIndicator to mark fields green on correct input.

StatusIndicator also relies on Accounting to generate the tid and track transactions.



