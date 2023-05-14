# What am I going to build
My product generates GUI from function signature and/or schema definition.

It looks like this.

E.g.  You write a smart contract for Ethereum in solidity, you give the solidity code to my product and you end up with desktop software and CLI app that can invoke the contract, log the request parameters and the response.

E.g. You wrote a python code but it doesn't work with  My software automatically generates the GUI interface for it.

E.g. You have a Open API definition written in JSON, this is for your internal tools. You want to create a desktop software and/or GUI with it. Instead of 

## Use Case
### Development Cost
By automating GUI/Logic mapping, it frees developers from writing redundant code.
Additionally, teams developing GUI primary by copy-and-pasting (trust me, it happens a lot), can stop doing it.

### UI Modernalization
Say you have some software written in C, Java or whatever that comes with an antiquated UI. This product reads the code and generate pretty UI on the fly.

### Continuous UI Upgrade
Decomissioning of Internet Explorer turned out to be an expensive, time consuming project for many organization.  
This product can continously upgrade the UI, keeping the software up-to-date with the best design standards.

## Competitors (includes potential competitors)
### vs ReTool
Unlike, ReTool, our product,
1. Can be used for UI modernization e.g. COBOR
2. Works directly with the programming language or the existing schema definition (i.e. Works with the existing tech debt)
3. Maps underlying logic to user interface
4. You can plug it into the CI/DC pipeline

### vs Frontend Engineers
This product is, faster and cheaper.
It cannot conduct task analysis or context specific GUI development, however, this is not the field we want to compete.

## Development Road map
- Support multiple programming languages such as COBOL
- Support multiple different design schemes e.g. Material Design, Fluent Design (as in windows) ... etc
- Smithy Compatability i.e. allow generation of AWS dashboard

## Case Study
### Citi Bank mistakenly sends 900 million USD instead of 7.8 million thanks to terrible UI 
https://interx-labs.com/citibank-500milliondollarerror-interactiondesign/

Reportedly, Citibank's internal software had one of the most confusing UI, which is cited as the primary cause of the incident.

My product can generate clearner UI, thus, preventing such incident to happen.

## How do or will you make money? How much could you make? 
1. Consultation  
I will come in and advice firms how to take advantage of my product

2. License Fees  
I will charge firms for using the product. 

The cost of the product will be less than what the front end engineers would cost.
