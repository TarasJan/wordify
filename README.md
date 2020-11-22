# Wordify

## Showcase



## About
Wordify is an open source Excel Plugin that allows you to convert a numeric value to
a plaintext words for usage in receipts, invoices or any documents requiring human redable input.

The plugin currenty handles output in 7 languages with 7 currencies and values up to 2 decimal points.

The plugin adds two new methods to your Excel environment

`WORDIFY(number)` - taking in the numeric value and converting it to the same value expressed in words
`WORDIFYWITHLANGUAGEANGUNIT(number, lang, unit)` - allowing for conversion of the number to words in specific language with specific unit.

## Supported languages
1. English [en]
2. Chinese [cn] 中文
3. German [de] Deutsch
4. Japanese [jp] 日本語
5. Polish [pl] Polski
6. Russian [ru] Русский
7. Spanish [es] Español
 
## Supported units

\*Currently supported units are dollars `USD`, euro `EUR`, pounds `GBP`, yen `JPY`, zloty `PLN`, `CNY` yuan, and `RUB` rubles and `MXN` pesos)

## Dependencies

The processing is done remotely on a server which also hosts the demo available [here](num2wordz.herokuapp.com)

The processing on the server is done by an exquisite Golang library:
[humango](https://github.com/TarasJan/humango)


## Installation

The plugin is provided in a standard XLAM format. 

The instruction on installation procedure for Excel plugins can be found here:

[Official MS Support Docs](https://support.microsoft.com/en-us/office/add-or-remove-add-ins-in-excel-0af570c4-5cf3-4fa9-9b88-403625a0b460)
