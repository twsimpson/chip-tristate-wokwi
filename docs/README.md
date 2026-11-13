# Wokwi Inverter Chip Example

This is a basic custom chip for [Wokwi](https://wokwi.com/).

## Pin names

| Name | Description    |
| ---- | -------------- |
| INx  | Input signal   |
| OUTx | Output signal  |
| GND  | Ground         |
| VCC  | Supply voltage |

## Usage

To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
  "dependencies": {
    "chip-inverter": "github:twsimpson/chip-template-wokwi@1.0.0"
  }
```

Then, add the chip to your circuit by adding a `chip-template` item to the `parts` section of diagram.json:

```json
  "parts": {
    ...,
    { "type": "chip-template", "id": "chip1" }
  },
```

For a complete example, see [the inverter chip test project](https://wokwi.com/projects/350946636543820370).
