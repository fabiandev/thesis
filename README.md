# Master's Thesis

**Title:** Generating Runtime Type Validations for JavaScript from the Static Type Information of its Superset TypeScript  
**Author:** Fabian Pirklbauer  
**Project:** [ts-runtime](https://github.com/fabiandev/ts-runtime)  
**University:** [University of Applied Sciences Upper Austria](https://www.fh-ooe.at/en/)  
**Course of Studies:** [Interactive Media](https://www.fh-ooe.at/en/hagenberg-campus/studiengaenge/master/interactive-media/)  
  
Download the [PDF](https://github.com/fabiandev/thesis/raw/master/thesis.pdf) or [LaTeX](https://github.com/fabiandev/thesis/archive/master.zip) source, or read it online on 
[Overleaf](https://www.overleaf.com/read/jxkrbfsdqjzw).

## Abstract

Even though JavaScript's dynamic type system can be of advantage in a lot of scenarios, it adds the risk of introducing errors. Therefore TypeScript came up with a superset of JavaScript, with the ability to optionally add type annotations, resulting in increased code readability, scalability and maintainability. In addition, TypeScript's static compile time type checks can detect a multitude of conditions that may cause issues in the target code at runtime. Although type compatibility is checked during compile time, type information is not available in the compiled JavaScript code. The removal of types is intended and is defined in the design goals of the language. Therefore extensive type checks have to be performed manually, which results in increased development effort and greater susceptibility to errors. The fact that suitable type information is available for most situations suggests that generating runtime type checks based on the existing data at compile time is technically possible. The information which is usually removed by the TypeScript compiler will be reflected in the target code to obtain it for type compatibility checks during program execution. These checks will be generated and inserted in the resulting JavaScript code automatically, which should help to identify possible issues during the development of a project the TypeScript compiler cannot detect.

## License

[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
