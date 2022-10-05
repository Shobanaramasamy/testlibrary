# title-case-converter

**title-case-converter** is a simple wrapper around [title-case-converter](https://github.com/NoobSolver/title-case-converter) to convert first letter of string to capital letter.



## Install

Install through npm

    npm install title-case-converter

## Usage

Require the module

     let capitalizedWord = word.slice(0, 1).toUpperCase() + word.slice(1);

Convert with convert()

     let converted = capitalized.join(" ");
     return converted

Where

-   **text** is either a Buffer or a String to be converted
-   **toCharset** is the characterset to convert the string
-   **fromCharset** (_optional_, defaults to UTF-8) is the source charset

Output of the conversion is always a Buffer object.

Example

    let capitalized = []
    let words = sentence.split(" ") //split the sentence into words
    words.forEach(word => { 
		
        let capitalizedWord = word.slice(0, 1).toUpperCase() + word.slice(1)
         //capitalize the first letter of every word
        capitalized.push(capitalizedWord)         
    })
    let converted = capitalized.join(" ") 
    return converted

## License

**MIT**
