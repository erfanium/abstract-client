# abstract-client
This is my personal standard to create HTTP API clients

**Under development**

## Pros
Clients that have implemented this standard has these features *by default*:

### Standard
Uses web-fetch api and other low-level standart stuff.  
There's lot of http clients right now, axios, got, ky, fetch and etc. But which one is better? In my opinion **the most standard of them**. fetch is simple, works everywhere and has a big ecosystem and most importantly, it's web standard.

### Extendable
Methods and low-level api's are easly extendable.  
You can modify default fetch instance with other compatible alternatives.

### Mockable
You may create a client instance that should not actually work, for example in tests. It's not always easy without a standard that has already considered this.

### Debuggable
Uses `debug` package under the hood

### Standard Error Objects
This is often ignored but it's very important. Error objects should be expressive and must have debuggable content for both Development and Production environment
