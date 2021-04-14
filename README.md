# owlsay

OWLSAY is a talking owl with configurable messages.

```text
              ( Hi! I'm Owlsay )
            o                   
    ,___, °                     
    [O.o]                       
    /)__)                       
    ╔”═”╗                       
    ║   ║                       
    ║   ║                       
    ╚═══╝                       
```

## Installation

To install this package just type and execute:

```bash
npm install -g owlsay
```
or
```bash
npm i owlsay
```

## How to use

To use this package, write:

```js
const example = require('owlsay')
```

* owlsay message

For a configurable message:

```js
example.sayOwl("example text")
```

Preview:

```text
              ( example text )
            o                   
    ,___, °                     
    [O.o]                       
    /)__)                       
    ╔”═”╗                       
    ║   ║                       
    ║   ║                       
    ╚═══╝                       
```

* Double owlsay message

For a double configurable message:

```js
example.sayDoubleOwl("example A", "example B")
```

Preview:

```text
                 ( example A )
               o
       ,___, °               ( example B )
       [O.o]               o   
       /)__)       ,___, °     
       ╔”═”╗       [O.o]       
       ║   ║       /)__)       
       ║   ╚════════”═”═════╗  
       ╚════════════════════╝ 
```

## Testing

For testing the package, write:


```js
example.botOwl()
```

or

```js
example.botDoubleOwl()
```

## Help

To help, write:

```js
example.thanksOwl()
```

## Notes

This package is free to use and will be updated as more owls are developed.

```text
              ( Thanks for read! )
            o                   
    ,___, °                     
    [O.o]                       
    /)__)                       
    ╔”═”╗                       
    ║   ║                       
    ║   ║                       
    ╚═══╝                       
```

## Contact

If you want to see others proyects, visit [my homepage]
(luiscorrea.prismasoftware.cl)