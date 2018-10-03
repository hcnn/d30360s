# d30360s
* Date difference in years according to the **30/360 ICMA** daycount method
* Synonyms: 30/360 ICMA, 30/360 Eurobond Basis, ISDA-2006, 30S/360 Special German


## ISO 20022 -- A011

    "Method whereby interest is calculated based on a 30-day month and a 360-day year. Accrued interest to a value date on the last day of a month shall be the same as to the 30th calendar day of the same month, except for February. This means that a 31st is assumed to be a 30th and the 28 Feb (or 29 Feb for a leap year) is assumed to be a 28th (or 29th). It is the most commonly used 30/360 method for non-US straight and convertible bonds issued before 01/01/1999."

[link](https://www.iso20022.org/15022/uhb/mt565-16-field-22f.htm)


### Installation
```
clib install hcnn/d30360s
```

Or add to your `package.json` and run `clib install`

```
{ ...
    "dependencies": {
        "hcnn/d30360s": "0.1.0"
        ...
```

### Test and Demo
Download, compile, and run [test.c](https://github.com/hcnn/d30360s/blob/master/test.c) and [demo.c](https://github.com/hcnn/d30360s/blob/master/demo.c)

```
git clone git@github.com:hcnn/d30360s.git
cd d30360s
make deps
make validate
make showcase
```
