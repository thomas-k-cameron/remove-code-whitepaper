# What am I going to build
My product generates GUI from function signature and/or schema definition.

E.g.  You write a smart contract for Ethereum in solidity, you give the solidity code to my product and you end up with desktop software and CLI app that can invoke the contract, log the request parameters and the response.

E.g. You write a python code, which my product will automatically parses it to 

## Use Case and Merits
### a. Interface Modernization
Say you want to modernize/improve the software's interface.

Many in-house software ends up lacking the technical documentations necessary to understand the implementation. When you want to find out about the software, company needs to spend a lot of time on salvaging documents about what they had built in the past. 
Thanks to budget constraints, company will not move forward with the project and users will be forced to work on antiquated/weird UI.

By automating the generation of GUI/CLI interface, you can substantially reduce the development cost of the GUI, allowing users to modernize under tight budget constraint.

Not only this improves the productivity, it also save company from potential loss.
E.g. Citibank sent 900 Million USD instead of 7.8 Million USD thanks to bad UI design.
https://interx-labs.com/citibank-500milliondollarerror-interactiondesign/

### b. Coherent GUI & Speed Up Development
You no longer need to write GUI. GUI doesn't look the prettiest but it is prettier than randomly copy and pasted code.

Furthermore, you will get a coherent design, as the design is handled by the product.

## Anticipated Features
### a. More Source Support 
I will allow code-generation from other interfaces, such as Python, C#, COBOR, Open API ... etc

E.g. You write a python code, you throw that python code into my product, then  you end up with a desktop software that you can run the python code from the GUI interface.

### b. Design Variation
Many design scheme has been introduced in the past. I will allow users to generate GUI in different design scheme.

E.g. Material, Fluent, ...etc


# Idea
## Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making? 
1. I have worked on projects that ended up reducing the development time by 50% in the past thanks to code generation

2. Some companies and open source projects thrives thanks to it's aggressive code generation strategy.

E.g. AWS's smithy project. Every AWS SDK is code-gened; Allowing them to rapidly produce effective SDKs

E.g. Walis code-gen frontend code for interacting with the backend process

3. I worked on a decade old code-base   
Tech-lead barely understood the framework and was encouraging people to copy-and paste the cod from somewhere else, which wasn't really working.   
The software was not only lagging all the time but also having issues showing more than 70 letters, and no one knew what it was happening.  
Something similar can be said for the backend as well.  

They were spending 2 month for implementing a simple table which would only take hours if it was in a clean state.

## Who are your competitors? What do you understand about your business that they don't? 
1. Low-code/No-code tools
 
Low-code/No-code tools offer similar capacity in terms of reducing development cost.  

My product takes *remove-code* approach, where it effectively removes the need of engaging in the production al-together.  


2. Frontend engineers   
They can conduct proper task analysis and produce pretty GUI interface.  

We can compete with them because, 
- a. It can substantially reduce the cost of development  
    Unless you need to do a proper task analysis, the product's GUI is lot better.

- b. Adoption of the product forces development team to clarify interface definition

    Many in-house software do not have proper technical document and it ends up becoming a huge tech debt as it would become very difficult to understand what 
    it actually does.  
    Since the product generates it's GUI from function signature and schema definitions, dev team can quickly identify which function does what.


3. Open Source Tools. e.g. Open API, Smithy ...etc    
The aim of my product is to increase the number of things that you can do with code-generation. They may just adopt my idea to their project.

I believe we can survive by supporting exotic languages like COBOL or sell the company before it happens.

## How do or will you make money? How much could you make? 
1. Consultation  
I will come in and advice firms how to take advantage of my product

2. License Fees  
I will charge firms for using the product. 

The cost of the product will be less than what the front end engineers would cost.
