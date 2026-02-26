```mermaid
classDiagram

class Geometry {
    +atoms: Atom[]
}

class Atom {
    +element: str
    +x: Decimal
    +y: Decimal
    +z: Decimal
    +mass: Decimal
    +charge: Decimal
}

Geometry "1" *-- "1..*" Atom