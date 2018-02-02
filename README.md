# Unitwise Constants

Add fundamental physics/chemistry constants to [Unitwise](https://github.com/joshwlewis/unitwise).

## Installation

Through RubyGems:

```
$ gem install unitwise-constants
```

## Usage

In your script:

```
require 'unitwise/constants'
=> true

Unitwise::GRAVITY
=> #<Unitwise::Measurement value=9.81 unit=m/s2>
```

### Included Constants

|Constant Name|Description|Value|
|-------------|-----------|-----|
|GRAVITY      | Acceleration by Gravity on Earth  |9.81 m/s2|
|LIGHTSPEED   | Speed of Light                    |3.00E8 m/s|
|GRAVITATION  | Univeral Gravitation Constant     |6.67E-11 N.m2/kg2|
|AVOGADRO     | Avogadro's Number                 |6.02E23 1/mol|
|CHARGE       | Fundamental Unit of Charge        |1.60E-19 C|
