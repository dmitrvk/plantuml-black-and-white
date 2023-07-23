# plantuml
PlantUML Black &amp; White Style

* Only black and white colors
* Roboto as the default font
* `allowmixing` is enabled

Official PlantUML guide: https://plantuml.com/en/guide

## Usage

```plantuml
!include https://raw.githubusercontent.com/dmitrvk/plantuml/main/base.puml
```

Example:

```plantuml
'PlantUML Online Editor: https://www.planttext.com/

@startuml

!include https://raw.githubusercontent.com/dmitrvk/plantuml/main/base.puml

() A
() B

A .> B

@enduml
```

To use another font:

```plantuml
!include ...
skinparam defaultFontName Roboto Slab
```
