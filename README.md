# Learning Swift - iOS development

## Getting Started
Links úteis para aprender Swift + iOS development.
* [Desenvolver iOS App com Swift](https://developer.apple.com/library/archive/referencelibrary/GettingStarted/DevelopiOSAppsSwift/index.html#//apple_ref/doc/uid/TP40015214-CH2-SW1)
* Os pedaços de código dos exemplos abaixo são do [Swift Tour](https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html#)
* [Swift com TDD no exercism](http://exercism.io/languages/swift/exercises)

### Tentando Exercícios Swift  no exercism
* [Lista com todos os exercícios de Swift em TDD](http://exercism.io/languages/swift/exercises)
* Minhas soluções:
1. [Hello World - TDD](http://exercism.io/submissions/d17127eef148494792976ceb8c7504cc)
2. 
3. [Leap Year - TDD](http://exercism.io/submissions/a7cddfae87604cd8aec10e933a5d98a4)

* Criar o projeto no formato 
```
swift package generate-xcodeproj
```

### Aprendendo os basics da Swift

Não precisa de ; E não precisa do main() para um Hello World.
```swift
print("Hello, world!")
```
Use let para constantes e var para variáveis.
```swift
var myVariable = 42
myVariable = 50
let myConstant = 42
```
Pode especificar o tipo da variável/constante também
```swift
let explicitDouble: Double = 70
```
Pra fazer casts de variáveis que você recebe de uma forma, mas quer tratar de outra. 
Você cria uma instância do tipo esperado.
```swift
let label = "The width is "
let width = 94
let widthLabel = label + String(width)
```
Para concatenar variáveis com uma backslash
```swift
let apples = 3
let oranges = 5
let appleSummary = "I have \(apples) apples."
let fruitSummary = "I have \(apples + oranges) pieces of fruit."
```
Para formatar o código em Strings que ficam em múltiplas linhas
```swift
let quotation = """
I said "I have \(apples) apples."
And then I said "I have \(apples + oranges) pieces of fruit."
```
### Tipos de variáveis na Swift
```
Int
Float
Double
String
Character
Bool
```
### Arrays (???)
