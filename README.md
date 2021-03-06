# Master's Thesis

**Title:** Generating Runtime Type Validations for JavaScript Based on the Static Type Information Provided by its Superset TypeScript  
**Author:** Fabian Pirklbauer  
**Project:** [ts-runtime](https://github.com/fabiandev/ts-runtime)  
**University:** [University of Applied Sciences Upper Austria](https://www.fh-ooe.at/en/)  
**Course of Studies:** [Interactive Media](https://www.fh-ooe.at/en/hagenberg-campus/studiengaenge/master/interactive-media/)  
  
Download the [PDF](https://github.com/fabiandev/thesis/raw/master/thesis.pdf) or [LaTeX](https://github.com/fabiandev/thesis/archive/master.zip) source, or read it online on 
[Overleaf](https://www.overleaf.com/read/zdkjpzmxqxkk).

## Abstract

Even though JavaScript's dynamic type system can be of advantage in many scenarios, it adds the risk of introducing errors. Therefore TypeScript was defined as a superset of JavaScript, with the ability to optionally add type annotations, resulting in increased code readability, scalability and maintainability. In addition, TypeScript's static compile time type checks can detect a multitude of conditions that may cause issues in the target code at runtime. Although type compatibility is checked during compilation, type information is not available in the compiled JavaScript code, i.e., at runtime. The removal of the type information is intended and is defined in the design goals of the language, even though dynamic type validations can improve the quality of the executable program. By extending the TypeScript compiler, this thesis provides an efficient method to maintain the type information for type checks at runtime. These checks are automatically generated and inserted into the resulting JavaScript code, which is helpful during the development of a project, to identify possible issues the TypeScript compiler cannot detect.

## License

[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
